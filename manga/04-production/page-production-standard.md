# Manga Page Production Standard

## Purpose

Every manga page is generated from exactly **one self-contained production Markdown file**.

Naming:

```text
page-001-production.md
page-002-production.md
page-003-production.md
```

## Image Format Workflow

Every manga page is generated as PNG first.

```text
page-001.png
page-002.png
page-003.png
```

These PNGs are intermediate visual-review candidates only.

After a PNG passes page QA, the user manually converts that exact approved PNG to the final repository authority:

```text
page-001.webp
page-002.webp
page-003.webp
```

Only the final WebP becomes canonical page/continuity authority. Do not ask image generation to output WebP directly.

See `manga/02-references/image-format-workflow.md`.

Do not create separate page prompt, blueprint, reference-manifest, dialogue, script, or QA Markdown files.

---

## Required Structure of Every `page-###-production.md`

### 1. Page Identity / Status

Specify:

- series
- arc
- chapter
- page number
- page title/working label if useful
- production status: `BLOCKED`, `READY`, `GENERATED`, `VISUAL REVIEW`, `APPROVED`, or `RETIRED`
- exact PNG generation candidate filename: `page-###.png`
- exact final WebP authority filename: `page-###.webp`

### 2. Source Authority

List the exact approved story and canon files from which this page is compiled. At minimum include the relevant current authorities under:

- `manga/00-series/`
- `manga/03-story/arc-##/chapter-###/`
- `manga/01-style/`
- `manga/02-references/reference-register.md`

The page file may compile these sources but must not silently alter their facts.

### 3. Exact Required Attachments / References

List every file that must be attached or consulted for generation, using exact repository paths.

Separate `REQUIRED` from `OPTIONAL`.

Typical categories:

```text
STYLE
- ...md
- ...webp

CHARACTERS
- .../canon.md
- .../canonical.webp

ENVIRONMENTS
- .../canon.md
- .../master-atlas.webp
- .../floor-plan.webp          # when required

OBJECTS
- .../canon.md
- .../canonical.webp

EFFECTS
- .../canon.md
- .../atlas.webp

LOCAL CONTINUITY
- previous approved page WebP  # when needed
```

Every required reusable WebP must be `APPROVED` in `manga/02-references/reference-register.md`.

Missing required reference = **STOP GENERATION**.

### 4. Page Canvas / Size Lock

Specify exact production geometry for the PNG generation candidate:

- orientation
- pixel width
- pixel height
- aspect ratio
- trim/border/safe-area rules if applicable
- reading direction once series reading direction is approved
- whether artwork may bleed to page edge

The manual PNG → WebP conversion must preserve the approved page geometry. The external page canvas remains consistent with the approved series page specification. Story variation comes from panel composition inside the page.

### 5. Page Purpose / Scenario

Specify what this page accomplishes narratively:

- page purpose
- active event thread(s)
- chronology / exact relative timing
- location
- time of day
- weather when relevant
- normal/supernatural/power state
- emotional tone
- scene context entering the page
- page-turn function / reveal target

### 6. Continuity Input

Freeze all inherited state that matters when the page begins:

- character positions
- poses / facing direction
- wardrobe / damage / wet-dry state
- held objects and which hand holds them
- object positions and states
- doors/windows/lights/device states
- environment orientation
- injuries or marks
- supernatural/power state
- dialogue knowledge state
- prior-page visual seam facts

### 7. Page Composition / Panel Architecture

Specify:

- total panel count
- reading order
- approximate panel dimensions or relative percentages
- row/column relationship where useful
- dominant panel(s)
- inset/reaction panels
- gutter size/rhythm
- border treatment
- bleed panels if any
- intentional blank/negative space

Panel count and panel sizes are **not fixed** across pages. They must follow the story rhythm.

### 8. Complete Panel-by-Panel Blueprint

For **every panel**, specify all applicable details:

