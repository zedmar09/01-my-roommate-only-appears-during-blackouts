# Manga Page Production Standard

## Purpose

Final manga pages use one final-page production Markdown:

`page-###-production.md`

When composition must be established separately, a second **pre-production-only** Markdown is allowed:

`page-###-layout-production.md`

This layout-production file generates an approved `page-###-layout-reference.webp` used only as composition authority.

See:

- `manga/04-production/layout-reference-workflow.md`
- `manga/01-style/reader-visible-language-lock.md`

---

## File Model

Example:

```text
page-001-layout-production.md      # separate composition pre-production
page-001-layout-reference.webp     # approved composition authority
page-001-production.md             # final story-page generation authority
page-001.png                       # final-page review candidate
page-001.webp                      # final approved page authority
```

A layout production file is not required for every page. Use it where composition drift, blocking, continuity geometry, or page rhythm needs an explicit visual lock.

---

## Global Reader-Visible Language Lock — ENGLISH ONLY

All active manga production follows:

`manga/01-style/reader-visible-language-lock.md`

Default rule: **all reader-visible text is English only**.

This applies to:

- dialogue
- thought balloons
- narration/captions
- SFX
- signs
- labels
- device/UI text
- notes/messages
- book/manuscript titles
- any other readable lettering

Final pages may contain only exact English text explicitly approved in the current page-production MD.

Do not translate, paraphrase, localize, romanize or substitute approved wording.

Do not generate Japanese, Korean, Chinese, other non-English scripts, fake multilingual glyphs or unapproved readable background text.

### Layout-reference lettering rule

Layout references use:

- **EMPTY speech balloons**
- empty thought balloons/caption boxes when placement must be locked
- no SFX text
- no readable background text
- no signs/labels/UI/document text

The layout reference locks lettering **placement only**. Exact English wording is added during final page generation.

A user-approved page-specific exception may override this only when explicitly stated before generation.

---

## Final Page Gate

If `page-###-production.md` declares a layout reference required, final-page generation is blocked until:

`page-###-layout-reference.webp`

exists and is approved.

Missing required layout reference = **STOP FINAL PAGE GENERATION**.

The approved layout reference controls:

- panel count/order
- panel boundaries/proportions
- reading flow
- camera/framing
- character blocking
- poses/gestures
- major object placement
- negative space
- balloon-placement intent

The final generator must not redesign, beautify into a different composition, or cinematicize the approved layout reference.

---

## Story-Page Style Reference Rule

Broad Style A/B images are not automatic story-page attachments.

For Chapter 001, default final story-page generation omits:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

Reason: those broad visual sheets can overpower the exact page Markdown and canonical character/environment authorities.

The rendering authority for story pages is:

1. `manga/01-style/manga-style-lock.md`
2. `manga/01-style/reader-visible-language-lock.md`
3. current `page-###-production.md`
4. approved layout reference for composition only
5. canonical WebPs for identity/geometry only

Style A/B may be explicitly opted in only after page-specific testing proves they help without causing drift.

---

## Final Story-Page Quality Lock

Final pages are **finished 2D hand-drawn black-and-white manga**, not sketches.

Required:

- clean finished inks
- natural pen/brush line-weight variation
- refined anatomy and readable hands
- crisp 2D background linework
- screentone as manga tone, not painted gray
- hatching/cross-hatching where useful
- flat solid-black ink shapes where graphically appropriate
- conventional manga panel/gutter construction
- integrated speech balloons
- clean final-page readability

Do not require roughness, pencil residue, construction lines or visible sketch marks in the final page.

Reject:

- rough unfinished sketch output
- empty/storyboard-only art
- cinematic lighting
- movie-still look
- glossy webtoon rendering
- painterly grayscale
- photorealism
- CGI/3D
- smooth digital gradient shading
- bloom/lens flare/volumetric light/depth-of-field/bokeh

Solid black is allowed as flat manga ink; reject only when black behaves like cinematic lighting or digital shadow rendering.

---

## Required Structure of Every Final `page-###-production.md`

### 1. Page Identity / Status

Specify series, arc, chapter, page, label, status, final PNG filename and final WebP filename.

### 2. Production Gate

State whether an approved layout reference is required. If required, list its exact repository path.

### 3. Exact Final-Generation Attachments

List only files needed for the final page:

- current `page-###-production.md`
- approved `page-###-layout-reference.webp` when required
- canonical character WebP(s)
- canonical environment/object/effect WebP(s)
- previous approved page WebP only when local seam continuity needs it

Do not include layout-generation instructions here.

### 4. Source Authority

List story/canon/style documents used internally to compile the final page.

### 5. Page Canvas / Size Lock

Specify orientation, exact dimensions, aspect ratio, reading direction, margins/gutters and black-and-white mode.

### 6. Page Purpose / Scenario

Specify narrative function, chronology/time, location, power/supernatural state, emotional tone and page-turn role.

### 7. Continuity Input

Freeze character/environment/object/knowledge state entering the page.

### 8. Page Composition Authority

If an approved layout reference exists, state that it is binding for composition. Otherwise define exact panel architecture in the production MD.

### 9. Panel-by-Panel Blueprint

For every panel specify beat, framing, blocking, expression, actions/hands, props, environment anchors and continuity output.

### 10. Exact Script / Lettering

Specify exact English dialogue, narration, thoughts, SFX and intentional silence.

Required statement:

**Reader-visible language: ENGLISH ONLY.**

Do not allow generated paraphrasing, translation or invented text.

Also state which background text is allowed. Default: **none**.

### 11. Character Requirements

Canonical WebPs control identity. Page production controls temporary pose/expression/wardrobe state.

### 12. Environment / Object / Effect Requirements

Canonical WebPs control reusable design/geometry. The page MD controls temporary story state.

### 13. Finished 2D Manga Style Lock

Restate page-relevant final quality requirements from `manga-style-lock.md` and the English-only language lock.

### 14. Complete Final Generation Instruction

Provide one deterministic instruction for generating exactly one final manga page PNG. Explicitly require exact English lettering and prohibit all unapproved readable text.

### 15. Automatic Rejection Conditions

Include:

- layout drift
- identity/geometry drift
- approved English text changed or translated
- non-English text
- fake/gibberish readable text
- unapproved background labels/UI/documents
- anatomy failure
- wrong dimensions
- unfinished-sketch output
- cinematic/digital-render drift

### 16. Continuity Output

Freeze state for the next page.

### 17. QA / Approval Record

Verify:

- required layout reference present when applicable
- exact canonical attachments used
- layout adherence
- exact English script accuracy
- no non-English text
- no invented readable background text
- character/environment continuity
- finished manga quality
- anatomy/hands
- final PNG accepted/rejected
- approved PNG manually converted to final WebP

---

## Separate Layout Production Standard

A `page-###-layout-production.md` exists only to create the optional/required composition authority.

It should specify:

- layout-reference PNG/WebP filenames
- exact canonical attachments required for staging
- panel beats
- empty balloon/caption placement
- **zero readable text by default**
- clean content-filled 2D manga layout-reference quality
- composition QA

The exact final English script may be documented inside the layout MD for planning, but the generated layout image must keep balloons empty and must not render those words.

It must **not** become a second competing story authority.

The final `page-###-production.md` wins for story facts and exact final English lettering.

---

## Production Rule Summary

When a layout reference is required:

**layout production MD → approved text-free layout-reference WebP → final page-production MD → exact-English final PNG review → approved final WebP.**

The layout reference is generated separately. The final page is finished 2D manga, not a rough-sketch cleanup pass.
