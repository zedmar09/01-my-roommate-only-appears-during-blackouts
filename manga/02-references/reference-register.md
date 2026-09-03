# Reference Register

This is the production gate for canonical reference assets.

## Image Format Rule

All first-generation visual candidates are PNG. After visual approval, the user manually converts the exact accepted PNG to WebP. Only the WebP is final repository authority.

See `manga/02-references/image-format-workflow.md`.

| Type | ID | Canon MD | PNG Review Candidate | Final Approved WebP | Status | Notes |
|---|---|---|---|---|---|---|
| STYLE | `series-manga-style` | `manga/01-style/manga-style-lock.md` | `series-manga-style-reference.png` | `manga/01-style/reference-style/series-manga-style-reference.webp` | TEXT APPROVED | **Generate the PNG first.** After approval, manually convert it to the listed WebP. |
| CHARACTER | `nari` | `manga/02-references/characters/nari/canon.md` | `nari-canonical.png` | `manga/02-references/characters/nari/nari-canonical.webp` | TEXT APPROVED | Nari baseline approved: 30-year-old publishing editor. Generate PNG only after the style WebP is approved. |
| ENVIRONMENT | `nari-apartment` | `manga/02-references/environments/nari-apartment/canon.md` | `nari-apartment-master-atlas.png` + optional `nari-apartment-floor-plan.png` | `manga/02-references/environments/nari-apartment/nari-apartment-master-atlas.webp` + optional `nari-apartment-floor-plan.webp` | TEXT APPROVED | 40–45 m² one-bedroom, two-chair continuity system, neighbor directly below. Generate PNG candidate(s) after style approval. |
| ENVIRONMENT | `nari-workplace` | `manga/02-references/environments/nari-workplace/canon.md` | `nari-workplace-master-atlas.png` | `manga/02-references/environments/nari-workplace/nari-workplace-master-atlas.webp` | TEXT APPROVED | Mid-sized publishing-company editorial office. Generate PNG after style approval. |

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
- `TEXT APPROVED` — canon/prompt approved; no visual candidate yet
- `VISUAL REVIEW` — PNG generation candidate exists and is under review; it is not canonical authority
- `APPROVED` — exact approved PNG was manually converted to WebP, the WebP exists in the repository, and that WebP is safe to use in page generation
- `RETIRED` — must not be used for new production

Only `APPROVED` WebPs may appear as required image authorities inside a page's `page-###-production.md`.

## Current Gate

The only image that should be generated **now** is the PNG review candidate:

`series-manga-style-reference.png`

After it passes review, manually convert it to:

`manga/01-style/reference-style/series-manga-style-reference.webp`

Then mark the style package `APPROVED`. Do not generate Nari/apartment/workplace PNG candidates until that approved style WebP exists.
