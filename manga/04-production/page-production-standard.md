# Manga Page Production Standard

## Purpose

The normal manga production model is **direct final-page generation from one self-contained page-production Markdown**:

`page-###-production.md`

Default sequence:

`page-production MD → final PNG review candidate → approval → final WebP`

A separate layout-reference workflow exists only as an **optional troubleshooting exception** when direct generation repeatedly fails to hold composition or temporary geometry.

See:

- `manga/04-production/layout-reference-workflow.md`
- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`

---

## Normal File Model

```text
page-001-production.md
page-001.png
page-001.webp
```

The page-production MD must contain everything required to generate the final page directly:

- exact attachments
- panel architecture
- framing
- blocking
- poses/actions
- environment/object state
- exact English lettering
- final 2D manga rendering rules
- rejection conditions
- continuity and QA

---

## Optional Troubleshooting Layout Model

Only when direct page generation repeatedly fails, the user may explicitly invoke:

```text
page-###-layout-production.md
page-###-layout-reference.webp
```

This is **not normal production** and must not be treated as a required gate unless the current page-production MD explicitly says so.

A troubleshooting layout reference controls composition only. The final `page-###-production.md` remains the authority for story facts, exact English text and final rendering.

Page 001 currently does **not** require a layout reference.

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

Background text default: **none**.

---

## Story-Page Style Reference Rule

Broad Style A/B images are not automatic story-page attachments.

For Chapter 001, default final story-page generation omits:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

Reason: broad visual sheets can overpower the exact page Markdown and canonical character/environment authorities.

The rendering authority for story pages is:

1. `manga/01-style/manga-style-lock.md`
2. `manga/01-style/reader-visible-language-lock.md`
3. current `page-###-production.md`
4. canonical WebPs for identity/geometry only
5. previous approved page only for local seam continuity when needed
6. optional layout reference only if explicitly invoked

Style A/B may be opted in only after page-specific testing proves they help without causing drift.

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

Reject:

- rough unfinished sketch output
- storyboard-only art
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

## Required Structure of Every `page-###-production.md`

### 1. Page Identity / Status

Specify series, arc, chapter, page, working label, status, final PNG filename and final WebP filename.

Normal status should be `READY FOR DIRECT FINAL-PAGE GENERATION` once canon/reference requirements are satisfied.

### 2. Direct Production Rule

State that the page is generated directly from the production MD and exact listed references.

If the page is one of the rare exceptions requiring a layout reference, say so explicitly. Otherwise, no layout-reference gate exists.

### 3. Exact Final-Generation Attachments

List only files needed for the final page:

- current `page-###-production.md`
- canonical character WebP(s)
- canonical environment/object/effect WebP(s)
- previous approved page WebP only when local continuity materially requires it
- optional approved layout reference only if explicitly invoked

Do not automatically attach Style A/B.

### 4. Source Authority

List story/canon/style documents used internally to compile the page. They are not generation attachments unless explicitly listed in Section 3.

### 5. Page Canvas / Size Lock

Specify orientation, exact dimensions, aspect ratio, reading direction, margins/gutters and black-and-white mode.

### 6. Page Purpose / Scenario

Specify narrative function, chronology/time, location, power/supernatural state, emotional tone and page-turn role.

### 7. Continuity Input

Freeze character/environment/object/knowledge state entering the page.

### 8. Exact Page Composition Authority

Define directly inside the MD:

- exact/target panel count
- panel hierarchy
- reading flow
- panel proportions/roles
- camera/framing intent
- character blocking
- pose/facing direction
- major environment/object placement
- balloon-placement requirements

The image generator must not invent a materially different composition.

### 9. Panel-by-Panel Blueprint

For every panel specify beat, framing, blocking, expression, actions/hands, props, environment anchors, text/balloon state and continuity output.

### 10. Exact Script / Lettering

Specify exact English dialogue, narration, thoughts, SFX and intentional silence.

Required statement:

**Reader-visible language: ENGLISH ONLY.**

Also specify the exact permitted reader-visible words and explicitly prohibit all others.

Background text default: **none**.

### 11. Balloon Requirements

When dialogue exists, specify:

- exact total balloon count when practical
- balloon type
- which panel each balloon belongs to
- correct speaker/tail
- exact English text

### 12. Character Requirements

Canonical WebPs control identity. Page production controls temporary pose/expression/wardrobe state.

### 13. Environment / Object / Effect Requirements

Canonical WebPs control reusable design/geometry. The page MD controls temporary story state.

### 14. Finished 2D Manga Style Lock

Restate page-relevant final quality requirements from `manga-style-lock.md` and the English-only language lock.

### 15. Complete Final Generation Instruction

Provide one deterministic instruction for generating exactly one final manga page PNG directly from the listed attachments.

### 16. Automatic Rejection Conditions

Include:

- panel/composition drift
- identity/geometry drift
- approved English text changed or translated
- non-English text
- fake/gibberish readable text
- unapproved background labels/UI/documents
- incorrect balloon count/ownership when specified
- anatomy failure
- wrong dimensions
- unfinished-sketch output
- cinematic/digital-render drift

### 17. Continuity Output

Freeze page-end state for the next page.

### 18. QA / Approval Record

Verify:

- exact attachment set used
- exact panel/composition requirements followed
- exact English script accuracy
- no non-English text
- no invented readable background text
- character/environment continuity
- finished manga quality
- anatomy/hands
- final PNG accepted/rejected
- approved PNG manually converted to final WebP

---

## Optional Layout-Reference Troubleshooting Standard

A `page-###-layout-production.md` may be created or used only when the user explicitly chooses the fallback because direct generation repeatedly fails composition or geometry.

If used:

- layout reference is composition authority only
- it contains zero readable text by default
- dialogue balloons remain empty
- final page production still adds exact approved English
- final `page-###-production.md` remains the story and rendering authority
- Style A/B are not automatically attached

Do not add this extra stage merely because it is available.

---

## Production Rule Summary

Normal:

**one manga page = one production MD + one PNG review candidate + one approved final WebP.**

Fallback only when genuinely needed:

**optional layout reference → final page-production MD → final PNG → final WebP.**
