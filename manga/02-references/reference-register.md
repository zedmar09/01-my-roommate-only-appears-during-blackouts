# Reference Register

This is the production gate for canonical reference assets.

## Centralized WebP Rule

All approved final WebP visual authorities live in:

`manga/02-references/approved-webp/`

Generation/page-production prompts must point to exact files in that folder. PNG review candidates remain intermediate and are not canonical authorities.

See:

- `manga/02-references/image-format-workflow.md`
- `manga/02-references/generation-attachment-map.md`
- `manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

| Type | ID | Canon MD | PNG Review Candidate | Final Approved WebP | Status | Notes |
|---|---|---|---|---|---|---|
| STYLE | `series-manga-style-a` | `manga/01-style/manga-style-lock.md` | `series-manga-style-reference-a.png` | `manga/02-references/approved-webp/series-manga-style-reference-a.webp` | APPROVED | Rendering-language authority A. Never copy its generic subject identity. |
| STYLE | `series-manga-style-b` | `manga/01-style/manga-style-lock.md` | `series-manga-style-reference-b.png` | `manga/02-references/approved-webp/series-manga-style-reference-b.webp` | APPROVED | Rendering-language authority B for adult-female, ordinary-life, domestic and quiet-suspense treatment. |
| CHARACTER | `nari` | `manga/02-references/characters/nari/canon.md` | `nari-canonical.png` | `manga/02-references/approved-webp/nari-canonical.webp` | APPROVED | Yoon Nari identity authority. |
| ENVIRONMENT | `nari-apartment` | `manga/02-references/environments/nari-apartment/canon.md` | `nari-apartment-master-atlas.png` | `manga/02-references/approved-webp/nari-apartment-master-atlas.webp` | APPROVED | Apartment master atlas also provides sufficient Chapter 001 floor-plan/spatial authority; no separate floor-plan image required. |
| ENVIRONMENT | `nari-workplace` | `manga/02-references/environments/nari-workplace/canon.md` | `nari-workplace-master-atlas.png` | `manga/02-references/approved-webp/nari-workplace-master-atlas.webp` | APPROVED | Publishing-company workplace authority for daytime and late-night scenes. |

## Chapter 001 Reference Gate

**CORE REUSABLE REFERENCE SET COMPLETE.**

Chapter 001 page-production files may now be compiled using the approved references above.

No reusable Hyejin reference is required for Chapter 001. Any optional phone/friend presence remains offscreen. The downstairs neighbor is chapter-local and should be preserved through adjacent approved-page continuity rather than a full canonical atlas.

## Explicitly Deferred For Chapter 001

Do not generate solely for Chapter 001:

- Hyun-woo canonical
- separate apartment floor-plan image
- building service/electrical-area atlas
- blackout visual-language atlas
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical
- full neighbor canonical
- Hyejin canonical

## Status Values

- `PLANNED` — story needs it, but semantic package is not complete
- `TEXT APPROVED` — canon/prompt approved; visual candidate not yet accepted
- `VISUAL REVIEW` — PNG candidate exists and is under review
- `APPROVED` — exact approved PNG was manually converted to WebP, centralized WebP exists, and it is safe for generation
- `RETIRED` — must not be used for new production

Only `APPROVED` WebPs may be used as required reusable image authorities.