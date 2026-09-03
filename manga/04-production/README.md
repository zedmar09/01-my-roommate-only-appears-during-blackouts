# Manga Production

Production is page-based and supports a **separate layout-reference pre-production step** when composition needs to be locked before final art.

See:

- `manga/04-production/page-production-standard.md`
- `manga/04-production/layout-reference-workflow.md`

## Structure

```text
04-production/
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

The layout-production MD is optional pre-production used only when a page requires a visual composition lock.

The final `page-###-production.md` remains the final story-page generation authority.

---

## Separate Layout-Reference Workflow

When a page requires a layout reference:

1. use `page-###-layout-production.md`
2. generate `page-###-layout-reference.png`
3. review composition/blocking/framing
4. manually convert the accepted PNG to `page-###-layout-reference.webp`
5. commit it beside the page production files
6. use the separate final `page-###-production.md`
7. generate final `page-###.png`
8. review against the approved layout reference
9. manually convert the accepted final PNG to `page-###.webp`

A layout reference is a clean content-filled 2D manga layout draft, not empty boxes and not a rough scribble sketch.

---

## Story-Page Style Rule

Broad reusable Style A/B images are not automatic layout-reference or final-story-page attachments.

For Chapter 001, default story-page production omits:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

because they may visually overpower page-specific Markdown.

Canonical character/environment WebPs control identity/geometry only.

The final rendering authority is the written manga style lock plus the exact final page-production MD.

---

## Final Manga Quality

Final story pages are **finished 2D hand-drawn black-and-white manga**, not sketch output.

Required:

- clean finished ink lines
- line-weight variation
- screentone
- hatching where useful
- flat graphic solid blacks where appropriate
- refined anatomy/hands
- clean manga backgrounds
- conventional manga panel and balloon construction

Reject rough construction art, cinematic/movie-still rendering, glossy webtoon finish, painterly grayscale, photorealism and CGI/3D.

---

## Production Authority Rule

A separate layout-production MD does not compete with story authority.

- `page-###-layout-production.md` = composition pre-production only
- `page-###-layout-reference.webp` = approved composition authority
- `page-###-production.md` = final story/page generation authority
- `page-###.webp` = final approved page visual authority

---

## Artwork Storage

Review candidates:

```text
page-001-layout-reference.png
page-001.png
```

Approved production visuals:

```text
page-001-layout-reference.webp
page-001.webp
```

Rejected PNGs are not canon.