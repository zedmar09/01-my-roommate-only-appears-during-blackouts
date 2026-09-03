# Reference Register

This is the production gate for canonical reference assets.

| Type | ID | Canon MD | Planned/Approved WebP | Status | Notes |
|---|---|---|---|---|---|
| STYLE | `series-manga-style` | `manga/01-style/manga-style-lock.md` | `manga/01-style/reference-style/series-manga-style-reference.webp` | TEXT APPROVED | **Generate this first.** Original broad black-and-white manga calibration image; no copied characters/panels/compositions. |
| CHARACTER | `nari` | `manga/02-references/characters/nari/canon.md` | `manga/02-references/characters/nari/nari-canonical.webp` | TEXT APPROVED | Nari baseline approved: 30-year-old publishing editor. Generate only after the style WebP is approved. |
| ENVIRONMENT | `nari-apartment` | `manga/02-references/environments/nari-apartment/canon.md` | `manga/02-references/environments/nari-apartment/nari-apartment-master-atlas.webp` + `nari-apartment-floor-plan.webp` | TEXT APPROVED | 40–45 m² one-bedroom, two-chair continuity system, neighbor directly below, immediate common route merged when possible. Generate after style approval. |
| ENVIRONMENT | `nari-workplace` | `manga/02-references/environments/nari-workplace/canon.md` | `manga/02-references/environments/nari-workplace/nari-workplace-master-atlas.webp` | TEXT APPROVED | Mid-sized publishing-company editorial office. Generate after style approval. |

## Conditional Chapter 001 Candidate

- `hyejin` — possible trusted friend/coworker anchor. The old QA/technical occupation is retired. Do not create her package until her rebuilt role and manga design are separately approved and the Chapter 001 page plan confirms she is visually needed.

## Explicitly Deferred For Chapter 001

Do not generate solely for Chapter 001:

- Hyun-woo canonical
- building service/electrical-area atlas
- blackout visual-language atlas
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical
- full neighbor canonical unless later story planning makes the neighbor recurring

## Status Values

- `PLANNED` — story needs it, but semantic package is not complete
- `TEXT APPROVED` — canon/prompt approved, visual reference still missing
- `VISUAL REVIEW` — candidate WebP exists but is not approved
- `APPROVED` — safe to use in page generation
- `RETIRED` — must not be used for new production

Only `APPROVED` entries may appear as required image authorities inside a page's `page-###-production.md`.

## Current Gate

The only image that should be generated **now** is `series-manga-style-reference.webp`.

Do not generate Nari/apartment/workplace images until that style candidate is reviewed and marked `APPROVED`.
