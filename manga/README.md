# Manga Production Root

`manga/` is the active production root for **My Roommate Only Appears During Blackouts**.

## Directory Model

```text
manga/
├── 00-series/
├── 01-style/
├── 02-references/
│   ├── approved-webp/
│   ├── characters/
│   ├── environments/
│   ├── objects/
│   ├── effects/
│   ├── generation-attachment-map.md
│   └── reference-register.md
├── 03-story/
└── 04-production/
    ├── page-production-standard.md
    ├── layout-reference-workflow.md
    └── arc-01/
        └── chapter-001/
            ├── page-001-layout-production.md
            ├── page-001-layout-reference.webp
            ├── page-001-production.md
            ├── page-001.webp
            └── ...
```

There is no volume layer. Arcs are major story units; chapters are installments inside arcs.

## Format Lock

Final story pages are:

- black-and-white
- finished **2D hand-drawn manga**
- clean inked line art
- natural line-weight variation
- screentone
- hatching/cross-hatching where useful
- flat graphic solid-black ink shapes where appropriate
- expressive manga simplification
- conventional manga page construction
- right-to-left reading

Final pages are **not rough sketches**.

Reject glossy/cinematic, painterly, photoreal, CGI/3D, airbrushed-gradient or vertical-webtoon rendering.

## Layout Reference Model

When composition needs to be locked, the layout reference is generated separately:

```text
page-###-layout-production.md
→ page-###-layout-reference.png
→ approve/manual WebP conversion
→ page-###-layout-reference.webp
```

The layout reference is a clean content-filled 2D manga composition draft, not empty boxes and not a rough scribble sketch.

Final generation then uses:

`page-###-production.md`

The final page-production MD controls final story/page generation. The approved layout reference controls composition only.

## PNG → WebP Workflow

All generated visuals are PNG review candidates first.

After approval, the user manually converts the exact accepted PNG to WebP.

Reusable approved character/environment/style reference WebPs live under:

`manga/02-references/approved-webp/`

Page-local layout-reference and final page WebPs stay under `04-production/` beside their production files.

## Style A/B Policy

Approved Style A/B WebPs remain reference-development assets.

They are **not default Chapter 001 story-page attachments** because they can overpower page-specific Markdown.

Use the exact attachment set in:

`manga/02-references/generation-attachment-map.md`

Do not attach every approved reference automatically.

## Production Authority

For a page using a layout reference:

1. current user instruction
2. series/arc/chapter story canon
3. `manga/01-style/` text style rules
4. final `page-###-production.md` for page facts/script/final generation
5. approved `page-###-layout-reference.webp` for composition
6. canonical character/environment/object/effect WebPs for identity/geometry
7. previous approved page WebP for local seam continuity only

A required authority missing from production blocks generation; do not improvise a substitute.