- panel number
- narrative beat
- approximate panel size / hierarchy
- camera framing and angle
- lens/perspective intent without photographic/cinematic styling
- environment/location anchors
- character(s) present
- exact pose, blocking, gaze, expression, hand action, body direction
- object/prop position and state
- supernatural/effect state
- action sequence
- reaction sequence
- required foreground/background details
- what must remain outside the crop
- continuity inherited from previous panel
- continuity state passed to next panel

### 9. Exact Script / Lettering

For every panel include the exact reader-visible text in final form:

- dialogue
- thought balloons
- narration/captions
- SFX
- signs/screens only when story-required
- intentional silence

Specify speaker/source, balloon type, placement priority, and reading order when needed.

Do not let image generation invent or paraphrase dialogue.

### 10. Character Requirements

Restate only page-relevant character requirements that cannot be safely inferred from the attached canon:

- temporary wardrobe
- temporary hairstyle state
- expression
- emotional state
- pose/action
- injuries
- carried/held items
- interaction rules

Canonical identity still comes from the approved character `.md` + final `.webp` package. PNG reference candidates are not valid production attachments.

### 11. Environment / Object / Effect Requirements

State page-specific requirements such as:

- exact room/area used
- camera-consistent geometry
- furniture/door/window positions
- required architectural anchors
- object scale
- prop state
- device state
- blackout/electrical state
- recurring effect appearance/state

References control design. The page file controls temporary story state.

### 12. Page-Wide Manga Style Lock

At minimum enforce:

- black-and-white manga only
- hand-drawn pencil/ink impression
- intentional variable line weight
- screentone, hatching, cross-hatching, and solid blacks as appropriate
- natural anatomy and readable hands
- detailed backgrounds when storytelling needs them
- simplified backgrounds when emotion/dialogue benefits from reduction
- expressive manga abstraction where appropriate
- no color
- no glossy/webtoon finish
- no photorealism
- no CGI/3D render look
- no painterly/airbrushed rendering
- no cinematic grading, bloom, lens flare, volumetric light, or depth-of-field blur
- no production labels, panel IDs, filenames, crop guides, QA notes, or metadata inside reader-facing artwork

### 13. Complete Generation Instruction

Provide one final deterministic instruction that tells the image generator to create **exactly one complete manga page as PNG** using the page canvas, attached approved WebP references, panel architecture, script, actions, scenario, continuity, and visual rules defined above.

The generation instruction must not leave essential story decisions to the image model.

### 14. Automatic Rejection Conditions

List page-specific failures that require regeneration, including as applicable:

- wrong panel count/order
- missing/extra character
- character identity drift
- environment mirroring/redesign
- incorrect object state
- wrong hand/object continuity
- missing or changed dialogue/SFX
- invented text
- wrong chronology/event order
- missing reveal
- anatomy/hand failure
- incorrect page dimensions
- color/glossy/3D/cinematic drift
- unreadable composition

### 15. Continuity Output

Freeze the state at page end for the next page:

- character positions
- expressions / direction
- held objects
- environment/device/door/light states
- supernatural/power state
- unresolved motion/action
- knowledge/dialogue state
- page-turn reveal state

### 16. QA / Approval Record

The same page-production MD also holds its QA result. Record:

- PNG candidate generated
- PNG candidate reviewed
- script/text accuracy
- panel architecture accuracy
- reference adherence
- character continuity
- environment continuity
- object/effect continuity
- style compliance
- anatomy/hands
- page readability
- continuity seam
- PNG final visual decision: accepted/rejected
- manual PNG → WebP conversion completed
- final WebP repository path verified
- final status

Only after the PNG passes QA and the user manually converts that exact PNG to WebP does the matching `page-###.webp` become the page visual authority for downstream local continuity.

---

## Production Rule Summary

**One manga page = one production Markdown + one PNG review candidate + one manually converted approved WebP authority.**

The Markdown contains everything needed to generate and audit the page. ChatGPT/image generation gives PNG first. The WebP is created manually by the user only after the PNG passes visual and continuity review.
