# Page 001 Production

## 1. Page Identity / Status

- series: `My Roommate Only Appears During Blackouts`
- arc: `Arc 01 — title pending`
- chapter: `Chapter 001`
- page: `001`
- working label: `Still At Work`
- production status: **BLOCKED — APPROVED LAYOUT REFERENCE REQUIRED**
- final-page review candidate: `page-001.png`
- final approved repository output after manual conversion: `page-001.webp`
- required composition authority: `page-001-layout-reference.webp`

This file generates the **final Page 001 manga page only**.

Layout-reference generation is handled separately by:

`manga/04-production/arc-01/chapter-001/page-001-layout-production.md`

Global lettering authority:

`manga/01-style/reader-visible-language-lock.md`

---

## 2. Production Gate — ABSOLUTE

Do not generate the final Page 001 until this approved file exists:

`manga/04-production/arc-01/chapter-001/page-001-layout-reference.webp`

Missing approved layout reference = **STOP FINAL PAGE GENERATION**.

The layout reference controls composition. This final production MD controls final story content, exact English script, final manga rendering and QA.

---

## 3. Exact Final-Generation Attachments

When generating `page-001.png`, attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/04-production/arc-01/chapter-001/page-001-layout-reference.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp`
4. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do **not** attach:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Reason: for story-page generation these broad style images have repeatedly overpowered the Markdown and caused incorrect cinematic/polished drift.

### Attachment roles

1. `page-001-production.md` — final story/page instruction and exact English lettering authority
2. `page-001-layout-reference.webp` — absolute composition/staging authority
3. `nari-canonical.webp` — Nari identity authority
4. `nari-workplace-master-atlas.webp` — workplace geometry authority

No attached image may override the finished 2D manga or English-only lettering rules.

---

## 4. Source Authority — INTERNAL AUDIT ONLY

- `manga/00-series/story-concept.md`
- `manga/00-series/continuity-ledger.md`
- `manga/00-series/narrative-rules.md`
- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`
- `manga/01-style/speech-balloon-guide.md`
- `manga/01-style/sfx-lettering-guide.md`
- `manga/01-style/page-composition-rules.md`
- `manga/01-style/panel-language.md`
- `manga/01-style/screentone-and-hatching-guide.md`
- `manga/03-story/arc-01/chapter-001/chapter-outline.md`
- `manga/03-story/arc-01/chapter-001/scene-sequence.md`
- `manga/03-story/arc-01/chapter-001/dialogue-script.md`
- `manga/03-story/arc-01/chapter-001/page-map.md`
- `manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`
- `manga/04-production/arc-01/chapter-001/page-001-layout-production.md`
- `manga/02-references/characters/nari/canon.md`
- `manga/02-references/environments/nari-workplace/canon.md`

These source Markdown files are not image-generation attachments.

---

## 5. Page Canvas / Size Lock

- portrait
- **1024 × 1536 px**
- aspect ratio: **2:3**
- right-to-left manga reading
- one complete manga page only
- conventional manga margins/gutters
- black-and-white only
- no webtoon spacing

---

## 6. Page Purpose / Scenario

### Narrative purpose

Open the series on ordinary adult life, not supernatural horror.

The reader must clearly understand that Nari is physically at her publishing-company workplace after midnight. This is the first half of the later simultaneity contradiction.

### Story time

Previous night, approximately **12:25–12:30 a.m.**

### Location

Nari's approved publishing-company editorial office.

### Emotional tone

- ordinary deadline fatigue
- grounded adult routine
- mild dry work humor
- calm professional atmosphere
- not horror
- not ominous
- not cinematic

### Power / supernatural state

Ordinary supplied power. No visible supernatural activity.

### Page-turn function

The next page cuts to activity heard from Nari's apartment while she is away. Page 001 must therefore make Nari's location unmistakable.

---

## 7. Continuity Input

- Nari is age 30 and matches `nari-canonical.webp`
- approved practical publishing-office work outfit
- hair loose by default
- tired but composed
- seated/working at her recurring desk
- a small number of ordinary coworkers may remain or leave
- no named supporting character appears
- no apartment mystery has been mentioned to Nari
- no supernatural clue is in Nari's awareness

