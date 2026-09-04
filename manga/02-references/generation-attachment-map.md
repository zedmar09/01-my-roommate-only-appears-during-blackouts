# Generation Attachment Map

This file defines exact visual attachments used for reference and story-page generation.

Approved reusable WebPs live in:

`manga/02-references/approved-webp/`

For reader-visible language, see:

`manga/01-style/reader-visible-language-lock.md`

For optional layout troubleshooting only, see:

`manga/04-production/layout-reference-workflow.md`

---

## Core Rule — Attach Only What Controls the Output

Normal story-page production is direct from:

- current `page-###-production.md`
- required canonical visual(s)
- previous approved page only when local continuity materially requires it

Do not attach everything automatically.

Do not insert a layout-reference stage automatically.

---

## Global Language Rule

Final story pages use **English only** for reader-visible text.

Only exact approved English text from the page-production MD may appear.

Default readable background text: **none**.

Do not copy incidental text from canonical images.

---

## Style A/B Policy

The approved Style A/B assets remain reference-development resources, but they are **not default story-page attachments**.

For Chapter 001, omit by default:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`

Reason: they can overpower page-specific instructions and character identity.

Final story-page rendering is controlled by:

- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`
- exact current page-production MD

---

## Canonical Character / Environment Pool

### Nari — Exact Identity Authority

`manga/02-references/approved-webp/nari-canonical.webp`

Attach whenever Nari is visible.

This file controls **identity only**:

- exact mature face proportions
- narrow almond eye shape
- strong slightly angular brows
- nose/lip/jaw read
- short-to-medium shaggy layered dark hair
- asymmetrical face-framing strands
- age read
- **absence of beauty mark/mole/facial dot**

Do **not** genericize or soften Nari away from this image.

Do **not** copy incidental source elements from the canonical image:

- headphones
- techwear/hoodie
- cyberpunk background
- neon lighting
- glowing circuitry/tattoos
- source props
- source color palette
- cinematic poster mood

Story wardrobe/rendering come from semantic canon and page production.

### Apartment

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Attach when approved apartment/common-route geometry is visible. Geometry/design only.

### Workplace

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Attach when Nari's publishing workplace is visible. Geometry/design only.

Canonical WebPs do not control reader-visible language.

---

## Typical Direct Final Story-Page Attachments

1. `page-###-production.md`
2. required character canonical(s)
3. required environment/object/effect canonical(s)
4. immediately previous approved page only when local seam continuity materially requires it

Do not automatically attach:

- Style A/B
- layout references
- extra canon/story MDs

The exact page-production MD is the final attachment authority.

---

## Page 001 — Exact Direct Final Generation

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

### Page 001 identity rule

Nari must match the exact canonical female face/hair identity.

Reject if:

- face becomes generic/soft/round
- eye/brow structure drifts
- hair becomes smooth bob or long hair
- **any beauty mark/mole/facial dot appears**
- headphones/techwear/neon/cyberpunk source elements appear

Permitted reader-visible text only:

- `You're still here?`
- `Just one more pass.`

No other readable words are permitted.

---

## Workplace Page With Visible Nari

Default:

- page production MD
- current Nari canonical
- workplace atlas
- previous approved page only when seam continuity helps

The current Nari canonical controls identity even when the page-production scene uses different grounded clothing.

---

## Apartment / Corridor / Elevator Page With Visible Nari

Default:

- page production MD
- current Nari canonical
- apartment atlas
- previous approved page when local continuity requires it

---

## Empty Apartment Page

Default:

- page production MD
- apartment atlas
- previous approved page when exact Chair B/camera continuity requires it

Do not attach Nari merely because she owns the apartment.

---

## Downstairs-Neighbor-Only Pages

Use:

- page production MD
- previous approved page for neighbor/interior continuity when needed

Do not create a full reusable neighbor canonical solely for Chapter 001.

---

## Previous-Page Continuity

Previous approved page art is local seam authority only for:

- pose/facing direction
- temporary object state
- chapter-local neighbor appearance
- environment crop
- Chair B exact position
- ongoing motion/action

It never overrides current page production or canonical character/environment identity.

---

## Optional Layout-Reference Troubleshooting

A layout reference is **not normal production**.

Use only if direct generation repeatedly fails composition/temporary geometry and the user explicitly invokes the fallback.

Page 001's old layout-production file is deprecated and not needed for normal Page 001 generation.

---

## Chapter Production Authority

Before generation, consult the exact current production Markdown and:

`manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

Never attach every available WebP automatically.
