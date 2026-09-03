# Generation Attachment Map

This file answers one question for every reference-generation prompt:

**Which approved WebP images must be attached to ChatGPT/image generation for the strongest continuity?**

All final WebP authorities live in:

`manga/02-references/approved-webp/`

PNG review candidates are not listed as reusable authorities.

---

## Series Style Reference Generation

Status: **COMPLETED / APPROVED PAIR EXISTS**

Approved style authorities:

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Do not generate another Chapter 001 style reference unless the current pair is deliberately retired.

---

## Yoon Nari Canonical

Prompt:

`manga/02-references/characters/nari/nari-reference-generation-prompt.md`

Status: **COMPLETED / APPROVED**

Required WebP attachments for any future Nari regeneration:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Identity authority remains:

`manga/02-references/characters/nari/canon.md`

Approved final visual:

`manga/02-references/approved-webp/nari-canonical.webp`

Do not use the generic people in Style A/B as Nari identity authority.

---

## Nari Apartment — Master Atlas

Prompt:

`manga/02-references/environments/nari-apartment/nari-apartment-reference-generation-prompt.md`

Status: **READY TO GENERATE PNG**

Required WebP attachments:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Do **not** attach `nari-canonical.webp` for the environment master atlas. The atlas should lock architecture and furniture without allowing a character reference to bias or populate the scene.

Semantic authority:

`manga/02-references/environments/nari-apartment/canon.md`

Generate review candidate:

`nari-apartment-master-atlas.png`

After approval, manually convert and centralize as:

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

---

## Nari Apartment — Floor Plan

Use the floor-plan section of:

`manga/02-references/environments/nari-apartment/nari-apartment-reference-generation-prompt.md`

Status: **WAIT UNTIL MASTER ATLAS IS APPROVED**

Required WebP attachments:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`
3. `manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

The master atlas is the spatial visual authority. Do not redesign the apartment while creating the floor plan.

Generate review candidate only if a separate floor-plan image is actually needed:

`nari-apartment-floor-plan.png`

After approval, manually convert and centralize as:

`manga/02-references/approved-webp/nari-apartment-floor-plan.webp`

---

## Nari Workplace — Master Atlas

Prompt:

`manga/02-references/environments/nari-workplace/nari-workplace-reference-generation-prompt.md`

Status: **READY AFTER / ALONGSIDE APARTMENT REFERENCE WORK**

Required WebP attachments:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Do **not** attach `nari-canonical.webp` to the environment atlas unless a later revised prompt explicitly requires Nari to appear. Keep the workplace atlas focused on stable geometry and editorial-office identity.

Semantic authority:

`manga/02-references/environments/nari-workplace/canon.md`

Generate review candidate:

`nari-workplace-master-atlas.png`

After approval, manually convert and centralize as:

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

---

## Future Hyejin Canonical — Conditional

Do not generate yet.

If Chapter 001 later confirms she visibly appears and her rebuilt role/design is approved, her character-generation prompt should normally attach:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp` — optional comparison authority only when the prompt explicitly uses it to preserve distinct identity/relative adult scale

Nari must never be copied into Hyejin's identity.

---

## Future Manga Page Rule

A `page-###-production.md` must explicitly list only the WebPs needed by that page. Typical attachment order:

1. Style A
2. Style B
3. required character canonical(s)
4. required environment atlas/floor plan
5. required object/effect authority if any
6. immediately previous approved page WebP when local seam continuity is needed

Never attach every available WebP automatically. More attachments are useful only when they directly control something visible on that page.
