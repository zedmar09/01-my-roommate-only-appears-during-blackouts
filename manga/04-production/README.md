# Manga Production

Final story-page production uses **direct generation from one page-production Markdown** and targets finished 2D black-and-white manga.

See:

- `manga/04-production/page-production-standard.md`
- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`
- `manga/04-production/layout-reference-workflow.md` — optional troubleshooting only

## Normal Structure

```text
04-production/
├── page-production-standard.md
├── layout-reference-workflow.md          # optional fallback only
└── arc-01/
    └── chapter-001/
        ├── page-001-production.md        # complete direct final-page authority
        ├── page-001.webp                 # final approved page
        ├── page-002-production.md
        ├── page-002.webp
        └── ...
```

Normal page sequence:

`page-###-production.md → page-###.png → review → page-###.webp`

A separate layout reference is **not required by default**.

---

## Page 001

Page 001 is generated directly from:

1. `page-001-production.md`
2. `nari-canonical.webp`
3. `nari-workplace-master-atlas.webp`

Do not attach:

- Style A/B
- `page-001-layout-production.md`
- `page-001-layout-reference.webp`

The old Page 001 layout-production file remains only as a deprecated troubleshooting pointer.

---

## English-Only Reader-Visible Text

All final story pages use **English only** for reader-visible text unless the user explicitly approves a page-specific exception before generation.

This includes dialogue, captions, thoughts, SFX, signs, labels, notes and UI.

Each final page-production MD must list exact permitted English wording.

Background text default: **none**.

Any non-English, translated, invented or fake readable text is a regeneration failure.

---

## Story-Page Style Rule

Broad reusable Style A/B images are not automatic story-page attachments.

For Chapter 001, default story-page generation omits:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

because they can visually overpower page-specific Markdown.

The page-production Markdown controls final composition, rendering and exact English lettering. Canonical character/environment WebPs control identity and geometry only.

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

## Optional Layout-Reference Troubleshooting

Use `layout-reference-workflow.md` only when direct generation repeatedly fails panel composition, blocking or story-critical temporary geometry.

If invoked, the layout reference is text-free and controls composition only. It does not replace the final page-production MD.

Do not add this stage merely because it exists.

---

## PNG → WebP Workflow

1. generate final PNG review candidate
2. visually audit
3. user manually converts exact accepted PNG to WebP
4. commit approved WebP

Final page:

`page-###.png` → approve → `page-###.webp`

Rejected PNGs are not canon.
