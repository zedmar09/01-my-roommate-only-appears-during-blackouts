# Manga Page Layout Reference Workflow

## Purpose

A page may use a **separate layout-reference production step** when composition needs to be locked before final-page generation.

This step is independent from the final `page-###-production.md`.

The layout reference exists to lock:

- panel geometry
- reading flow
- camera/framing
- character blocking
- poses/gestures
- major environment/object placement
- negative space
- speech-balloon placement

It does **not** replace final page production and it does not alter story canon.

---

## Separate Production Files

When a layout reference is needed, use:

```text
page-001-layout-production.md
page-001-layout-reference.png
page-001-layout-reference.webp
page-001-production.md
page-001.png
page-001.webp
```

The layout production Markdown is a pre-production specification only.

The final page-production Markdown remains the final story/generation authority.

---

## Layout Reference Quality — NOT A Rough Sketch

The layout reference is **not** an empty panel template and it is **not** a loose scribble page.

Target: a clean, content-filled **2D manga layout draft/reference**.

Required:

- black-and-white only
- clear manga panel borders
- clean ink-like line drawing
- readable faces/expressions
- readable character poses and gestures
- understandable hands when action depends on them
- simplified but coherent perspective/backgrounds
- major props/furniture present
- speech-balloon shapes and approximate placement
- right-to-left reading flow
- enough visual information that the final-page stage does not invent new framing or blocking

It may be simpler than final art:

- less micro-detail
- simpler backgrounds
- lighter/minimal screentone
- simplified texture

But it should still look like **2D manga drawing**, not wireframes, stick figures, empty rectangles, or rough construction scribbles.

---

## Layout Reference vs Final Page

### Layout reference controls

- composition
- shot choice
- staging
- panel rhythm
- pose direction
- major object placement
- balloon placement

### Final page adds

- final clean inks
- refined anatomy/hands
- final facial detail
- final environment detail
- final screentone/hatching
- final flat solid-black design
- polished lettering integration

The final page must preserve the approved layout reference unless the user explicitly approves a composition revision.

---

## Finished Manga Direction

Even the layout reference should stay inside the project's 2D manga language.

Do not use:

- cinematic lighting
- movie-still framing logic
- painterly grayscale
- glossy rendering
- photorealism
- 3D/CG
- bloom, bokeh, depth-of-field or volumetric light

For final story pages, follow:

`manga/01-style/manga-style-lock.md`

---

## Style A/B Policy

Do not automatically attach:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

for layout-reference or final story-page generation.

Use only the exact references listed by the relevant production Markdown.

Style A/B remain available for reference-development work, but they are not default story-page authorities.

---

## Layout Reference Approval Gate

Approve only if:

- every panel contains readable story content
- panel order is clear
- page rhythm works
- camera/framing is established
- poses/blocking are established
- major environment geometry is coherent
- important props are positioned
- balloons have usable placements
- the page reads as 2D manga rather than cinema

After approval:

1. manually convert the exact approved layout PNG to WebP
2. commit `page-###-layout-reference.webp` beside the page production files
3. final page production may then use that WebP as composition authority when required

---

## Production Gate

If a final `page-###-production.md` marks a layout reference as required and the approved WebP does not exist:

**STOP FINAL PAGE GENERATION.**

The user should generate and approve the layout reference separately using its `page-###-layout-production.md`.