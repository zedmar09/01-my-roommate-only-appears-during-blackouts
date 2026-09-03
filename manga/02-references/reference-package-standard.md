# Reference Package Standard

## Purpose

A reference package gives manga generation both **semantic authority** and **visual authority**. Text alone is insufficient for visual continuity, and an image alone is insufficient for story/identity rules.

## Image Format Workflow

Follow `manga/02-references/image-format-workflow.md` for every generated reference image.

The required sequence is:

1. ChatGPT/image generation creates the first candidate as `.png`.
2. The PNG is reviewed visually.
3. If approved, the user manually converts that exact approved PNG to `.webp`.
4. Only the converted WebP is committed/stored as the final visual authority.

So throughout this repository:

- `.png` means **generated review candidate**
- `.webp` means **approved final repository authority**

Do not ask the image generator to produce WebP as its first output.

## General Approval Rule

A reusable reference is production-safe only when:

1. its `canon.md` is approved;
2. its reference-generation prompt is synchronized with that canon;
3. its PNG generation candidate has been visually approved;
4. that exact approved PNG has been manually converted to WebP;
5. the approved repository `.webp` exists;
6. `reference-register.md` marks the package `APPROVED`.

Rejected or intermediate PNG/JPEG generations are never canon.

## Character Package

```text
characters/<character-id>/
├── canon.md
├── <character-id>-reference-generation-prompt.md
├── <character-id>-canonical.webp
└── variants/                       # optional scripted wardrobe/state references
```

Generation candidate before manual conversion:

`<character-id>-canonical.png`

Final repository authority after approval/manual conversion:

`<character-id>-canonical.webp`

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

The generator first produces matching PNG candidates such as:

```text
<location-id>-master-atlas.png
<location-id>-floor-plan.png
```

After visual approval, the user manually converts the accepted PNG(s) to the WebP paths shown in the package structure.

The master atlas should cover the minimum reusable angles required by the story. Camera changes must not redesign geometry.

When generation-count reduction is important, a floor plan may be incorporated into the master atlas instead of becoming a separate final WebP **only if** the combined atlas remains legible enough to serve as a reliable spatial authority. Do not force a separate generation merely for folder symmetry.

## Object Package

```text
objects/<object-id>/
├── canon.md
├── <object-id>-reference-generation-prompt.md
└── <object-id>-canonical.webp
```

Generate `<object-id>-canonical.png` first; after approval, manually convert that exact candidate to `<object-id>-canonical.webp`.

Small related props may share a single approved prop atlas when separate canonicals would waste generation effort.

## Effect Package

```text
effects/<effect-id>/
├── canon.md
├── <effect-id>-reference-generation-prompt.md
└── <effect-id>-atlas.webp
```

Generate `<effect-id>-atlas.png` first; after approval, manually convert that exact candidate to `<effect-id>-atlas.webp`.

Use effect packages for recurring supernatural marks, blackout manifestation language, impact grammar, or other effects whose appearance must remain recognizable.

## No Duplication Rule

Do not copy canonical WebPs into every chapter or page folder. Each page's single `page-###-production.md` lists the exact approved files it requires under its attachment/reference section. This avoids drift and keeps the repository small.
