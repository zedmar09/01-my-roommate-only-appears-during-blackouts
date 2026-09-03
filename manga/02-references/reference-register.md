# Reference Register

This is the production gate for canonical reference assets.

## Centralized WebP Rule

All approved final WebP visual authorities live in one folder:

`manga/02-references/approved-webp/`

Generation prompts must point to exact files in that folder. PNG review candidates remain local/intermediate and are not canonical authorities.

See:

- `manga/02-references/image-format-workflow.md`
- `manga/02-references/generation-attachment-map.md`

| Type | ID | Canon MD | PNG Review Candidate | Final Approved WebP | Status | Notes |
|---|---|---|---|---|---|---|
| STYLE | `series-manga-style-a` | `manga/01-style/manga-style-lock.md` | `series-manga-style-reference-a.png` | `manga/02-references/approved-webp/series-manga-style-reference-a.webp` | APPROVED | Strong character/anatomy/ink/hatching calibration. Rendering language only; never copy its subject identity. |
| STYLE | `series-manga-style-b` | `manga/01-style/manga-style-lock.md` | `series-manga-style-reference-b.png` | `manga/02-references/approved-webp/series-manga-style-reference-b.webp` | APPROVED | Complements A with adult-female, ordinary-life, domestic, quiet-suspense and environment language. Rendering language only. |
| CHARACTER | `nari` | `manga/02-references/characters/nari/canon.md` | `nari-canonical.png` | `manga/02-references/approved-webp/nari-canonical.webp` | APPROVED | Approved Yoon Nari identity authority. |
| ENVIRONMENT | `nari-apartment` | `manga/02-references/environments/nari-apartment/canon.md` | `nari-apartment-master-atlas.png` + optional `nari-apartment-floor-plan.png` | `manga/02-references/approved-webp/nari-apartment-master-atlas.webp` + optional `nari-apartment-floor-plan.webp` | TEXT APPROVED | **Next reference to generate.** Attach Style A + Style B. |
| ENVIRONMENT | `nari-workplace` | `manga/02-references/environments/nari-workplace/canon.md` | `nari-workplace-master-atlas.png` | `manga/02-references/approved-webp/nari-workplace-master-atlas.webp` | TEXT APPROVED | Attach Style A + Style B. Generate after/alongside apartment reference work. |

## Conditional Chapter 001 Candidate

- `hyejin` — possible trusted friend/coworker anchor. The old QA/technical occupation is retired. Do not create her package until her rebuilt role/design is separately approved and the Chapter 001 page plan confirms she is visually needed.

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
- `TEXT APPROVED` — canon/prompt approved; PNG visual candidate not yet approved
- `VISUAL REVIEW` — PNG candidate exists and is under review
- `APPROVED` — exact approved PNG was manually converted to WebP, the centralized WebP exists, and that WebP is safe to use in generation
- `RETIRED` — must not be used for new production

Only `APPROVED` WebPs may be used as required image authorities.

## Current Gate

Style A, Style B, and Nari are approved.

The next Chapter 001 reference generation is:

`nari-apartment-master-atlas.png`

Required WebP attachments:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

See `generation-attachment-map.md` before every generation so the exact attachment set never needs to be guessed.
