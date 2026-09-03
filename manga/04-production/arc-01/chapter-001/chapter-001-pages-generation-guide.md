# Chapter 001 Pages Generation Guide

## Status

**APPROVED PRODUCTION GUIDE — DIRECT FINAL-PAGE WORKFLOW.**

Chapter 001 story pages are generated directly from their exact `page-###-production.md` files plus only the canonical visual references needed for that page.

A separate layout-reference step is **not part of the normal workflow**.

Story authority remains under `manga/03-story/`.

See also:

- `manga/04-production/page-production-standard.md`
- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`
- `manga/02-references/generation-attachment-map.md`

---

## Chapter Function

Chapter 001 begins as an ordinary apartment-security mystery.

Nari is provably at her publishing-company workplace while the downstairs neighbor hears activity from her supposedly empty apartment. The chapter follows mundane security logic, a weak chair clue, a deliberate known-state test, ordinary domestic life, then a reader-only final chair movement.

The chapter must not reveal Hyun-woo, a roommate claim, the blackout rule or the wider mechanism.

---

## Normal Production Sequence

For every page, the default sequence is:

`page-###-production.md → final page PNG → visual review → approved final WebP`

Do not generate an additional layout-reference image unless direct generation has repeatedly failed and the user explicitly chooses the troubleshooting workflow.

Final approved page example:

`page-001.png` → approve → manually convert exact accepted PNG → `page-001.webp`

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

## Global Reader-Visible Language Lock — ENGLISH ONLY

Every Chapter 001 final page uses **English only** for reader-visible text.

This includes:

- dialogue
- thoughts
- narration/captions
- SFX
- story-required signs/labels/UI/notes

Rules:

- exact English wording must be copied into each final `page-###-production.md`
- never translate approved English into Japanese, Korean, Chinese or another language
- never invent pseudo-foreign glyphs or fake multilingual text
- never invent readable background text
- documents/books/binders/screens/signs are unreadable by default
- story-required background text must be exact approved English
- SFX use exact approved English/Latin-letter forms such as `THUMP` and `SKRRR`

Any non-English reader-visible text = **AUTOMATIC REJECT**.

Global authority:

`manga/01-style/reader-visible-language-lock.md`

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

They are **not default Chapter 001 story-page attachments**.

Default: **omit Style A/B from story-page generation**.

Only opt them into a specific page if the exact page-production MD explicitly requires them after successful testing.

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

Canonical images control identity/geometry, not final page composition, rendering finish or reader-visible language.

Do not copy incidental readable text from canonical images into generated story pages.

---

## Page 001 — Direct Final-Page Production

Page 001 does **not** require a layout reference.

Use:

`manga/04-production/arc-01/chapter-001/page-001-production.md`

Attach exactly:

1. `page-001-production.md`
2. `nari-canonical.webp`
3. `nari-workplace-master-atlas.webp`

Do not attach:

- Style A
- Style B
- `page-001-layout-reference.webp`
- `page-001-layout-production.md`

Generate directly:

`page-001.png`

Page 001 reader-visible text is limited to exactly:

- `You're still here?`
- `Just one more pass.`

No other readable words are permitted.

After approval, manually convert the exact accepted PNG to:

`page-001.webp`

---

## Previous-Page Continuity

Starting with Page 002, use the immediately previous approved page WebP only when it materially helps:

- pose/facing direction
- chapter-local neighbor identity
- environment crop
- Chair B state
- temporary clothing/object state
- ongoing action

Previous-page art never overrides:

1. current `page-###-production.md`
2. character canonical
3. environment canonical
4. global manga-style lock
5. English-only language lock

---

## Optional Layout-Reference Troubleshooting — EXCEPTION ONLY

A separate `page-###-layout-production.md` / `page-###-layout-reference.webp` workflow is available only when:

- direct generation repeatedly changes panel structure,
- precise temporary geometry cannot be held,
- blocking/camera continuity repeatedly fails,
- or the user explicitly decides a page needs a composition lock.

It is **not a default production requirement**.

If used:

- layout output is text-free with empty balloons
- the final `page-###-production.md` remains the story/lettering/rendering authority
- the layout reference controls composition only
- Style A/B remain omitted unless explicitly opted in

Page 001's old layout-production file is deprecated and should not be used normally.

Pages 024–036 may benefit from this fallback if Chair B geometry repeatedly drifts, but it is not mandatory.

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

