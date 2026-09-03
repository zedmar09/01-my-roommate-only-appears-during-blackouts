# Reference Package Standard

## Purpose

A reference package gives manga generation both **semantic authority** and **visual authority**. Text alone is insufficient for visual continuity, and an image alone is insufficient for story/identity rules.

## General Approval Rule

A reusable reference is production-safe only when:

1. its `canon.md` is approved;
2. its reference-generation prompt is synchronized with that canon;
3. the generated reference image has been visually approved;
4. the approved repository image exists as `.webp`;
5. `reference-register.md` marks the package APPROVED.

Intermediate PNG/JPEG generations are not canon. Prefer lossless WebP for line-art preservation.

## Character Package

```text
characters/<character-id>/
├── canon.md
├── <character-id>-reference-generation-prompt.md
├── <character-id>-canonical.webp
└── variants/                       # optional scripted wardrobe/state references
```

The canonical WebP should be a compact black-and-white manga model sheet/atlas: consistent face, hair, body proportions, important angles, expressions, primary outfit construction, and permanent identifiers. Generate one useful atlas instead of many redundant single-view images.

## Environment Package

```text
environments/<location-id>/
├── canon.md
├── <location-id>-reference-generation-prompt.md
├── <location-id>-master-atlas.webp
├── <location-id>-floor-plan.webp    # only when spatial continuity needs it
└── details/                         # optional critical architectural details
```

The master atlas should cover the minimum reusable angles required by the story. Camera changes must not redesign geometry.

When generation-count reduction is important, a floor plan may be incorporated into the master atlas instead of becoming a separate WebP **only if** the combined atlas remains legible enough to serve as a reliable spatial authority. Do not force a separate generation merely for folder symmetry.

## Object Package

```text
objects/<object-id>/
├── canon.md
├── <object-id>-reference-generation-prompt.md
└── <object-id>-canonical.webp
```

Small related props may share a single approved prop atlas when separate canonicals would waste generation effort.

## Effect Package

```text
effects/<effect-id>/
├── canon.md
├── <effect-id>-reference-generation-prompt.md
└── <effect-id>-atlas.webp
```

Use for recurring supernatural marks, blackout manifestation language, impact grammar, or other effects whose appearance must remain recognizable.

## No Duplication Rule

Do not copy canonical WebPs into every chapter or page folder. Each page's single `page-###-production.md` lists the exact approved files it requires under its attachment/reference section. This avoids drift and keeps the repository small.
