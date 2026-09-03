# Manga Production Root

`manga/` is the active production root for **My Roommate Only Appears During Blackouts**.

## Directory Model

```text
manga/
├── 00-series/
├── 01-style/
│   └── reader-visible-language-lock.md
├── 02-references/
│   ├── approved-webp/
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

There is no volume layer. Arcs are story units; chapters are installments inside those arcs.

## Format Lock

- black-and-white manga
- finished 2D hand-drawn ink quality
- line-weight variation
- screentone and hatching
- flat graphic solid blacks
- expressive manga simplification
- conventional manga pages, not vertical webtoon strips
- variable panel count/size/shape according to scene rhythm
- no color pipeline
- no glossy, cinematic, CGI, 3D-rendered, photoreal or painterly look

## Reader-Visible Language Lock

Global authority:

`manga/01-style/reader-visible-language-lock.md`

**All reader-visible manga text is English only** unless the user explicitly approves a page-specific exception before generation.

This covers:

- dialogue
- thoughts
- narration/captions
- SFX
- signs/labels
- notes/messages
- UI/screens
- any other readable lettering

Final pages may contain only exact English wording explicitly listed in their `page-###-production.md`.

Layout references are text-free by default: empty balloons, no SFX letters, no readable labels/documents/UI and no foreign-language or placeholder text.

Any Japanese, Korean, Chinese, other non-English script, translated dialogue, fake glyphs or invented readable text is an automatic regeneration failure.

## Layout Reference Workflow

When composition needs a separate visual authority:

1. use `page-###-layout-production.md`
2. generate `page-###-layout-reference.png`
3. review composition with empty balloons / zero readable text
4. manually convert approved PNG to `page-###-layout-reference.webp`
5. commit beside final page-production MD
6. generate final page from `page-###-production.md`
7. add exact approved English lettering only in final generation

## Story-Page Attachments

Do not attach every visual reference automatically.

For Chapter 001, Style A/B are not default story-page attachments because they may overpower the exact production Markdown.

Canonical character/environment WebPs control identity and geometry only. Page Markdown controls final rendering and lettering.

See:

`manga/02-references/generation-attachment-map.md`

## PNG → WebP Workflow

Generated PNGs are review candidates.

After visual approval, the user manually converts the exact accepted PNG to WebP.

Approved reusable reference WebPs live under:

`manga/02-references/approved-webp/`

Approved page layout-reference and final page WebPs stay beside their production MDs under `manga/04-production/`.

## Authority Order

1. current explicit user instruction
2. `00-series/` canon and continuity
3. current approved story files under `03-story/`
4. `01-style/reader-visible-language-lock.md`
5. `01-style/manga-style-lock.md`
6. current page production Markdown
7. approved layout reference for composition only
8. canonical reusable WebPs for identity/geometry
9. previous approved page only for local continuity

Never let a visual reference override exact English script or introduce readable text not authorized by the production MD.