Page 035 contains restrained `SKRRR` with source unseen.

Page 036 shows Chair B displaced.

For Pages 024–036, use the previous approved page aggressively for local Chair B continuity. Only invoke an optional layout-reference fallback if direct production still cannot preserve the geometry reliably.

---

## Page-by-Page Reference Matrix

Legend:

- `N` = Nari canonical
- `APT` = apartment atlas
- `WORK` = workplace atlas
- `PREV` = previous approved page
- `LAYOUT*` = optional troubleshooting layout reference only if explicitly invoked

Style A/B are intentionally omitted.

| Page | Panels Guide | Core Beat | Canonical Visual Refs | Local Continuity |
|---|---:|---|---|---|
| 001 | ~4 | late-night publishing office; Nari still away from home | N, WORK | none |
| 002 | ~4–5 | neighbor hears first human-weight movement | page production MD | none |
| 003 | ~4 | footsteps / `THUMP`; neighbor reacts | page production MD | PREV required |
| 004 | ~3 | `SKRRR`; neighbor checks time; Nari intercut | N, WORK | PREV useful |
| 005 | ~3–4 | Nari finishes/leaves after noise time | N, WORK | PREV useful |
| 006 | ~4 | morning corridor/elevator neighbor encounter | N, APT | none |
| 007 | ~5 | complaint begins | N, APT | PREV required |
| 008 | ~5 | walking + chair scrape specified | N, APT | PREV required |
| 009 | ~4 | Nari asks what time | N, APT | PREV required |
| 010 | 2–3 | `I wasn't home.` | N, APT | PREV required |
| 011 | ~4 | publishing work resumes | N, WORK | none |
| 012 | ~5–6 | ordinary coworker/dry humor | N, WORK | PREV required |
| 013 | ~4 | timestamp evidence | N, WORK | PREV useful |
| 014 | ~5 | access history opened | N, WORK | PREV useful |
| 015 | ~3–4 | no ordinary entry | N, WORK | PREV useful |
| 016 | ~5 | mundane explanations | N, WORK | PREV useful |
| 017 | ~5 | work interrupts investigation | N, WORK | PREV useful |
| 018 | ~3–4 | Nari decides to inspect home | N, WORK | PREV useful |
| 019 | ~4 | ordinary return home | N, APT | none |
| 020 | ~5 | practical inspection | N, APT | PREV required |
| 021 | ~4 | nothing dramatic found | N, APT | PREV required |
| 022 | ~3 | Chair B slightly displaced | N, APT | PREV required |
| 023 | ~5 | self-doubt | N, APT | PREV required |
| 024 | ~4 | deliberately align Chair B | N, APT | PREV required; LAYOUT* only if needed |
| 025 | ~3 | exact known Chair B position | N, APT | PREV required; LAYOUT* only if needed |
| 026 | ~5 | normal home routine | N, APT | PREV required |
| 027 | ~5–6 | meal/cleanup/domestic rhythm | N, APT | PREV required |
| 028 | ~6 | optional offscreen call | N, APT | PREV required |
| 029 | ~5 | conversation moves away from mystery | N, APT | PREV required |
| 030 | ~4 | late-night quiet | N, APT | PREV required |
| 031 | ~4–5 | bedtime preparation | N, APT | PREV required |
| 032 | ~3 | final verified empty-room state | N, APT | PREV required; LAYOUT* if geometry fails |
| 033 | ~2–3 | empty room; Chair B unchanged | APT | PREV required; LAYOUT* if geometry fails |
| 034 | ~2 | extend stillness | APT | PREV required; LAYOUT* if geometry fails |
| 035 | ~2–3 | restrained `SKRRR`; source unseen | APT | PREV required; LAYOUT* if geometry fails |
| 036 | 1–2 | Chair B visibly displaced | APT | PREV required; LAYOUT* if geometry fails |

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

---

## Generation Sequence

Normal:

`page-production MD → final PNG → review → final WebP`

Optional troubleshooting only:

`layout-production MD → text-free layout-reference → final page-production MD → final PNG`

Do not batch-generate the chapter blindly.

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
- layout-reference generation was used only when genuinely needed
- Page 025 establishes Chair B known state clearly
- Chair B remains unchanged through Page 034 whenever visible
- Page 035 keeps movement source unseen
- Page 036 proves displacement without explanation
- Nari ends unaware of final movement
