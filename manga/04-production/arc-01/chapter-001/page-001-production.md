# Page 001 Production

## 1. Page Identity / Status

- series: `My Roommate Only Appears During Blackouts`
- arc: `Arc 01 — title pending`
- chapter: `Chapter 001`
- page: `001`
- working label: `Still At Work`
- production status: **LAYOUT SKETCH REQUIRED**
- Stage A sketch review candidate: `page-001-layout-sketch.png`
- Stage A approved sketch authority: `page-001-layout-sketch.webp`
- Stage B final-page review candidate: `page-001.png`
- final approved repository output after manual conversion: `page-001.webp`

---

## 2. TWO-STAGE PRODUCTION RULE — ABSOLUTE

Page 001 must be produced in two separate generation stages.

### STAGE A — HUMAN-DRAWN PAGE LAYOUT SKETCH

Generate and approve the manga page layout sketch first.

Output review candidate:

`page-001-layout-sketch.png`

After visual approval, manually convert that exact PNG to:

`manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`

The approved sketch becomes the **highest visual authority for Page 001 composition**.

### STAGE B — FINAL MANGA PAGE

Do **not** generate the final Page 001 artwork until the approved file below exists:

`manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`

Missing approved layout sketch = **STOP. DO NOT GENERATE THE FINAL PAGE.**

Stage B must preserve the approved sketch rather than inventing, redesigning, beautifying, cinematicizing, or re-staging it.

### Current repository state

At the time this production rule is established, `page-001-layout-sketch.webp` has not yet been created. Therefore Page 001 is intentionally **blocked at Stage A** until a sketch candidate is generated, visually approved, converted to WebP and committed.

---

## 3. STYLE SHEET ATTACHMENT BAN FOR STORY-PAGE GENERATION

Do **not** attach these files when generating either the Page 001 layout sketch or the final Page 001 manga page:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Reason:

The paired style sheets are reusable reference-development assets, but for story-page generation they can visually overpower the page-specific Markdown and pull output toward polished, heavy-black, cinematic, or key-art rendering.

For Page 001, the **written human-drawn manga style lock in this file is the rendering authority**.

Style A/B must not be used as page composition, lighting, contrast, or finish authorities.

---

## 4. STAGE A — EXACT ATTACHMENTS

When generating `page-001-layout-sketch.png`, attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/02-references/approved-webp/nari-canonical.webp`
3. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A or Style B.

### Stage A attachment roles

- `page-001-production.md` controls story, composition intent, panel rhythm, sketch style, dialogue placement and anti-cinematic rules.
- `nari-canonical.webp` controls Nari's identity only.
- `nari-workplace-master-atlas.webp` controls workplace geometry only.

Neither Nari canonical nor the workplace atlas may override the required rough human-drawn manga-sketch treatment.

---

## 5. STAGE B — EXACT ATTACHMENTS

After `page-001-layout-sketch.webp` has been approved and committed, generate `page-001.png` using exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp`
4. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A or Style B.

### Stage B authority priority

1. `page-001-production.md` — story and written production authority
2. `page-001-layout-sketch.webp` — **absolute composition authority**
3. `nari-canonical.webp` — Nari identity authority
4. `nari-workplace-master-atlas.webp` — workplace geometry authority

If a canonical reference visually encourages polished/cinematic rendering, ignore that rendering characteristic and preserve the hand-drawn manga treatment defined here.

---

## 6. Source Authority — INTERNAL AUDIT ONLY

Internal story/canon authorities:

- `manga/00-series/story-concept.md`
- `manga/00-series/continuity-ledger.md`
- `manga/00-series/narrative-rules.md`
- `manga/01-style/manga-style-lock.md`
- `manga/01-style/page-composition-rules.md`
- `manga/01-style/panel-language.md`
- `manga/01-style/screentone-and-hatching-guide.md`
- `manga/03-story/arc-01/chapter-001/chapter-outline.md`
- `manga/03-story/arc-01/chapter-001/scene-sequence.md`
- `manga/03-story/arc-01/chapter-001/dialogue-script.md`
- `manga/03-story/arc-01/chapter-001/page-map.md`
- `manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`
- `manga/02-references/characters/nari/canon.md`
- `manga/02-references/environments/nari-workplace/canon.md`

These are not image-generation attachments.

---

## 7. Page Canvas / Size Lock

For both Stage A and Stage B:

- orientation: portrait
- width: **1024 px**
- height: **1536 px**
- aspect ratio: **2:3**
- reading direction: **right-to-left**
- one complete manga page only
- clean outer page margin
- conventional manga gutters
- black-and-white only
- no webtoon spacing

---

## 8. Page Purpose / Scenario

### Narrative purpose

Open the series on ordinary adult life, not supernatural horror.

The reader must clearly understand that Nari is physically at her publishing-company workplace after midnight. This establishes the first half of the later simultaneity contradiction.

### Story time

