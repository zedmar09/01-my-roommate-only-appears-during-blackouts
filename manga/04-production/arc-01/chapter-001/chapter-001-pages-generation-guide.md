# Chapter 001 Pages Generation Guide

## Status

**APPROVED PRODUCTION GUIDE — SEPARATE LAYOUT-REFERENCE + FINAL 2D MANGA WORKFLOW.**

This file controls production workflow for all 36 Chapter 001 pages. Story authority remains under `manga/03-story/`.

See also:

- `manga/04-production/layout-reference-workflow.md`
- `manga/04-production/page-production-standard.md`
- `manga/01-style/reader-visible-language-lock.md`

---

## Chapter Function

Chapter 001 begins as an ordinary apartment-security mystery.

Nari is provably at her publishing-company workplace while the downstairs neighbor hears activity from her supposedly empty apartment. The chapter follows mundane security logic, a weak chair clue, a deliberate known-state test, ordinary domestic life, then a reader-only final chair movement.

The chapter must not reveal Hyun-woo, a roommate claim, the blackout rule or the wider mechanism.

---

## Global Reader-Visible Language Lock — ENGLISH ONLY

Every Chapter 001 final page uses **English only** for all reader-visible text.

This includes:

- dialogue
- thoughts
- narration/captions
- SFX
- story-required signs/labels/UI/notes

Rules:

- copy exact English wording from the approved story/dialogue authorities into each final `page-###-production.md`
- never translate English dialogue into Japanese, Korean, Chinese or another language
- never invent non-English lettering or fake multilingual glyphs
- never invent readable background text
- omit readable books, binders, documents, signs, screens and notes unless story-required
- when story-required background text exists, it must be exact approved English
- English/Latin-letter SFX only, matching the exact page script

### Layout-reference rule

All Chapter 001 layout-reference images use **zero readable text by default**:

- dialogue balloons EMPTY
- thought balloons EMPTY
- caption boxes empty if placement is needed
- no SFX letters
- no readable signs/labels/documents/UI

A layout reference locks placement only. Exact English wording is added during final page generation.

Any non-English reader-visible text = **AUTOMATIC REJECT**.

---

## Page Canvas Lock

All final story pages use:

- portrait
- **1024 × 1536 px** PNG review candidate
- **2:3** aspect ratio
- right-to-left manga reading
- black-and-white only
- conventional manga page gutters
- no vertical-webtoon dead space

---

## Final 2D Manga Quality Rule

Every final Chapter 001 page must look like **finished professional black-and-white 2D manga**, not a rough sketch.

Required:

- clean finished inks
- natural line-weight variation
- refined 2D character drawing
- readable anatomy/hands
- clean background perspective
- screentone
- hatching/cross-hatching where useful
- flat graphic solid-black ink shapes where appropriate
- integrated speech balloons
- conventional manga page readability

Solid black is allowed as manga graphic design. It must not behave like soft cinematic shadow rendering.

Reject:

- rough/sketch/construction-line final pages
- glossy digital illustration
- movie-still/cinematic lighting
- painterly grayscale
- photorealism
- CGI/3D
- smooth airbrush gradients
- bloom/bokeh/volumetric light/depth-of-field

---

## Style A/B Story-Page Rule

These remain approved reference-development assets:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

They are **not default Chapter 001 layout-reference or final-page attachments**.

Default: **omit Style A/B from story-page production**.

Only opt them into a specific page if that page's production MD explicitly requires them after successful testing.

---

## Canonical Story-Page References

### Nari

`manga/02-references/approved-webp/nari-canonical.webp`

Attach whenever Nari is visible. Identity authority only.

### Apartment

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Attach when the approved apartment/common-route environment is visible.

### Workplace

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Attach when the publishing workplace is visible.

Canonical images control identity/geometry, not final page rendering finish or language.

---

## Separate Layout Reference Production

A page may use a separate:

`page-###-layout-production.md`

when composition needs a visual lock.

That file generates:

`page-###-layout-reference.png`

After approval, manually convert the exact accepted PNG to:

`page-###-layout-reference.webp`

The layout reference should be a clean, content-filled 2D manga draft/reference — not empty boxes, wireframes, stick figures or rough scribble sketches.

