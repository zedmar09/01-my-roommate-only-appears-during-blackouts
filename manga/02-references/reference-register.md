# Reference Register

This is the production gate for canonical reference assets.

| Type | ID | Canon MD | Approved WebP | Status | Notes |
|---|---|---|---|---|---|
| STYLE | `series-manga-style` | `manga/01-style/manga-style-lock.md` | PENDING | PLANNED | Generate and approve the original black-and-white manga style reference first. |
| CHARACTER | `nari` | `manga/02-references/characters/nari/canon.md` | PENDING | PLANNED | Blocked until Nari occupation/design/wardrobe baseline is approved. |
| ENVIRONMENT | `nari-apartment` | `manga/02-references/environments/nari-apartment/canon.md` | PENDING | PLANNED | Blocked until apartment spatial canon and chair position are approved. Immediate common route should be merged if the atlas remains readable. |
| ENVIRONMENT | `nari-workplace` | `manga/02-references/environments/nari-workplace/canon.md` | PENDING | PLANNED | Blocked until Nari occupation/workplace identity is approved. |

## Conditional Chapter 001 Candidates

Do not add these as required packages until the story decision is made:

- `hyejin` — only if Koo Hyejin is formally retained as the recurring visible coworker/friend
- separate apartment common-route package — only if it cannot be covered safely by the Nari apartment master atlas

## Explicitly Deferred For Chapter 001

Do not generate solely for Chapter 001:

- Hyun-woo canonical
- building service/electrical-area atlas
- blackout visual-language atlas
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical

## Status Values

- `PLANNED` — story needs it, but package is not complete
- `TEXT APPROVED` — canon/prompt approved, visual reference still missing
- `VISUAL REVIEW` — candidate WebP exists but is not approved
- `APPROVED` — safe to use in page generation
- `RETIRED` — must not be used for new production

Only `APPROVED` entries may appear as required image authorities inside a page's `page-###-production.md`.
