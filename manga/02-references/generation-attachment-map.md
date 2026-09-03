# Generation Attachment Map

This file defines the exact visual attachments used for reference generation, layout-reference generation and final story-page generation.

All reusable canonical WebPs live in:

`manga/02-references/approved-webp/`

For layout-reference production, see:

`manga/04-production/layout-reference-workflow.md`

For all reader-visible language, see:

`manga/01-style/reader-visible-language-lock.md`

---

## Core Rule — Do Not Attach Everything

More image references are not automatically better.

Attach only files that directly control something visible or structurally important in the requested output.

---

## Global Language Rule

Story-page production is **English only** for reader-visible text.

Layout-reference generation is **text-free by default**:

- empty balloons
- no SFX lettering
- no signs/labels/UI/document text
- no Japanese/Korean/Chinese/other scripts
- no English placeholder text
- no fake readable writing

Final story-page generation may add only the exact approved English text from the current `page-###-production.md`.

Visual reference images may contain incidental text inside the reference itself, but that text must **never be copied into story-page or layout-reference output** unless the production MD explicitly approves exact English wording.

---

## Style A/B Policy

These approved assets remain available for **reference-development** work:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

They are **not automatic story-page attachments**.

For Chapter 001 layout references and final story pages, default to **NOT attaching Style A/B** because repeated generation showed that their visual finish can overpower the page Markdown.

Final story-page rendering is controlled by:

- `manga/01-style/manga-style-lock.md`
- `manga/01-style/reader-visible-language-lock.md`
- the exact current page-production MD

Style A/B may be used only if a specific production MD explicitly opts them in after successful page-specific testing.

---

## Canonical Character / Environment Pool

### Nari

`manga/02-references/approved-webp/nari-canonical.webp`

Use whenever Nari is visible. It controls identity only.

### Apartment

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Use when the approved apartment/common-route environment is visible. It controls geometry/design.

### Workplace

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Use when Nari's publishing workplace is visible. It controls geometry/design.

Canonical WebPs do not control final rendering finish or reader-visible language.

**Do not copy readable text from canonical WebPs into generated manga pages.**

---

## Separate Layout Reference Rule

When a page needs a composition lock, generate it separately using:

`page-###-layout-production.md`

Review candidate:

`page-###-layout-reference.png`

Approved visual authority:

`page-###-layout-reference.webp`

The layout reference controls:

- panel boundaries/proportions
- page rhythm
- camera/framing
- character blocking
- poses/gestures
- major prop/environment placement
- negative space
- empty speech-balloon placement

It should be a clean content-filled 2D manga layout draft/reference — not empty boxes and not a rough scribble sketch.

It should contain **zero readable text** unless the user explicitly approves a page-specific exception.

---

## Typical Layout-Reference Attachments

1. `page-###-layout-production.md`
2. required canonical character WebP(s)
3. required environment atlas WebP(s)
4. required object/effect WebP(s) only when staging depends on them

Do not automatically attach Style A/B.

Do not reproduce text found in attached canonical images.

---

## Typical Final Story-Page Attachments

1. `page-###-production.md`
2. approved `page-###-layout-reference.webp` when the page requires one
3. required canonical character WebP(s)
4. required environment/object/effect WebP(s)
5. immediately previous approved page WebP only when local seam continuity requires it

Do not automatically attach Style A/B.

Final lettering must remain exact approved English.

---

## Page 001 — Exact Layout-Reference Generation

Use separate production:

`manga/04-production/arc-01/chapter-001/page-001-layout-production.md`

Attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-layout-production.md`
2. `manga/02-references/approved-webp/nari-canonical.webp`
3. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

Generate/review:

`page-001-layout-reference.png`

Required text state:

- Panel 2 balloon EMPTY
- Panel 3 balloon EMPTY
- no readable text anywhere else

After approval, manually convert and commit:

`manga/04-production/arc-01/chapter-001/page-001-layout-reference.webp`

---

## Page 001 — Exact Final Page Generation

Only after the approved layout reference exists, attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/04-production/arc-01/chapter-001/page-001-layout-reference.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp`
4. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

Permitted reader-visible text only:

- `You're still here?`
- `Just one more pass.`

No other readable words are permitted.

---

## Workplace Page With Visible Nari

Default final-page attachment pattern:

- page production MD
- approved layout reference when required
- Nari canonical
- workplace atlas
- previous approved page only when seam continuity materially helps

---

## Apartment / Corridor / Elevator Page With Visible Nari

Default:

- page production MD
- approved layout reference when required
- Nari canonical
- apartment atlas
- previous approved page when local scene continuity requires it

---

## Empty Apartment Page

Default:

- page production MD
- approved layout reference when required
- apartment atlas
- previous approved page when exact Chair B/camera continuity requires it

Do not attach Nari merely because she owns the apartment.

---

## Downstairs-Neighbor-Only Pages

The neighbor is chapter-local.

Use:

- page production MD
- approved layout reference when required
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

It never overrides current page production, approved layout reference, canonical character/environment design, or the English-only language lock.

---

## Chapter Production Authority

Before generation, consult the exact current production Markdown and:

`manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

Never attach every available WebP automatically.