It locks:

- panel geometry
- framing
- blocking
- pose direction
- major props/environment
- negative space
- empty balloon placement

**It should not render dialogue or other readable text.**

Final page production occurs separately using `page-###-production.md`.

---

## Page 001 — Mandatory Separate Layout Reference

Page 001 requires an approved layout reference before final generation.

### Layout-reference production

Use:

`manga/04-production/arc-01/chapter-001/page-001-layout-production.md`

Attach exactly:

1. `page-001-layout-production.md`
2. `nari-canonical.webp`
3. `nari-workplace-master-atlas.webp`

Do not attach Style A/B.

Generate/review:

`page-001-layout-reference.png`

Required lettering state:

- Panel 2 balloon EMPTY
- Panel 3 balloon EMPTY
- zero readable background text

After approval, manually convert and commit:

`manga/04-production/arc-01/chapter-001/page-001-layout-reference.webp`

### Final Page 001 production

Only after the approved layout reference exists, use:

`manga/04-production/arc-01/chapter-001/page-001-production.md`

Attach exactly:

1. `page-001-production.md`
2. `page-001-layout-reference.webp`
3. `nari-canonical.webp`
4. `nari-workplace-master-atlas.webp`

Do not attach Style A/B.

Final Page 001 uses exactly these English lines and no other reader-visible words:

- `You're still here?`
- `Just one more pass.`

Final Page 001 must be finished 2D manga quality, not a sketch-cleanup look.

---

## Previous-Page Continuity

Use the immediately previous approved page WebP only when it materially helps:

- pose/facing direction
- chapter-local neighbor identity
- environment crop
- Chair B state
- temporary clothing/object state
- ongoing action

Previous-page art never overrides:

1. current final page-production MD
2. approved layout reference
3. character canonical
4. environment canonical
5. English-only language lock

---

## Chapter-Wide Visual Rhythm

Required progression:

1. ordinary adult work life
2. mundane neighbor irritation
3. rational security contradiction
4. practical inspection
5. weak chair clue
6. deliberate known-state setup
7. comfortable domestic decompression
8. quiet empty-room suspense
9. restrained reader-only physical proof

Do not render the entire chapter as horror.

---

## Chair B Continuity Lock

Pages 024–025 establish the known position.

Pages 025–034 must preserve it whenever visible.

Page 035 contains restrained English/Latin-letter SFX `SKRRR` with source unseen.

Page 036 shows Chair B displaced.

Pages 024–036 should strongly consider separate layout references because exact room/chair geometry is story-critical.

---

## Page-by-Page Reference Matrix

Legend:

- `N` = Nari canonical
- `APT` = apartment atlas
- `WORK` = workplace atlas
- `PREV` = previous approved page
- `LAYOUT` = approved page-specific layout reference when required

Style A/B are intentionally omitted.

