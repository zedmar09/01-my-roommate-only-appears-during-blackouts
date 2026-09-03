# Reference Register

This is the production gate for reusable canonical reference assets.

## Centralized WebP Rule

All approved reusable final WebPs live in:

`manga/02-references/approved-webp/`

PNG review candidates are not reusable authorities.

See:

- `manga/02-references/image-format-workflow.md`
- `manga/02-references/generation-attachment-map.md`
- `manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

| Type | ID | Canon MD | Final Approved WebP | Status | Story-Page Role |
|---|---|---|---|---|---|
| STYLE | `series-manga-style-a` | `manga/01-style/manga-style-lock.md` | `manga/02-references/approved-webp/series-manga-style-reference-a.webp` | APPROVED | Reference-development asset; not a default Chapter 001 story-page attachment. |
| STYLE | `series-manga-style-b` | `manga/01-style/manga-style-lock.md` | `manga/02-references/approved-webp/series-manga-style-reference-b.webp` | APPROVED | Reference-development asset; not a default Chapter 001 story-page attachment. |
| CHARACTER | `nari` | `manga/02-references/characters/nari/canon.md` | `manga/02-references/approved-webp/nari-canonical.webp` | APPROVED | Attach when Nari is visible; identity authority only. |
| ENVIRONMENT | `nari-apartment` | `manga/02-references/environments/nari-apartment/canon.md` | `manga/02-references/approved-webp/nari-apartment-master-atlas.webp` | APPROVED | Attach when apartment/common-route geometry is visible. |
| ENVIRONMENT | `nari-workplace` | `manga/02-references/environments/nari-workplace/canon.md` | `manga/02-references/approved-webp/nari-workplace-master-atlas.webp` | APPROVED | Attach when publishing-workplace geometry is visible. |

## Approval Does Not Mean Automatic Attachment

The register answers whether an asset is safe to use. It does not require all approved assets to be attached.

For actual generation, follow:

`manga/02-references/generation-attachment-map.md`

For Chapter 001 story pages, the default is to omit Style A/B unless an exact page-production MD explicitly opts them in.

## Page-Local Layout References

Approved page layout references such as:

`page-001-layout-reference.webp`

are page-local production authorities, not reusable reference-register assets. They stay under `manga/04-production/` beside their page files.

## Chapter 001 Reference Gate

**CORE REUSABLE REFERENCE SET COMPLETE.**

No reusable Hyejin reference is required for Chapter 001. The downstairs neighbor is chapter-local and should be preserved through adjacent-page continuity rather than a full canonical atlas.

## Explicitly Deferred For Chapter 001

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

- `PLANNED`
- `TEXT APPROVED`
- `VISUAL REVIEW`
- `APPROVED`
- `RETIRED`

Only `APPROVED` reusable WebPs may be required as canonical visual authorities.