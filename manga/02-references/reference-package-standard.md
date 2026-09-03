# Reference Package Standard

## Purpose

A reference package gives manga generation both **semantic authority** and **visual authority**. Text alone is insufficient for visual continuity, and an image alone is insufficient for story/identity rules.

## Centralized Approved WebP Rule

All approved final WebP visual authorities live in:

`manga/02-references/approved-webp/`

Subject folders keep their semantic files (`canon.md`, generation prompt, notes). Final WebPs are not duplicated inside those subject folders.

This gives one easy place to browse/attach every approved visual authority.

## General Approval Rule

A reusable reference is production-safe only when:

1. its `canon.md` is approved;
2. its reference-generation prompt is synchronized with that canon;
3. its PNG review candidate has been visually approved;
4. the exact approved PNG has been manually converted to WebP;
5. the WebP exists under `approved-webp/`;
6. `reference-register.md` marks the package `APPROVED`.

## Character Package

Semantic files:

```text
characters/<character-id>/
├── canon.md
├── <character-id>-reference-generation-prompt.md
└── variants/                       # optional scripted wardrobe/state notes
```

Centralized final visual:

```text
approved-webp/<character-id>-canonical.webp
```

The canonical WebP should be a compact black-and-white manga model sheet/atlas: consistent face, hair, body proportions, important angles, expressions, primary outfit construction, and permanent identifiers.

## Environment Package

Semantic files:

```text
environments/<location-id>/
├── canon.md
├── <location-id>-reference-generation-prompt.md
└── details/                        # optional text/detail authority
```

Centralized final visuals:

```text
approved-webp/<location-id>-master-atlas.webp
approved-webp/<location-id>-floor-plan.webp    # only when needed
```

The master atlas should cover the minimum reusable angles required by the story. Camera changes must not redesign geometry.

When generation-count reduction is important, a floor plan may be incorporated into the master atlas instead of becoming a separate WebP **only if** the combined atlas remains legible enough to serve as reliable spatial authority.

## Object Package

Semantic files:

```text
objects/<object-id>/
├── canon.md
└── <object-id>-reference-generation-prompt.md
```

Centralized final visual:

```text
approved-webp/<object-id>-canonical.webp
```

Small related props may share a single approved prop atlas when separate canonicals would waste generation effort.

## Effect Package

Semantic files:

```text
effects/<effect-id>/
├── canon.md
└── <effect-id>-reference-generation-prompt.md
```

Centralized final visual:

```text
approved-webp/<effect-id>-atlas.webp
```

Use for recurring supernatural marks, blackout manifestation language, impact grammar, or other effects whose appearance must remain recognizable.

## Style Authorities

The current series style uses two approved WebPs together:

- `approved-webp/series-manga-style-reference-a.webp`
- `approved-webp/series-manga-style-reference-b.webp`

They control rendering language only and never override character identity or environment geometry.

## Generation Attachment Requirement

Every generation prompt that relies on existing visual authorities must contain an explicit **Exact WebP Attachments** section using full repository paths.

The central cross-check is:

`manga/02-references/generation-attachment-map.md`

Do not say only “attach the approved style” or “use Nari reference.” Name the exact files.

## No Duplication Rule

Do not copy approved WebPs back into character/environment/chapter folders. Page/reference prompts point to the single centralized approved file. This avoids drift and keeps attachment selection simple.