| Page | Panels Guide | Core Beat | Canonical Visual Refs | Local Continuity |
|---|---:|---|---|---|
| 001 | ~4 | late-night publishing office; Nari still away from home | N, WORK, LAYOUT mandatory | none |
| 002 | ~4–5 | neighbor hears first human-weight movement | LAYOUT if required | none |
| 003 | ~4 | footsteps / `THUMP`; neighbor reacts | LAYOUT if required | PREV required |
| 004 | ~3 | `SKRRR`; neighbor checks time; Nari intercut | N, WORK + LAYOUT if required | PREV useful |
| 005 | ~3–4 | Nari finishes/leaves after noise time | N, WORK + LAYOUT if required | PREV useful |
| 006 | ~4 | morning corridor/elevator neighbor encounter | N, APT + LAYOUT if required | none |
| 007 | ~5 | complaint begins | N, APT + LAYOUT if required | PREV required |
| 008 | ~5 | walking + chair scrape specified | N, APT + LAYOUT if required | PREV required |
| 009 | ~4 | Nari asks what time | N, APT + LAYOUT if required | PREV required |
| 010 | 2–3 | `I wasn't home.` | N, APT + LAYOUT recommended | PREV required |
| 011 | ~4 | publishing work resumes | N, WORK + LAYOUT if required | none |
| 012 | ~5–6 | ordinary coworker/dry humor | N, WORK + LAYOUT if required | PREV required |
| 013 | ~4 | timestamp evidence | N, WORK + LAYOUT if required | PREV useful |
| 014 | ~5 | access history opened | N, WORK + LAYOUT if required | PREV useful |
| 015 | ~3–4 | no ordinary entry | N, WORK + LAYOUT recommended | PREV useful |
| 016 | ~5 | mundane explanations | N, WORK + LAYOUT if required | PREV useful |
| 017 | ~5 | work interrupts investigation | N, WORK + LAYOUT if required | PREV useful |
| 018 | ~3–4 | Nari decides to inspect home | N, WORK + LAYOUT if required | PREV useful |
| 019 | ~4 | ordinary return home | N, APT + LAYOUT if required | none |
| 020 | ~5 | practical inspection | N, APT + LAYOUT if required | PREV required |
| 021 | ~4 | nothing dramatic found | N, APT + LAYOUT if required | PREV required |
| 022 | ~3 | Chair B slightly displaced | N, APT + LAYOUT recommended | PREV required |
| 023 | ~5 | self-doubt | N, APT + LAYOUT if required | PREV required |
| 024 | ~4 | deliberately align Chair B | N, APT + LAYOUT strongly recommended | PREV required |
| 025 | ~3 | exact known Chair B position | N, APT + LAYOUT strongly recommended | PREV required |
| 026 | ~5 | normal home routine | N, APT + LAYOUT if required | PREV required |
| 027 | ~5–6 | meal/cleanup/domestic rhythm | N, APT + LAYOUT if required | PREV required |
| 028 | ~6 | optional offscreen call | N, APT + LAYOUT if required | PREV required |
| 029 | ~5 | conversation moves away from mystery | N, APT + LAYOUT if required | PREV required |
| 030 | ~4 | late-night quiet | N, APT + LAYOUT if required | PREV required |
| 031 | ~4–5 | bedtime preparation | N, APT + LAYOUT if required | PREV required |
| 032 | ~3 | final verified empty-room state | N, APT + LAYOUT recommended | PREV required |
| 033 | ~2–3 | empty room; Chair B unchanged | APT + LAYOUT recommended | PREV required |
| 034 | ~2 | extend stillness | APT + LAYOUT recommended | PREV required |
| 035 | ~2–3 | restrained `SKRRR`; source unseen | APT + LAYOUT strongly recommended | PREV required |
| 036 | 1–2 | Chair B visibly displaced | APT + LAYOUT strongly recommended | PREV required |

---

## Dialogue Authority

Every final page-production file must copy exact **English** reader-visible wording from approved story/dialogue authorities.

Do not let image generation invent, paraphrase, translate, localize or romanize text.

Background text default: **none**.

---

## Automatic Chapter-Wide Rejection Conditions

Reject any final page that introduces:

- wrong Nari identity
- environment geometry drift
- accidental Chair B state drift
- visible hidden presence
- ghost/shadow-person imagery
- explicit blackout explanation
- invented supernatural effects
- premature horror intensity
- unreadable right-to-left order
- invented dialogue/logos/text
- non-English reader-visible text
- translated dialogue/SFX
- fake readable background text
- rough unfinished sketch final art
- cinematic/poster/key-art rendering
- glossy/painterly/photoreal/CGI treatment
- smooth digital gradient lighting

If an approved layout reference is required, also reject material composition departure from it.

---

## Generation Sequence

When a layout reference is required:

`layout-production MD → text-free layout-reference PNG → review → approved layout-reference WebP → final page-production MD → exact-English final page PNG → review → final page WebP`

The user may generate layout references separately before final-page production.

Do not batch-generate final pages blindly.

---

## Final Chapter QA

Verify:

- Nari identity remains stable
- environment geometry remains stable
- final pages remain finished 2D manga quality
- all reader-visible text is English only
- exact English scripts/SFX are preserved
- no fake/non-English background text appears
- Style A/B were not attached unless explicitly opted in
- required layout references were approved before final pages
- Page 025 establishes Chair B known state clearly
- Chair B remains unchanged through Page 034 whenever visible
- Page 035 keeps movement source unseen
- Page 036 proves displacement without explanation
- Nari ends unaware of final movement
