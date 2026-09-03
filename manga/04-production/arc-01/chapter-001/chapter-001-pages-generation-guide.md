# Chapter 001 Pages Generation Guide

## Status

**APPROVED PRODUCTION GUIDE — SKETCH-FIRST STORY-PAGE WORKFLOW.**

This file controls the production workflow for all 36 Chapter 001 pages. Story authority remains under `manga/03-story/`.

See also:

`manga/04-production/layout-sketch-workflow.md`

---

## Chapter Function

Chapter 001 begins as an ordinary apartment-security mystery.

Nari is provably at her publishing-company workplace while the downstairs neighbor hears activity from her supposedly empty apartment. The chapter follows mundane security logic, a weak chair clue, a deliberate known-state test, ordinary domestic life, then a reader-only final chair movement.

The chapter must not reveal Hyun-woo, a roommate claim, the blackout rule or the wider mechanism.

---

## Page Canvas Lock

All pages use:

- portrait
- **1024 × 1536 px** PNG review candidates
- **2:3** aspect ratio
- right-to-left manga reading
- black-and-white only
- conventional manga page gutters
- no vertical-webtoon dead space

---

## Human-Drawn Manga Rule

Every Chapter 001 story page must look visibly drawn by a human manga artist.

Required:

- organic pencil/ink lines
- line-pressure variation
- natural imperfection
- white paper dominant on ordinary pages
- restrained spot blacks
- light screentone and hand hatching where useful
- line-driven faces/clothes/backgrounds
- natural anatomy/readable hands

Reject:

- cinematic lighting
- poster/key-art finish
- glossy digital manga
- excessive solid-black masses
- noir/chiaroscuro treatment on ordinary scenes
- movie-still framing
- bloom, bokeh, volumetric light, DOF blur
- painterly grayscale
- photorealism
- CGI/3D
- plastic/vector-clean AI finish

If an output is more polished/cinematic but less human-drawn, reject it.

---

## Style A/B Story-Page Rule

These remain approved reference-development assets:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

They are **not default Chapter 001 story-page attachments**.

Do not attach them to a story-page sketch or final page unless the exact page-production MD explicitly opts them in after successful testing.

Default: **omit Style A/B from story-page generation**.

---

## Canonical Story-Page References

### Nari

`manga/02-references/approved-webp/nari-canonical.webp`

Attach whenever Nari is visible. It controls identity only.

### Apartment

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Attach when the approved apartment/common-route environment is visible.

### Workplace

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Attach when Nari's publishing workplace is visible.

Canonical images control identity/geometry, not page rendering finish.

---

## Sketch-First Production

A page production MD may declare an approved layout sketch mandatory.

### Stage A

Generate:

`page-###-layout-sketch.png`

The sketch must establish:

- panel count/order
- page rhythm
- framing
- blocking
- major objects
- negative space
- balloon positions

It must look like a manga artist's rough/name/layout, not finished key art.

After approval, manually convert the exact accepted PNG to:

`page-###-layout-sketch.webp`

and commit it beside the page production MD.

### Stage B

If the page marks the layout sketch required, final-page generation is blocked until the approved WebP exists.

The approved sketch becomes the final page's composition authority.

Do not redesign or cinematicize it.

---

## Page 001 — Mandatory Sketch-First Gate

Page 001 must use the two-stage workflow.

### Page 001 Stage A attachments

Attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/02-references/approved-webp/nari-canonical.webp`
3. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

Generate/review:

`page-001-layout-sketch.png`

Approve, manually convert and commit:

`manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`

### Page 001 Stage B attachments

Only after the approved sketch exists, attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp`
4. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

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

1. page production MD,
2. approved page layout sketch,
3. character canonical,
4. environment canonical.

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

Do not render the whole chapter as horror.

---

## Chair B Continuity Lock

Pages 024–025 establish the known position.

Pages 025–034 must preserve it whenever visible.

Page 035 contains restrained `SKRRR` with source unseen.

Page 036 shows Chair B displaced.

Future production files for these pages should strongly consider mandatory sketch-first layouts because exact chair geometry is story-critical.

---

## Page-by-Page Reference Matrix

Legend:

- `N` = Nari canonical
- `APT` = apartment atlas
- `WORK` = workplace atlas
- `PREV` = previous approved page
- `SKETCH` = approved page-specific layout sketch when page MD requires it

**Style A/B are intentionally omitted from this matrix.**

