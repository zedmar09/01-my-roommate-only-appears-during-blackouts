# Manga Page Layout Sketch Workflow

## Purpose

Every manga page may use a **sketch-first two-stage workflow** when exact composition and a visibly human-drawn manga result are important.

The layout sketch exists to prevent the final image generator from inventing cinematic framing, changing panel rhythm, over-polishing the page, or ignoring the page-specific Markdown.

This workflow is especially recommended for story pages where prior generation attempts drift toward glossy, heavy-black, poster-like or cinematic rendering.

---

## Stage A — Layout Sketch

Generate a page-specific manga production sketch first.

Naming:

```text
page-001-layout-sketch.png
page-002-layout-sketch.png
...
```

The PNG is a review candidate only.

After visual approval, manually convert the exact accepted PNG to:

```text
page-001-layout-sketch.webp
page-002-layout-sketch.webp
...
```

Store the approved sketch beside the page production file:

```text
manga/04-production/arc-01/chapter-001/
├── page-001-production.md
├── page-001-layout-sketch.webp
├── page-001.webp
└── ...
```

---

## Stage A Visual Goal

The sketch must look like a real manga artist's production rough / name / layout drawing.

Required:

- black-and-white only
- organic rough pencil/ink lines
- visible human line variation
- simplified but readable anatomy
- conventional manga gutters
- clear right-to-left panel order
- clear character blocking
- major prop/environment placement
- speech-balloon placement
- white paper dominant
- no polished key-art rendering
- no cinematic lighting
- no heavy digital shading
- no glossy finish

The purpose is **composition**, not final rendering.

---

## Stage A Attachments

Do not automatically attach broad style-sheet WebPs.

For story-page layout sketches, use only references that control something essential to the page, normally:

- the page's `page-###-production.md`
- required canonical character WebP(s)
- required environment atlas WebP(s)
- required object/effect WebP(s), only when essential to layout

For Chapter 001 story pages, `series-manga-style-reference-a.webp` and `series-manga-style-reference-b.webp` are **not required page-generation attachments** and should normally be omitted because their visual finish may overpower the page Markdown.

---

## Stage A Approval Gate

Approve a layout sketch only when:

- panel count/order works
- page rhythm works
- reading direction is clear
- camera/framing works as manga, not cinema
- character blocking works
- major environment geometry is correct
- dialogue balloons have usable positions
- page has convincing human-drawn sketch character
- no glossy/cinematic/heavy-black drift appears

After approval, convert the exact accepted PNG to WebP and commit it next to the production MD.

---

## Stage B — Final Manga Page

The final manga page is generated only after the approved layout sketch exists when the page production file marks the sketch as required.

Stage B attachments normally include:

1. `page-###-production.md`
2. `page-###-layout-sketch.webp`
3. required canonical character WebP(s)
4. required environment/object/effect WebP(s)
5. previous approved page WebP only when local continuity requires it

Do not automatically attach Style A/B.

---

## Stage B Authority Priority

1. page production Markdown — story/instruction authority
2. approved page layout sketch — composition authority
3. character canonical WebP — identity authority
4. environment/object/effect canonical WebP — design/geometry authority
5. previous approved page — local seam authority only

The layout sketch controls:

- panel boundaries
- panel proportions
- reading flow
- camera/framing
- character blocking
- major object placement
- negative-space structure
- balloon-placement intent

The final generator must not redesign or cinematicize the approved sketch.

---

## Human-Drawn Manga Rule

Final pages must retain human-drawn character from the approved sketch.

Cleaning is allowed, but do not transform the sketch into:

- vector-clean digital contours
- glossy illustration
- movie-still lighting
- noir/high-contrast frame
- polished concept art
- 3D/CG-derived manga
- poster/key art

Prefer:

- organic ink/pencil variation
- white paper
- restrained spot blacks
- light screentone
- hand hatching
- ordinary manga readability

If the result becomes more polished/cinematic but less human-drawn, reject it.

---

## Style A/B Rule For Story Pages

`series-manga-style-reference-a.webp` and `series-manga-style-reference-b.webp` remain approved reusable **reference-development** assets.

They may still be used when building or revising canonical reference packages if useful.

They are **not automatic story-page generation attachments**.

A page production file may explicitly opt them in only if repeated testing proves they improve that specific page without overriding the Markdown or the approved layout sketch.

Default for story-page generation: **do not attach Style A/B**.

---

## Production Gate

If a page production file declares a layout sketch required and the corresponding approved WebP does not exist:

**STOP FINAL PAGE GENERATION.**

Generate, review, approve, convert and commit the layout sketch first.
