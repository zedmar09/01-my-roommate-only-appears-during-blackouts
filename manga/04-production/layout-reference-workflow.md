# Optional Manga Page Layout Reference Workflow

## Status

**OPTIONAL TROUBLESHOOTING WORKFLOW — NOT NORMAL PRODUCTION.**

The normal manga workflow is direct final-page generation from:

`page-###-production.md`

Use a separate layout reference only when direct generation repeatedly fails to preserve composition, blocking or temporary geometry, and only after the user explicitly decides to invoke this fallback.

Page 001 currently does **not** require this workflow.

---

## Normal Production

Default:

`page-###-production.md → page-###.png → review → page-###.webp`

Do not create an extra layout-reference image automatically.

---

## When This Fallback Is Appropriate

Use only when one or more problems persist across direct generations:

- panel structure keeps changing
- camera/framing repeatedly drifts
- character blocking/pose direction cannot be held
- temporary object geometry is story-critical and unstable
- exact continuity geometry cannot be preserved from the previous approved page

Examples may include late Chapter 001 Chair B pages if direct production repeatedly fails, but layout references are not mandatory merely because geometry matters.

---

## Optional Files

If explicitly invoked:

```text
page-###-layout-production.md
page-###-layout-reference.png
page-###-layout-reference.webp
```

The layout production Markdown is pre-production only.

The final `page-###-production.md` remains the final story, English-lettering and rendering authority.

---

## Layout Reference Purpose

A troubleshooting layout reference may lock:

- panel geometry
- reading flow
- camera/framing
- character blocking
- poses/gestures
- major environment/object placement
- negative space
- speech-balloon placement

It does not replace story canon or final-page production.

---

## Layout Reference Quality

If generated, use a clean content-filled 2D manga layout draft/reference rather than:

- empty boxes
- wireframes
- stick figures
- rough construction scribbles
- cinematic storyboard rendering

It may be simpler than final art, but framing and blocking must be clear enough to serve as composition authority.

---

## Language Rule — ZERO READABLE TEXT

Follow:

`manga/01-style/reader-visible-language-lock.md`

Troubleshooting layout-reference images use:

- empty dialogue balloons
- empty thought balloons/caption boxes if placement is needed
- no SFX lettering
- no readable background text
- no signs/labels/UI/document text
- no Japanese/Korean/Chinese/other scripts
- no English placeholder words
- no fake/gibberish writing

Arabic numerals are allowed only when an explicitly required numeric element such as a clock face is compositionally necessary.

Exact approved English wording belongs to the final `page-###-production.md`, not the layout image.

---

## Style A/B Policy

Do not automatically attach:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

Use only exact canonical references needed for identity/geometry.

---

## Authority Order When Fallback Is Used

1. final `page-###-production.md` — story, exact English lettering and final rendering
2. optional approved layout reference — composition only
3. character canonical WebPs — identity only
4. environment/object/effect WebPs — reusable geometry/design only
5. previous approved page — local seam continuity only

The final page must preserve the optional layout reference's composition if that reference has been explicitly approved for the page.

---

## Approval Gate

Approve an optional layout reference only if:

- panel order/rhythm works
- framing and blocking are clear
- major geometry is correct
- balloon placement is usable
- zero readable text appears
- the image remains 2D manga rather than cinematic/3D/painterly

After approval, manually convert the exact accepted PNG to WebP.

---

## Page 001 Note

`manga/04-production/arc-01/chapter-001/page-001-layout-production.md` is deprecated for normal Page 001 production.

Generate Page 001 directly from:

`manga/04-production/arc-01/chapter-001/page-001-production.md`
