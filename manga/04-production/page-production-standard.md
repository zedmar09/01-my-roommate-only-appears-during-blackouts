# Manga Page Production Standard

## Purpose

Every manga page uses exactly one self-contained `page-###-production.md` as its story and generation authority.

When composition drift is a risk, the page uses the sketch-first workflow defined in:

`manga/04-production/layout-sketch-workflow.md`

The page-specific production MD controls both Stage A sketch generation and Stage B final-page generation.

---

## Page File Naming

Production authority:

```text
page-001-production.md
page-002-production.md
...
```

Optional/required approved layout authority:

```text
page-001-layout-sketch.webp
page-002-layout-sketch.webp
...
```

Final page review candidate:

```text
page-001.png
page-002.png
...
```

Final approved page authority after manual conversion:

```text
page-001.webp
page-002.webp
...
```

---

## Two-Stage Workflow

### Stage A — Layout Sketch

If the page production MD marks a layout sketch as required, generate the sketch first.

Review candidate:

`page-###-layout-sketch.png`

After approval, manually convert the exact accepted PNG to:

`page-###-layout-sketch.webp`

The approved sketch becomes the composition authority for Stage B.

### Stage B — Final Manga Page

Do not generate the final page until the required approved layout sketch exists.

The final page must preserve the approved sketch's:

- panel count/order
- panel boundaries
- relative panel sizes
- camera/framing
- character blocking
- major object placement
- negative space
- balloon-placement intent

Do not redesign, beautify or cinematicize an approved layout sketch.

---

## Story-Page Style Reference Rule

Broad reusable style sheets are not automatic story-page attachments.

For Chapter 001, the default is:

**Do not attach**

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

when generating story-page sketches or final story pages.

Reason: broad visual style sheets may overpower page-specific Markdown, canonical story references and the approved layout sketch.

The written manga style lock and page-production MD control rendering for story pages.

Style A/B remain useful as reference-development assets and may only be opted into a page explicitly after testing proves they do not cause drift.

---

## Required Structure of Every `page-###-production.md`

### 1. Page Identity / Status

Specify:

- series
- arc
- chapter
- page number
- working label
- production status
- Stage A sketch filename when required
- Stage B PNG filename
- final WebP filename

Recommended statuses include:

- `LAYOUT SKETCH REQUIRED`
- `LAYOUT SKETCH REVIEW`
- `READY FOR FINAL PAGE`
- `VISUAL REVIEW`
- `APPROVED`
- `BLOCKED`

### 2. Stage / Production Gate

State whether the page requires Stage A before Stage B.

If required sketch is missing:

**STOP FINAL PAGE GENERATION.**

### 3. Exact Required Attachments

Separate Stage A and Stage B attachments.

Use only references controlling something visible or structurally important.

Typical Stage A:

- page production MD
- character canonical WebP(s)
- environment canonical WebP(s)
- object/effect authority only if essential to layout

Typical Stage B:

- page production MD
- approved page layout sketch WebP
- character canonical WebP(s)
- environment/object/effect canonical WebP(s)
- previous approved page WebP when local continuity requires it

Do not automatically attach broad style sheets.

### 4. Source Authority

List story/canon/style documents used to compile the page. These are internal audit sources unless explicitly required as generation attachments.

### 5. Page Canvas / Size Lock

Specify:

- orientation
- pixel dimensions
- aspect ratio
- reading direction
- margins/gutters
- color mode

### 6. Page Purpose / Scenario

Specify:

- narrative purpose
- chronology/time
- location
- normal/supernatural/power state
- emotional tone
- page-turn role

### 7. Continuity Input

Freeze page-entry state:

- character state
- wardrobe/hair
- positions/facing
- held objects
- environment state
- doors/lights/devices
- knowledge state
- prior-page seam facts

### 8. Page Composition / Layout Blueprint

Define:

- target panel count
- reading order
- major page rhythm
- dominant panels
- essential beats

For Stage A, exact percentages are guidance only unless story-required. A natural manga layout may refine them.

After Stage A approval, the approved layout sketch becomes binding Stage B composition authority.

### 9. Panel-by-Panel Blueprint

For each panel define:

- narrative beat
- framing intent
- location anchors
- character blocking
- expressions/gaze
- hands/actions
- object state
- required foreground/background details
- what must remain outside crop
- continuity output

### 10. Exact Script / Lettering

Specify exact:

- dialogue
- thought balloons
- captions
- SFX
- intentional silence

Do not let image generation paraphrase or invent reader-visible text.

### 11. Character Requirements

Restate only page-relevant character requirements.

Canonical WebPs control identity, not rendering finish or composition.

### 12. Environment / Object / Effect Requirements

Canonical environment/object/effect WebPs control design and geometry, not cinematic finish.

### 13. Human-Drawn Manga Style Lock

Every story page must remain visibly human-drawn.

Required:

- organic pencil/ink lines
- pressure variation
- natural imperfection
- line-driven forms
- substantial white paper
- restrained spot blacks
- light screentone/hatching as needed
- natural anatomy/readable hands
- conventional manga panel/balloon integration

Allowed:

- subtle sketch energy
- faint construction residue when intentional/readable
- hand irregularity

Reject:

- cinematic lighting
- movie-still composition
- poster/key-art finish
- glossy webtoon rendering
- excessive black masses
- heavy chiaroscuro on ordinary scenes
- airbrushed gradients
- painterly grayscale
- photorealism
- CGI/3D
- vector-clean plastic lines
- bloom/lens flare/volumetric light/DOF blur/bokeh

If output becomes more polished/cinematic but less human-drawn, reject it.

### 14. Stage A Generation Instruction

When a sketch is required, provide one deterministic instruction for generating a rough manga page layout sketch.

The sketch is for:

- composition
- panel rhythm
- blocking
- camera/framing
- balloon placement

It is not final key art.

### 15. Stage A Rejection Conditions

Reject if:

- sketch looks like polished illustration
- layout is unreadable
- reading order fails
- blocking does not support final page
- major environment geometry fails
- cinematic/heavy-black rendering dominates

### 16. Stage B Generation Instruction

State explicitly that final artwork must follow the approved layout sketch and may not redesign it.

### 17. Stage B Automatic Rejection Conditions

Include:

- missing required layout sketch
- material layout departure
- framing/blocking drift
- identity drift
- environment drift
- dialogue/text drift
- cinematic/glossy/heavy-black drift
- anatomy/hands failure
- wrong dimensions

### 18. Continuity Output

Freeze page-end state for the next page.

### 19. QA / Approval Record

Record Stage A and Stage B separately.

Stage A:

- sketch generated
- sketch reviewed
- composition approved/rejected
- sketch converted to WebP
- WebP repository path verified

Stage B:

- approved sketch attached
- canonical refs attached
- page generated
- sketch adherence reviewed
- script accuracy
- character/environment continuity
- style compliance
- final PNG accepted/rejected
- final WebP conversion completed

---

## One-Page / One-MD Rule

The sketch-first workflow does **not** create a second page-specific Markdown blueprint.

One page still has one production Markdown:

`page-###-production.md`

That MD controls both the layout-sketch stage and final-page stage.

The approved `page-###-layout-sketch.webp` is a visual production authority, not a second textual production specification.

---

## Production Rule Summary

When sketch-first is required:

**one manga page = one production MD + one approved layout-sketch WebP + one PNG final review candidate + one approved final page WebP.**

Generate sequentially and do not skip the layout approval gate.
