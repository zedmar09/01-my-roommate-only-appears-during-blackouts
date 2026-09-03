# Generation Attachment Map

This file answers one question for every generation step:

**Which approved WebP images must be attached to ChatGPT/image generation for the strongest continuity?**

All final reusable WebP authorities live in:

`manga/02-references/approved-webp/`

PNG review candidates are not reusable authorities.

---

## Approved Chapter 001 Reference Pool

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`
3. `manga/02-references/approved-webp/nari-canonical.webp`
4. `manga/02-references/approved-webp/nari-apartment-master-atlas.webp`
5. `manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

The apartment master atlas already provides sufficient floor-plan/spatial authority for Chapter 001. No separate apartment floor-plan WebP is required.

---

## Series Style References

Status: **COMPLETED / APPROVED PAIR**

- Style A: `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- Style B: `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Attach both to every Chapter 001 manga-page generation. They control rendering language only.

---

## Yoon Nari Canonical

Status: **COMPLETED / APPROVED**

Semantic authority:

`manga/02-references/characters/nari/canon.md`

Approved visual:

`manga/02-references/approved-webp/nari-canonical.webp`

Whenever Nari is visible on a manga page, attach:

1. Style A
2. Style B
3. Nari canonical
4. the page's required environment atlas, when a canonical environment is visible

Nari canonical overrides any generic person identity shown in Style A/B.

---

## Nari Apartment Master Atlas

Status: **COMPLETED / APPROVED**

Semantic authority:

`manga/02-references/environments/nari-apartment/canon.md`

Approved visual:

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

The atlas controls apartment interior geometry plus the immediate front-door/corridor/elevator route required by Chapter 001.

Use on Pages 006–010 and 019–036 whenever the apartment/common-route environment is visible.

Do not generate a separate floor plan for Chapter 001.

---

## Nari Workplace Master Atlas

Status: **COMPLETED / APPROVED**

Semantic authority:

`manga/02-references/environments/nari-workplace/canon.md`

Approved visual:

`manga/02-references/approved-webp/nari-workplace-master-atlas.webp`

Use on Pages 001, 004–005, and 011–018 whenever the publishing-office environment is visible.

---

## Chapter 001 Page Attachment Rules

### Workplace page with visible Nari

Attach:

1. Style A
2. Style B
3. Nari canonical
4. Nari workplace atlas
5. previous approved page WebP only when local seam continuity materially helps

### Apartment/corridor/elevator page with visible Nari

Attach:

1. Style A
2. Style B
3. Nari canonical
4. Nari apartment atlas
5. previous approved page WebP when the scene continues

### Empty apartment page

Attach:

1. Style A
2. Style B
3. Nari apartment atlas
4. previous approved page WebP when required for exact Chair B state / camera continuity

Do not attach Nari canonical when Nari is not visible merely because she owns the apartment.

### Downstairs-neighbor-only page before the common-route scene

Attach Style A + Style B. The neighbor/interior are chapter-local and should be preserved across adjacent pages using the immediately previous approved page WebP rather than creating speculative canonicals.

---

## Previous-Page Continuity

The previous approved manga page may be attached only for local seam continuity such as:

- pose/facing direction
- temporary object state
- chapter-local neighbor identity
- ongoing camera/environment crop
- Chair B exact position
- ongoing motion/action

Previous-page art never overrides the canonical character/environment WebPs.

---

## Conditional / Deferred

### Hyejin

No visible Hyejin canonical is required for Chapter 001. Keep any optional friend/phone presence offscreen. Do not generate Hyejin yet.

### Hyun-woo

Do not generate or attach for Chapter 001. He is not visible, voiced, silhouetted, or identified.

### Other deferred references

Do not generate solely for Chapter 001:

- separate apartment floor plan
- blackout visual-language atlas
- building service/electrical area
- separate dining-chair object
- separate smartphone
- separate smart lock
- full neighbor canonical

---

## Chapter Production Authority

Before generating any Chapter 001 page, consult:

`manga/04-production/arc-01/chapter-001/chapter-001-pages-generation-guide.md`

Each `page-###-production.md` must explicitly list the exact subset of approved WebPs required for that page. Never attach every available WebP automatically.