# My Roommate Only Appears During Blackouts

This repository is the active **black-and-white 2D manga** version of the project.

## Active Story Model

- **Series** — long-form canon
- **Arc** — major narrative movement
- **Chapter** — serialized installment
- **Page** — final visual storytelling unit

The active project root is `manga/`.

## Production Stack

1. `manga/00-series/` — series canon, continuity and chronology
2. `manga/01-style/` — final manga visual grammar
3. `manga/02-references/` — canonical reusable visual authorities
4. `manga/03-story/` — arcs and chapters
5. `manga/04-production/` — layout-reference pre-production and final page production

## Current Approved Reusable WebPs

Under `manga/02-references/approved-webp/`:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`
- `nari-canonical.webp`
- `nari-apartment-master-atlas.webp`
- `nari-workplace-master-atlas.webp`

Approved does not mean automatically attached. Exact attachment sets are defined in:

`manga/02-references/generation-attachment-map.md`

Style A/B are not default Chapter 001 story-page attachments.

## Image Format Workflow

1. image generation creates a PNG review candidate
2. PNG is visually reviewed
3. user manually converts the exact accepted PNG to WebP
4. approved reusable reference WebPs stay under `02-references/approved-webp/`
5. page-local layout references and final page WebPs stay under `04-production/`

## Separate Layout Reference Production

A page may use a separate composition pre-production file:

```text
page-001-layout-production.md
page-001-layout-reference.webp
page-001-production.md
page-001.webp
```

The layout reference is a clean content-filled 2D manga layout draft used to lock composition.

It is **not** an empty panel template and **not** a rough scribble sketch.

The final `page-###-production.md` generates finished final art and remains the final story-page generation authority.

## Visual Lock

Final pages must look like **finished professional black-and-white 2D hand-drawn manga**:

- clean inks
- line-weight variation
- screentone
- hatching/cross-hatching where useful
- flat graphic solid blacks where appropriate
- refined anatomy/hands
- clean manga backgrounds
- integrated speech balloons
- conventional right-to-left manga page construction

Final pages must not look rough/sketchy, glossy, cinematic, painterly, photorealistic, CGI/3D-rendered or like a vertical webtoon.

## Canon Reset

The previous full-color vertical Manhwa production is retired and recoverable through Git history. Story flow, character entrances, reveals, dialogue and chapter structure are rebuilt for the manga pipeline.