---

## 8. Composition Authority — LAYOUT REFERENCE LOCK

Follow:

`page-001-layout-reference.webp`

as the absolute visual authority for:

- panel count/order
- panel boundaries
- panel proportions
- camera/framing
- character blocking
- pose/facing direction
- major environment/prop placement
- negative space
- speech-balloon placement

Do not redesign, cinematicize, restage or replace its composition.

The layout reference should contain empty balloons. Final rendering adds the exact approved English text below.

Expected story structure remains exactly 4 panels with these beats:

1. late-night publishing-office establishing
2. coworker checks on Nari
3. Nari answers while continuing proof work
4. quiet time/location proof that she remains at work

---

## 9. Panel Content Requirements

### Panel 1 — Office Establishing

- Nari clearly visible at her recurring desk
- workplace reads immediately as publishing/editorial
- printed proofs/manuscripts/books visibly important
- screens secondary
- some desks already empty
- late-night context visible without horror/cinematic lighting
- **no reader-visible text**

### Panel 2 — Coworker Check-In

- generic unnamed adult coworker
- ordinary leaving-work body language
- coworker does not visually compete with Nari
- fill the approved empty balloon with exactly:

`You're still here?`

### Panel 3 — Nari Working

- Nari continues handling printed proof/manuscript pages
- readable natural hand action
- tired, composed, mildly resigned expression
- no exaggerated comedy or glamour pose
- fill the approved empty balloon with exactly:

`Just one more pass.`

### Panel 4 — Time / Location Proof

- Nari remains at work
- office mostly quiet/empty
- ordinary visual cue establishes after midnight
- analog wall clock may indicate approximately 12:25–12:30
- no dialogue
- no narration
- no SFX
- no readable background text

---

## 10. EXACT SCRIPT / LETTERING — ENGLISH ONLY

**Reader-visible language: ENGLISH ONLY.**

Panel 1: silence.

Panel 2:

COWORKER: `You're still here?`

Panel 3:

NARI: `Just one more pass.`

Panel 4: silence.

These are the **only reader-visible words permitted on Page 001**.

Do not translate, paraphrase or restyle the wording into another language.

Absolutely do not generate:

- Japanese text
- Korean text
- Chinese text
- any other non-English script
- fake multilingual glyphs
- company names
- book/manuscript titles
- readable proof/document text
- binder/folder labels
- sticky-note writing
- logos
- captions
- SFX
- fake UI
- monitor text
- extra dialogue

Arabic numerals on an analog clock face are allowed.

Any other readable text = **AUTOMATIC REJECT**.

---

## 11. Character Requirements

### Nari

- exact identity from `nari-canonical.webp`
- unmistakably adult Korean woman, age 30
- approved work outfit construction
- natural adult proportions
- readable hands
- tired but composed
- not teen-coded
- not glamorous/fashion-editorial
- not frightened or suspicious
- no cinematic heroine posing or lighting

### Unnamed coworker

- ordinary adult office worker
- generic/non-canonical
- no mystery emphasis
- no dramatic design
- no future-important visual coding

---

## 12. Environment / Object Requirements

### Workplace

- use approved workplace spatial identity
- preserve Nari desk orientation/location
- manuscripts/proofs/books must visually establish editorial work
- computers remain ordinary tools
- same architecture/furniture as workplace atlas
- late-night state changes occupancy, not geometry
- all documents/books/screens remain unreadable/blank unless explicitly permitted above

### Objects

- printed proofs/manuscript pages with no readable text
- ordinary pen/pencil
- optional simple bag/coat for departing coworker
- no plot-critical new object

---

## 13. FINISHED 2D HAND-DRAWN MANGA QUALITY LOCK — ABSOLUTE

This page is **not a sketch**.

Target: finished professional black-and-white 2D manga page quality.

Required:

- clean confident inked line art
- natural pen/brush line-weight variation
- crisp character contours and interior detail
- refined faces, hands and anatomy
- clean 2D perspective/background lines
- screentone used as manga tone
- hand hatching/cross-hatching where appropriate
- flat solid-black ink shapes where graphically useful
- clean white paper/negative space
- integrated manga speech balloons
- conventional printed-manga page readability

