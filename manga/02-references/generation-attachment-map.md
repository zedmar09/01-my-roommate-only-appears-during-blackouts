# Generation Attachment Map

This file answers one question for every generation step:

**Which approved WebP images must be attached for the strongest continuity without overpowering the page-specific Markdown?**

All reusable canonical WebP authorities live in:

`manga/02-references/approved-webp/`

For sketch-first page production, also see:

`manga/04-production/layout-sketch-workflow.md`

---

## Core Rule — Story Pages vs Reference Development

The reusable style sheets:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

remain approved reference-development assets.

They are **not automatic story-page generation attachments**.

For Chapter 001 story-page sketches and final story pages, default to **NOT attaching Style A/B** because their visual finish may overpower the page Markdown and cause cinematic, heavy-black, glossy or key-art drift.

The written page-production file and global manga style lock control story-page rendering.

---

## Approved Canonical Visual Pool

### Character

`manga/02-references/approved-webp/nari-canonical.webp`

Use when Nari is visible. It controls identity only:

- face
- hair
- age read
- proportions
- approved outfit construction

It does not control page composition or rendering finish.

### Environment

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Use when the approved apartment/common-route environment is visible.

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Use when Nari's publishing workplace is visible.

Environment atlases control spatial/design continuity, not cinematic finish.

---

## Page-Specific Layout Sketch Rule

If a `page-###-production.md` declares an approved layout sketch required, attach:

`page-###-layout-sketch.webp`

for Stage B final-page generation.

The layout sketch controls:

- panel boundaries
- panel proportions
- page rhythm
- camera/framing
- character blocking
- major prop placement
- negative-space structure
- balloon-placement intent

The final generator must not redesign or cinematicize the approved sketch.

Missing required layout sketch = **STOP FINAL PAGE GENERATION**.

---

## Stage A — Layout Sketch Attachments

Typical layout-sketch generation request:

1. `page-###-production.md`
2. required character canonical WebP(s)
3. required environment atlas WebP(s)
4. required object/effect WebP(s) only if essential to staging

Do not automatically attach Style A/B.

The Stage A output is a rough human-drawn manga page layout, not finished key art.

---

## Stage B — Final Page Attachments

Typical final-page generation request:

1. `page-###-production.md`
2. approved `page-###-layout-sketch.webp` when required
3. required character canonical WebP(s)
4. required environment/object/effect WebP(s)
5. previous approved page WebP only when local seam continuity is materially needed

Do not automatically attach Style A/B.

---

## Page 001 — Exact Workflow

### Stage A — Generate Page 001 layout sketch

Attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/02-references/approved-webp/nari-canonical.webp`
3. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

Generate:

`page-001-layout-sketch.png`

After approval, manually convert the exact accepted PNG and commit:

`manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`

### Stage B — Generate final Page 001

Only after the approved sketch exists, attach exactly:

1. `manga/04-production/arc-01/chapter-001/page-001-production.md`
2. `manga/04-production/arc-01/chapter-001/page-001-layout-sketch.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp`
4. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Do not attach Style A/B.

---

## Workplace Page With Visible Nari

Default story-page attachments:

- page production MD
- approved page layout sketch if required
- Nari canonical
- workplace atlas
- previous approved page only if seam continuity requires it

No Style A/B by default.

---

## Apartment / Corridor / Elevator Page With Visible Nari

Default story-page attachments:

- page production MD
- approved page layout sketch if required
- Nari canonical
- apartment atlas
- previous approved page when scene continuity requires it

No Style A/B by default.

---

## Empty Apartment Page

Default story-page attachments:

- page production MD
- approved page layout sketch if required
- apartment atlas
- previous approved page when exact Chair B/camera continuity requires it

Do not attach Nari canonical merely because she owns the apartment.

No Style A/B by default.

---

## Downstairs-Neighbor-Only Pages

The neighbor remains chapter-local.

Use:

- page production MD
- approved layout sketch if required
- previous approved page for neighbor/interior continuity when needed

Do not create speculative reusable neighbor canon solely for Chapter 001.

No Style A/B by default.

---

## Previous-Page Continuity

The previous approved manga page may be attached only for local seam continuity:

- pose/facing direction
- temporary object state
- chapter-local neighbor identity
- ongoing environment crop
- Chair B position
- ongoing action

Previous-page art never overrides canonical identity/geometry or the page-specific approved layout sketch.

---

## Style A/B Opt-In Exception

A specific story-page production MD may opt Style A/B back in only if:

1. repeated testing demonstrates that they improve that page,
2. they do not overpower the written production file,
3. they do not cause cinematic/heavy-black/glossy drift,
4. they do not change the approved layout sketch,
5. the page MD explicitly lists them as required.

Otherwise: **do not attach them to story-page generation.**

---

## Deferred Chapter 001 References

Do not generate solely for Chapter 001:

- Hyun-woo canonical
- separate apartment floor plan
- blackout visual-language atlas
- building service/electrical area
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical
- full neighbor canonical
- Hyejin canonical

---

## Chapter Production Authority

Before generating any Chapter 001 page, consult its exact `page-###-production.md` and:

`manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

Never attach every available WebP automatically.
