# Generation Attachment Map

This file defines the exact visual attachments used for reference generation and story-page generation.

All reusable canonical WebPs live in:

`manga/02-references/approved-webp/`

For all reader-visible language, see:

`manga/01-style/reader-visible-language-lock.md`

For optional layout-reference troubleshooting only, see:

`manga/04-production/layout-reference-workflow.md`

---

## Core Rule — Do Not Attach Everything

More image references are not automatically better.

Attach only files that directly control something visible or structurally important in the requested output.

Normal story-page production is **direct** from the current `page-###-production.md` plus required canonical visuals.

Do not insert a layout-reference stage automatically.

---

## Global Language Rule

Story-page production is **English only** for reader-visible text.

Final story-page generation may add only exact approved English text from the current `page-###-production.md`.

Default background text: **none**.

Do not copy incidental text visible inside canonical reference images.

Forbidden unless explicitly approved:

- Japanese/Korean/Chinese/other non-English scripts
- fake multilingual glyphs
- translated dialogue/SFX
- invented readable labels/signs/documents/UI
- pseudo-writing that appears readable

---

## Style A/B Policy

These approved assets remain available for **reference-development** work:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

They are **not automatic story-page attachments**.

For Chapter 001 final story pages, default to **NOT attaching Style A/B** because repeated generation showed that their visual finish can overpower the page Markdown.

Final story-page rendering is controlled by:

- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`
- the exact current page-production MD

Style A/B may be used only if a specific production MD explicitly opts them in after successful page-specific testing.

---

## Canonical Character / Environment Pool

### Nari

`manga/02-references/approved-webp/nari-canonical.webp`

Use whenever Nari is visible. Identity only.

### Apartment

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Use when the approved apartment/common-route environment is visible. Geometry/design only.

### Workplace

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Use when Nari's publishing workplace is visible. Geometry/design only.

Canonical WebPs do not control final composition, final rendering finish or reader-visible language.

---

## Typical Direct Final Story-Page Attachments

1. `page-###-production.md`
2. required canonical character WebP(s)
3. required environment/object/effect WebP(s)
4. immediately previous approved page WebP only when local seam continuity materially requires it

Do not automatically attach:

- Style A/B
- layout references
- extra canon/story MDs

The exact page-production MD is the final attachment authority.

---

## Page 001 — Exact Direct Final Page Generation

Use:

`manga/04-production/arc-01/chapter-001/page-001-production.md`

Attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/02-references/approved-webp/nari-canonical.webp`
3. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach:

- Style A/B
- `page-001-layout-production.md`
- `page-001-layout-reference.webp`
- previous page

Generate directly:

`page-001.png`

Permitted reader-visible text only:

- `You're still here?`
- `Just one more pass.`

No other readable words are permitted.

After visual approval, manually convert exact accepted PNG to:

`page-001.webp`

---

## Workplace Page With Visible Nari

Default final-page attachment pattern:

- page production MD
- Nari canonical
- workplace atlas
- previous approved page only when seam continuity materially helps

No layout reference unless explicitly invoked as troubleshooting.

---

## Apartment / Corridor / Elevator Page With Visible Nari

Default:

- page production MD
- Nari canonical
- apartment atlas
- previous approved page when local scene continuity requires it

No layout reference unless explicitly invoked as troubleshooting.

---

## Empty Apartment Page

Default:

- page production MD
- apartment atlas
- previous approved page when exact Chair B/camera continuity requires it

Do not attach Nari merely because she owns the apartment.

For story-critical Chair B pages, try direct production + previous approved page first. Invoke a layout-reference fallback only if geometry still repeatedly fails.

---

## Downstairs-Neighbor-Only Pages

The neighbor is chapter-local.

Use:

- page production MD
- previous approved page for neighbor/interior continuity where needed

Do not create a full reusable neighbor canonical solely for Chapter 001.

---

## Previous-Page Continuity

Previous approved page art is local seam authority only for:

- pose/facing direction
- temporary object state
- chapter-local neighbor appearance
- ongoing environment crop
- Chair B exact position
- ongoing motion/action

It never overrides current page production, canonical character/environment design, final manga style or the English-only language lock.

---

## Optional Layout-Reference Troubleshooting

A layout reference is **not normal production**.

Use only if direct generation repeatedly fails composition or temporary geometry and the user explicitly invokes the fallback.

If used:

1. `page-###-layout-production.md`
2. required canonical visual references
3. generate a text-free `page-###-layout-reference.png`
4. approve/convert to WebP
5. attach it only when the final page-production MD has been updated to use it

Troubleshooting layout images contain zero readable text and empty balloons only.

Page 001's old layout-production file is deprecated and is not needed for normal Page 001 generation.

---

## Chapter Production Authority

Before generation, consult the exact current production Markdown and:

`manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

Never attach every available WebP automatically.