Solid black is allowed and may be substantial where appropriate. It must read as **flat graphic ink**, not cinematic shadow rendering.

Do NOT produce:

- rough pencils
- visible construction lines
- scribbly sketch output
- unfinished storyboard quality
- glossy digital illustration
- movie-still lighting
- painterly grayscale
- photorealism
- CGI/3D
- bloom
- lens flare
- volumetric light
- depth-of-field blur
- photographic bokeh
- airbrushed gradients
- smooth digital shadow modeling

Night should be expressed through manga ink/tone design, not simulated cinematic exposure.

---

## 14. Complete Final Generation Instruction

Create exactly **ONE 1024×1536 portrait black-and-white FINISHED 2D HAND-DRAWN MANGA PAGE** for Chapter 001 Page 001.

Use the attached `page-001-layout-reference.webp` as the absolute composition authority. Preserve its panel geometry, framing, blocking, poses, major props, negative space and speech-balloon placement.

Use `nari-canonical.webp` only for Nari identity and `nari-workplace-master-atlas.webp` only for workplace geometry.

Do not attach or imitate Style A/B.

Render the final page as clean professional printed manga: finished ink lines, refined anatomy, screentone, hatching where useful, flat graphic solid blacks, clean whites and integrated balloons.

**All reader-visible text must be English only. Put exactly `You're still here?` in Panel 2 and exactly `Just one more pass.` in Panel 3. Generate no other readable words anywhere. Do not translate either line. Do not generate Japanese/Korean/Chinese characters, fake writing, labels, signs, document text or UI text.**

Story content:

- Nari is still at her publishing-company workplace after midnight
- final panel quietly proves she remains away from home

No horror imagery, supernatural effects, silhouettes, apartment imagery, mystery symbols, invented dialogue or logos.

Return conceptually as `page-001.png` for visual review.

---

## 15. Automatic Rejection Conditions

Reject/regenerate if:

- approved `page-001-layout-reference.webp` is missing
- final page materially changes the approved layout
- panel geometry/order changes
- camera/framing changes materially
- character blocking/pose direction changes materially
- balloon placement/flow changes materially
- Nari identity drifts
- workplace geometry drifts
- office reads as software/game/engineering workplace
- editorial materials disappear
- dialogue differs from exact approved English
- dialogue is translated
- any Japanese/Korean/Chinese/non-English text appears
- invented readable text/logos/labels/UI/document text appears
- output looks rough/sketch/unfinished
- output becomes cinematic/poster/key-art-like
- output becomes glossy/painterly/photoreal/CGI/3D
- value is created with smooth digital gradients instead of manga ink/tone
- anatomy/hands fail
- output is not 1024×1536 portrait

---

## 16. Continuity Output

At page end:

- Nari remains at the publishing office
- work outfit and loose hair remain consistent
- she is tired/focused but normal
- ordinary supplied power is on
- no apartment mystery is known to her
- reader understands she is away from home in the relevant late-night window

---

## 17. QA / Approval Record

Before approval verify:

- [ ] approved `page-001-layout-reference.webp` exists and was attached
- [ ] `page-001-production.md` attached
- [ ] Nari canonical attached
- [ ] workplace atlas attached
- [ ] Style A/B NOT attached
- [ ] 1024×1536 portrait PNG
- [ ] layout reference followed closely
- [ ] right-to-left flow clear
- [ ] Nari identity matched
- [ ] workplace geometry matched
- [ ] publishing/editorial identity clear
- [ ] Panel 2 says exactly `You're still here?`
- [ ] Panel 3 says exactly `Just one more pass.`
- [ ] all reader-visible text is English only
- [ ] no Japanese/Korean/Chinese/non-English text
- [ ] no invented readable background text/logos
- [ ] final page is clean finished 2D manga, not sketch quality
- [ ] screentone/black/hatching read as manga graphics, not cinema
- [ ] no cinematic/glossy/painterly/3D drift
- [ ] anatomy/hands acceptable
- [ ] final PNG decision recorded
- [ ] accepted PNG manually converted to `page-001.webp`

Final approval status: **BLOCKED UNTIL LAYOUT REFERENCE IS GENERATED AND APPROVED SEPARATELY**