Previous night, approximately **12:25–12:30 a.m.**

### Location

Nari's approved publishing-company editorial office.

### Emotional tone

- ordinary deadline fatigue
- grounded adult routine
- dry work humor
- calm professional atmosphere
- no horror framing
- no cinematic drama

### Power / supernatural state

Ordinary supplied power. No supernatural activity is visible.

---

## 9. Page Composition / Layout Sketch Blueprint

Target: **4 panels**, read right-to-left / top-to-bottom.

The Stage A sketch must establish a clear real-manga page rhythm rather than a rigid four-equal-box template.

### Panel 1 — Office Establishing

- dominant upper establishing panel
- Nari clearly visible at her recurring desk
- editorial workplace is immediately readable
- manuscripts/proofs/books are more important than computer screens
- some desks already empty
- ordinary night visible through windows only if consistent with workplace atlas
- no dramatic shadow design

### Panel 2 — Coworker Check-In

- smaller dialogue panel on the right side of the middle reading band
- unnamed coworker near Nari's desk, preparing to leave
- ordinary adult workplace interaction
- dialogue: `You're still here?`

### Panel 3 — Nari Working

- larger character/work panel to the left of Panel 2
- medium-close or equivalent natural manga framing
- Nari continues handling printed proofs
- expression tired, composed and mildly resigned
- dialogue: `Just one more pass.`

### Panel 4 — Time / Location Proof

- lower quiet atmosphere panel with breathing room
- Nari still working
- surrounding office mostly quiet/empty
- ordinary non-text cues make it clear that it is after midnight
- an analog wall clock may indicate approximately 12:25–12:30
- no dialogue

### Stage A composition rule

The sketch may adjust exact panel percentages to achieve a natural manga page, but it must preserve the four narrative beats and right-to-left readability above.

Once Stage A is approved, **its exact panel shapes, relative sizes, shot placement, character blocking, major prop placement, negative space and balloon placement become locked for Stage B**.

---

## 10. Exact Script / Lettering

Panel 1: silence.

Panel 2:

COWORKER: `You're still here?`

Panel 3:

NARI: `Just one more pass.`

Panel 4: silence.

Do not invent company names, manuscript text, logos, captions, labels, fake UI or additional dialogue.

---

## 11. Character Requirements

### Nari

- match `nari-canonical.webp` identity
- adult Korean woman, age 30
- approved practical publishing-office work outfit
- hair loose by default
- tired but composed
- not teen-coded
- not glamorous/fashion-editorial
- not frightened
- readable natural hands
- never posed or lit like key art, a movie heroine, or a fashion illustration

### Unnamed coworker

- ordinary adult office worker
- generic and non-canonical
- no mystery emphasis
- no dramatic lighting
- must not visually compete with Nari

---

## 12. Environment / Object Requirements

### Workplace

- preserve `nari-workplace-master-atlas.webp` spatial identity
- maintain Nari's recurring desk location/orientation
- visible publishing/editorial materials
- ordinary computers remain secondary
- late-night state changes occupancy only
- no office redesign
- no cinematic late-night transformation

### Objects

- printed proofs/manuscript pages
- ordinary pen/pencil
- optional simple bag/coat for coworker
- no new plot-critical object

---

## 13. HUMAN-DRAWN MANGA SKETCH / INK LOCK — ABSOLUTE

The most important visual requirement is that the page looks **drawn by a human manga artist**, not rendered by a cinematic image model.

### Required drawing character

- organic pencil/ink linework
- visible pressure variation
- slight natural line wobble
- human imperfection
- line-driven forms
- substantial white paper
- restrained black fills
- light screentone where useful
- irregular hand hatching where useful
- faces and clothing remain drawing-first rather than shading-first
- environments are constructed with hand-drawn perspective lines
- ordinary manga-panel readability

### Stage A specifically

The layout sketch must look like a genuine manga artist's production sketch / name / rough page:

- rough confident pencils or light rough inks
- simplified but readable anatomy
- clear panel borders
- clear staging
- balloon placement visible
- no polished rendering
- no finished cinematic shading
- no dramatic value painting
- no key-art finish

### Stage B specifically

The final page may clean the Stage A lines but must retain human-drawn character:

- do not erase all natural irregularity
- do not turn sketch lines into vector-clean contours
- use tone/hatching sparingly
- preserve white-space structure from the sketch
- preserve the exact approved layout

### Absolute anti-cinematic ban

Reject any output resembling:

- movie still
- cinematic storyboard
- poster
- key art
- glossy illustration
- noir frame
- painterly concept art
- 3D/CG render converted to manga

Do not use:

- rim lighting
- dramatic backlighting
- volumetric light
- bloom
- lens flare
- depth-of-field blur
- photographic bokeh
- heavy cinematic vignette
- airbrushed gradients
- smooth digital shadow masses
- large unnecessary black backgrounds
- theatrical chiaroscuro on faces

