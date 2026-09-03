# Manga Generation Standard

## Generation Unit

Generate **one complete manga page at a time** unless a deliberate edit/correction is being made to an already approved page. The page may contain one panel, many panels, inset panels, borderless panels, reaction cut-ins, or a full-page image as required by the page map.

## Required Authorities Before Generation

A page-generation prompt must resolve all applicable authorities:

1. series/world/continuity Markdown
2. Arc and Chapter story Markdown
3. manga style Markdown
4. approved style-reference WebP(s), when used
5. each required character `canon.md` + approved canonical WebP
6. each required environment `canon.md` + approved atlas/floor-plan WebP(s)
7. each required object/effect `canon.md` + approved WebP(s)
8. immediately previous approved page WebP when local continuity requires it
9. current page blueprint and exact dialogue/SFX

Missing required visual authority is a **STOP**, not permission to improvise a replacement design.

## Image File Rule

- generation may initially produce PNG for review
- repository canonical references should be lossless/visually lossless WebP
- approved final manga pages should preferably be stored as lossless WebP for compact Git storage without damaging line art
- rejected/intermediate images are not authority

## Anti-Drift Rule

Page prompts must list exact repository paths. Never say only "use Nari reference" or "same apartment" when an approved file exists.

## No Reference Duplication

Do not copy canonical WebPs into each page folder. The page manifest points to the single source-of-truth file under `02-references/`.