| Page | Panels Guide | Core Beat | Canonical Visual Refs | Local Continuity |
|---|---:|---|---|---|
| 001 | ~4 | late-night publishing office; Nari still away from home | N, WORK, SKETCH mandatory | none |
| 002 | ~4–5 | neighbor hears first human-weight movement | page MD + SKETCH if required | none |
| 003 | ~4 | footsteps / `THUMP`; neighbor reacts | page MD + SKETCH if required | PREV required |
| 004 | ~3 | `SKRRR`; neighbor checks time; Nari intercut | N, WORK + SKETCH if required | PREV useful |
| 005 | ~3–4 | Nari finishes/leaves after noise time | N, WORK + SKETCH if required | PREV useful |
| 006 | ~4 | morning corridor/elevator neighbor encounter | N, APT + SKETCH if required | none |
| 007 | ~5 | complaint begins | N, APT + SKETCH if required | PREV required |
| 008 | ~5 | walking + chair scrape specified | N, APT + SKETCH if required | PREV required |
| 009 | ~4 | Nari asks what time | N, APT + SKETCH if required | PREV required |
| 010 | 2–3 | `I wasn't home.` | N, APT + SKETCH recommended | PREV required |
| 011 | ~4 | publishing work resumes | N, WORK + SKETCH if required | none |
| 012 | ~5–6 | ordinary coworker/dry humor | N, WORK + SKETCH if required | PREV required |
| 013 | ~4 | timestamp evidence | N, WORK + SKETCH if required | PREV useful |
| 014 | ~5 | access history opened | N, WORK + SKETCH if required | PREV useful |
| 015 | ~3–4 | no ordinary entry | N, WORK + SKETCH recommended | PREV useful |
| 016 | ~5 | mundane explanations | N, WORK + SKETCH if required | PREV useful |
| 017 | ~5 | work interrupts investigation | N, WORK + SKETCH if required | PREV useful |
| 018 | ~3–4 | Nari decides to inspect home | N, WORK + SKETCH if required | PREV useful |
| 019 | ~4 | ordinary return home | N, APT + SKETCH if required | none |
| 020 | ~5 | practical inspection | N, APT + SKETCH if required | PREV required |
| 021 | ~4 | nothing dramatic found | N, APT + SKETCH if required | PREV required |
| 022 | ~3 | Chair B slightly displaced | N, APT + SKETCH recommended | PREV required |
| 023 | ~5 | self-doubt | N, APT + SKETCH if required | PREV required |
| 024 | ~4 | deliberately align Chair B | N, APT + SKETCH strongly recommended | PREV required |
| 025 | ~3 | exact known Chair B position | N, APT + SKETCH strongly recommended | PREV required |
| 026 | ~5 | normal home routine | N, APT + SKETCH if required | PREV required |
| 027 | ~5–6 | meal/cleanup/domestic rhythm | N, APT + SKETCH if required | PREV required |
| 028 | ~6 | optional offscreen call | N, APT + SKETCH if required | PREV required |
| 029 | ~5 | conversation moves away from mystery | N, APT + SKETCH if required | PREV required |
| 030 | ~4 | late-night quiet | N, APT + SKETCH if required | PREV required |
| 031 | ~4–5 | bedtime preparation | N, APT + SKETCH if required | PREV required |
| 032 | ~3 | final verified empty-room state | N, APT + SKETCH recommended | PREV required |
| 033 | ~2–3 | empty room; Chair B unchanged | APT + SKETCH recommended | PREV required |
| 034 | ~2 | extend stillness | APT + SKETCH recommended | PREV required |
| 035 | ~2–3 | restrained `SKRRR`; source unseen | APT + SKETCH strongly recommended | PREV required |
| 036 | 1–2 | Chair B visibly displaced | APT + SKETCH strongly recommended | PREV required |

---

## Dialogue Authority

Each page-production file must copy exact reader-visible wording from approved chapter story/dialogue authorities.

Do not let image generation invent or paraphrase text.

---

## Automatic Chapter-Wide Rejection Conditions

Reject/regenerate any page that introduces:

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
- cinematic/poster/key-art rendering
- excessive black cinematic masses
- glossy/painterly/photoreal/CGI treatment
- plastic/vector-clean AI linework

If a required approved layout sketch exists, also reject any material composition departure from it.

---

## Generation Sequence

For pages using mandatory sketch-first production:

`production MD → layout sketch PNG → review → approved layout sketch WebP → final page PNG → review → final page WebP`

Generate sequentially. Do not batch-generate the chapter blindly.

---

## Final Chapter QA

Verify:

- Nari identity remains stable
- environment geometry remains stable
- human-drawn manga character remains consistent
- no broad style-sheet reference caused cinematic drift
- required layout sketches were approved before their final pages
- Page 025 establishes Chair B known state clearly
- Chair B remains unchanged through Page 034 whenever visible
- Page 035 keeps movement source unseen
- Page 036 proves displacement without explanation
- Nari ends unaware of final movement