**If an output looks more polished/cinematic but less human-drawn, it is automatically wrong.**

---

## 14. STAGE A GENERATION INSTRUCTION

Create exactly **ONE 1024×1536 portrait black-and-white HUMAN-DRAWN MANGA PAGE LAYOUT SKETCH** for Chapter 001 Page 001.

This is not the final illustration. It is a manga artist's page-production sketch / rough page used to lock panel composition before final art.

Use the attached Nari canonical only to keep Nari recognizable and the workplace atlas only to keep the office spatially correct. Do not reproduce their polished rendering. Do not attach or imitate Style A/B.

Draw exactly the four story beats defined in this production file. Use organic rough pencil/ink lines, simple readable staging, conventional manga gutters, right-to-left reading order and visible balloon placement. Keep white paper dominant. Do not render cinematic lighting, glossy shading, dramatic black masses or finished key-art detail.

Output conceptually as:

`page-001-layout-sketch.png`

The PNG must be reviewed before conversion to `page-001-layout-sketch.webp`.

---

## 15. STAGE A SKETCH REJECTION CONDITIONS

Reject/regenerate the layout sketch if:

- it looks like finished key art instead of a manga production sketch
- panel order is unclear or left-to-right
- four core story beats are not present
- Nari is not recognizable
- workplace no longer reads as publishing/editorial
- composition is rigid or cinematic rather than manga-page-like
- heavy black/cinematic shading dominates
- balloon locations are missing or unreadable
- anatomy/blocking cannot support final art
- output is not 1024×1536 portrait

---

## 16. STAGE B FINAL-PAGE GENERATION INSTRUCTION

Only after `page-001-layout-sketch.webp` exists and is attached:

Create exactly **ONE 1024×1536 portrait black-and-white human-drawn manga page** for Chapter 001 Page 001.

Follow the attached approved sketch as the absolute composition authority. Preserve its panel boundaries, relative panel sizes, camera framing, character blocking, major object placement, negative space and balloon positions.

Do not redesign, improve, cinematicize or re-stage the approved sketch.

Use `nari-canonical.webp` only for Nari's identity and `nari-workplace-master-atlas.webp` only for office geometry. The written style lock in this MD controls rendering.

Clean the sketch into readable human-drawn manga artwork while preserving organic pencil/ink character, restrained blacks, white paper, sparse screentone and hand hatching. Do not create glossy, heavily rendered, noir, filmic or poster-like artwork.

Dialogue must remain exactly:

- `You're still here?`
- `Just one more pass.`

Return conceptually as `page-001.png` for review.

---

## 17. STAGE B AUTOMATIC REJECTION CONDITIONS

Reject/regenerate if:

- approved layout sketch is missing from the request
- final page materially departs from the approved sketch
- panel shapes/order/proportions are redesigned
- camera/framing is reinterpreted without necessity
- character blocking changes materially
- balloon placement/flow changes materially
- Nari identity drifts
- workplace geometry drifts
- office reads as technical/software/game workplace
- dialogue differs
- invented readable text/logos appear
- output becomes cinematic, glossy, heavily shaded, noir, key-art-like, painterly, photoreal or CGI-like
- excessive solid blacks replace line art/hatching
- hands/anatomy fail
- output is not 1024×1536 portrait

---

## 18. Continuity Output

At page end:

- Nari remains at the publishing office
- she is still in her work outfit with loose hair
- she remains tired/focused but normal
- ordinary supplied power is on
- no apartment mystery is known to her
- reader clearly understands she is away from home during the relevant late-night window

---

## 19. QA / Approval Record

### Stage A — layout sketch

- [ ] production MD attached
- [ ] Nari canonical attached
- [ ] workplace atlas attached
- [ ] Style A/B NOT attached
- [ ] `page-001-layout-sketch.png` generated
- [ ] human-drawn manga production-sketch look confirmed
- [ ] four beats present
- [ ] right-to-left flow confirmed
- [ ] panel composition approved
- [ ] blocking approved
- [ ] balloons approved
- [ ] no cinematic/heavy-black drift
- [ ] exact approved PNG manually converted to `page-001-layout-sketch.webp`
- [ ] approved sketch committed under production folder

### Stage B — final page

- [ ] approved `page-001-layout-sketch.webp` exists
- [ ] production MD attached
- [ ] approved layout sketch attached
- [ ] Nari canonical attached
- [ ] workplace atlas attached
- [ ] Style A/B NOT attached
- [ ] final page follows sketch closely
- [ ] Nari identity matched
- [ ] workplace matched
- [ ] dialogue exact
- [ ] human-drawn manga look preserved
- [ ] no cinematic/glossy/heavy-black drift
- [ ] anatomy/hands acceptable
- [ ] final PNG decision recorded
- [ ] exact accepted PNG manually converted to `page-001.webp`

Final status: **BLOCKED UNTIL LAYOUT SKETCH IS APPROVED AND COMMITTED**
