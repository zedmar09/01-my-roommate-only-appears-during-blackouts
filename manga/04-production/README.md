# Manga Production

Final story-page production uses **finished 2D black-and-white manga** and an optional separate layout-reference stage.

See:

- `manga/04-production/page-production-standard.md`
- `manga/04-production/layout-reference-workflow.md`
- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`

## Structure

```text
04-production/
├── page-production-standard.md
├── layout-reference-workflow.md
└── arc-01/
    └── chapter-001/
        ├── page-001-layout-production.md   # pre-production composition authority generator
        ├── page-001-layout-reference.webp # approved composition authority
        ├── page-001-production.md          # final page authority
        ├── page-001.webp                   # final approved page
        └── ...
```

Layout production is separate from final story-page production.

---

## English-Only Reader-Visible Text

All final story pages use **English only** for reader-visible text unless the user explicitly approves a page-specific exception before generation.

This includes dialogue, captions, thoughts, SFX, signs, labels, notes and UI.

Layout-reference images are **text-free by default**:

- speech balloons empty
- caption boxes empty
- no SFX text
- no readable signs/labels/documents/UI
- no Japanese/Korean/Chinese/other scripts
- no English placeholder words

Final English wording comes only from the final `page-###-production.md`.

Any non-English or invented reader-visible text is a regeneration failure.

---

## Story-Page Style Rule

Broad reusable Style A/B images are not automatic story-page attachments.

For Chapter 001, default story-page generation omits:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

because they can visually overpower page-specific Markdown.

The page production Markdown controls final story-page rendering and exact English lettering. Canonical character/environment WebPs control identity and geometry only.

---

## Final Manga Quality

Story pages must be finished professional 2D manga:

- clean final inks
- varied line weight
- refined anatomy
- screentone
- hatching
- flat graphic solid blacks
- conventional manga panel construction

Reject rough sketch final pages, cinematic lighting, glossy/painterly rendering, photorealism and CGI/3D.

---

## PNG → WebP Workflow

1. generate PNG review candidate
2. visually audit
3. user manually converts exact accepted PNG to WebP
4. commit approved WebP

Layout reference:

`page-###-layout-reference.png` → approve → `page-###-layout-reference.webp`

Final page:

`page-###.png` → approve → `page-###.webp`

Rejected PNGs are not canon.
