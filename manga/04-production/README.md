# Manga Production

Production remains **single-authority Markdown per manga page**, with an optional/required approved layout-sketch visual authority.

See:

- `manga/04-production/page-production-standard.md`
- `manga/04-production/layout-sketch-workflow.md`

## Structure

```text
04-production/
├── page-production-standard.md
├── layout-sketch-workflow.md
└── arc-01/
    └── chapter-001/
        ├── page-001-production.md
        ├── page-001-layout-sketch.webp   # approved composition authority when required
        ├── page-001.webp                 # final approved page authority
        ├── page-002-production.md
        └── ...
```

There is still exactly one page-specific production Markdown per manga page.

The optional/required `page-###-layout-sketch.webp` is a visual composition authority, not a second textual blueprint.

---

## Sketch-First Workflow

When a page production MD marks a layout sketch required:

1. generate `page-###-layout-sketch.png`
2. review its panel rhythm, blocking, framing and human-drawn manga quality
3. manually convert the exact approved sketch PNG to `page-###-layout-sketch.webp`
4. commit that WebP beside the page production MD
5. only then generate the final `page-###.png`
6. review the final page against the approved sketch
7. manually convert the accepted final PNG to `page-###.webp`

Missing required layout sketch = **STOP FINAL PAGE GENERATION**.

---

## Story-Page Style Rule

Broad reusable Style A/B images are not automatic story-page attachments.

For Chapter 001, default story-page generation omits:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

because they can visually overpower page-specific Markdown and cause polished/cinematic/heavy-black drift.

The page production Markdown controls story-page rendering. Canonical character/environment WebPs control identity and geometry only.

---

## Human-Drawn Requirement

Story pages must remain visibly human-drawn manga:

- organic pencil/ink line variation
- white paper
- restrained blacks
- light screentone/hatching
- natural anatomy
- conventional manga page construction

Reject cinematic, glossy, poster-like, noir, painterly, photoreal, CGI/3D or plastic/vector-clean rendering.

---

## One-Page / One-MD Rule

A `page-###-production.md` must contain everything needed to:

- generate the optional/required layout sketch
- approve the layout
- generate the final page
- verify script/reference adherence
- record QA and continuity

Do not split a page into separate prompt, blueprint, dialogue or QA Markdown files.

---

## Artwork Storage

Intermediate review candidates:

```text
page-001-layout-sketch.png
page-001.png
```

Approved repository authorities:

```text
page-001-layout-sketch.webp
page-001.webp
```

Rejected PNGs are not canon.
