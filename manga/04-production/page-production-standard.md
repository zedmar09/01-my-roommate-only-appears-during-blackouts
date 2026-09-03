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

## Global Human-Drawn Manga Rule — ABSOLUTE

Every page must visibly read as a **human-drawn black-and-white manga page**.

Default visual priority:

1. organic pencil/ink linework
2. white paper / negative space
3. restrained screentone
4. hand hatching/cross-hatching
5. sparse spot blacks only where genuinely needed

Do not optimize pages toward cinematic polish. More dramatic, more solid, more glossy, or more “finished” is not automatically better.

Reject any page that looks like a movie still, cinematic storyboard, key art, poster, digital concept illustration, glossy webtoon/manhwa panel, photoreal/3D-derived frame, or high-contrast noir image when that treatment is not explicitly story-required.

The global style authority is:

`manga/01-style/manga-style-lock.md`

The tone/value authority is:

`manga/01-style/screentone-and-hatching-guide.md`

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

List the exact approved story and canon files from which this page is compiled. At minimum include relevant authorities under:

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

OBJECTS
- .../canon.md
- .../canonical.webp

EFFECTS
- .../canon.md
- .../atlas.webp

LOCAL CONTINUITY
- previous approved page WebP
```

Every required reusable WebP must be `APPROVED` in `manga/02-references/reference-register.md`.

Missing required reference = **STOP GENERATION**.

#### User-supplied page sketch / thumbnail

If the user supplies or has approved a page-specific sketch/thumbnail/layout image for the page, the production MD must explicitly state that it is the highest composition authority for that generation.

The supplied sketch controls:

- panel geometry/proportions
- panel order
- camera/framing intent
- character blocking
- major prop placement
- negative space
- balloon-placement intent
- rough manga-page rhythm

Do not redesign, beautify, cinematicize, or “improve” an approved sketch. Character/environment canon still controls identity and reusable geometry.

### 4. Page Canvas / Size Lock

Specify exact production geometry for the PNG generation candidate:

- orientation
- pixel width
- pixel height
- aspect ratio
- trim/border/safe-area rules if applicable
- reading direction
- whether artwork may bleed to page edge

The manual PNG → WebP conversion must preserve the approved page geometry.

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

- total panel count or target count
- reading order
- approximate panel dimensions or relative percentages when no approved sketch exists
- row/column relationship where useful
- dominant panel(s)
- inset/reaction panels
- gutter size/rhythm
- border treatment
- bleed panels if any
- intentional blank/negative space

Panel count and panel sizes are not fixed across pages. They follow story rhythm.

If an approved page sketch is supplied, it overrides fallback textual layout percentages for composition.

### 8. Complete Panel-by-Panel Blueprint

For every panel, specify all applicable details:

- panel number
- narrative beat
- approximate panel size / hierarchy
- camera framing and angle
- environment/location anchors
- character(s) present
- pose, blocking, gaze, expression, hand action, body direction
- object/prop position and state
- supernatural/effect state
- action/reaction sequence
- required foreground/background details
- what must remain outside the crop
- continuity inherited from previous panel
- continuity state passed to next panel

Do not describe ordinary panels with film-language that encourages cinematic rendering. Prefer manga terms such as wide establishing panel, medium character panel, close-up, cut-in, reaction panel, dominant panel, and quiet atmosphere panel.

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

Restate only page-relevant character requirements that cannot be safely inferred from attached canon:

- temporary wardrobe
- temporary hairstyle state
- expression
- emotional state
- pose/action
- injuries
- carried/held items
- interaction rules

Canonical identity comes from the approved character package.

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
- **visibly human-drawn pencil/ink character**
- organic, non-uniform line weight
- slight natural line imperfection allowed
- subtle pencil/sketch residue allowed when intentional and readable
- line-driven form rather than shadow-driven digital modeling
- substantial white-paper areas
- restrained screentone
- hand-drawn hatching/cross-hatching as appropriate
- sparse controlled spot blacks rather than large default black masses
- natural anatomy and readable hands
- detailed backgrounds when storytelling needs them
- simplified backgrounds when emotion/dialogue benefits from reduction
- expressive manga abstraction where appropriate
- no color
- no glossy/webtoon finish
- no photorealism
- no CGI/3D render look
- no painterly/airbrushed rendering
- no vector-clean/plastic AI ink finish
- no cinematic grading
- no cinematic rim/back lighting unless explicitly story-required
- no bloom, lens flare, volumetric light, bokeh, or depth-of-field blur
- no film-still, poster, key-art, or cinematic-storyboard composition drift
- no giant black vignette / noir treatment on ordinary scenes
- no production labels, panel IDs, filenames, crop guides, QA notes, or metadata inside reader-facing artwork

For ordinary-life scenes, **white + line art must dominate**.

### 13. Complete Generation Instruction

Provide one final deterministic instruction that tells the image generator to create exactly one complete manga page as PNG using the page canvas, attached approved references, panel architecture, script, actions, scenario, continuity, and visual rules defined above.

Every final generation instruction must explicitly repeat:

- `THIS MUST LOOK VISIBLY HUMAN-DRAWN.`
- not cinematic
- not poster/key art
- not glossy digital illustration
- restrained solid blacks
- white paper + organic linework + light tone/hatching first

The generation instruction must not leave essential story decisions to the image model.

### 14. Automatic Rejection Conditions

List page-specific failures that require regeneration, including as applicable:

- wrong panel count/order
- approved page sketch materially ignored/redesigned
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
- color/glossy/3D/photoreal/painterly drift
- cinematic lighting/value/composition drift
- poster/key-art/film-still appearance
- vector-clean/plastic AI linework
- excessive solid-black masses
- ordinary scene rendered as noir/high-contrast drama
- page does not visibly read as human-drawn manga
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
- approved sketch adherence when applicable
- reference adherence
- character continuity
- environment continuity
- object/effect continuity
- visibly human-drawn linework
- restrained solid-black use
- no cinematic/poster/key-art drift
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

The Markdown contains everything needed to generate and audit the page. The default visual target is a **real human-drawn black-and-white manga page**, never cinematic digital illustration unless a specific story page explicitly earns and authorizes a stronger treatment.
