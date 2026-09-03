# Generation Attachment Map

This file answers one question for every generation step:

**Which approved WebP images must be attached to ChatGPT/image generation for the strongest continuity?**

All final reusable WebP authorities live in:

`manga/02-references/approved-webp/`

PNG review candidates are not reusable authorities.

---

## Absolute Rendering Rule

The approved Style A + Style B images control broad manga drawing language only.

They do **not** authorize:

- cinematic lighting
- poster/key-art polish
- large default solid-black masses
- noir treatment for ordinary scenes
- glossy webtoon rendering
- film-still composition
- photoreal/3D-derived rendering

The global visual target is a **visibly human-drawn black-and-white manga page** using organic linework, white paper, restrained screentone, hand hatching, and sparse spot blacks.

See:

- `manga/01-style/manga-style-lock.md`
- `manga/01-style/screentone-and-hatching-guide.md`

If a style reference contains a heavily rendered/dark region, extract only the useful line/anatomy/hatching language needed by the page. Do not automatically copy its darkness or cinematic drama.

---

## User-Supplied Page Sketch / Thumbnail Rule

If the user supplies or has already approved a page-specific sketch/thumbnail/layout image, attach it for the generation request.

For that generation, the supplied sketch is the **highest composition authority** and controls:

- panel geometry/proportions
- panel order
- framing/camera intent
- character blocking
- major object placement
- negative space
- balloon-placement intent
- rough manga-page rhythm

Do not redesign, beautify, cinematicize, or “improve” an approved page sketch.

The sketch controls composition only. Canonical character/environment references still control identity and reusable geometry.

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

Attach both to every Chapter 001 manga-page generation. They control **broad hand-drawn manga rendering language only**.

They never control story-character identity, reusable environment geometry, page-specific layout, or permission to increase cinematic polish/darkness.

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
5. a user-approved page sketch/thumbnail when one exists for that page

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
6. user-approved page sketch/thumbnail when one exists for that page

### Apartment/corridor/elevator page with visible Nari

Attach:

1. Style A
2. Style B
3. Nari canonical
4. Nari apartment atlas
5. previous approved page WebP when the scene continues
6. user-approved page sketch/thumbnail when one exists for that page

### Empty apartment page

Attach:

1. Style A
2. Style B
3. Nari apartment atlas
4. previous approved page WebP when required for exact Chair B state / camera continuity
5. user-approved page sketch/thumbnail when one exists for that page

Do not attach Nari canonical when Nari is not visible merely because she owns the apartment.

### Downstairs-neighbor-only page before the common-route scene

Attach Style A + Style B. The neighbor/interior are chapter-local and should be preserved across adjacent pages using the immediately previous approved page WebP rather than creating speculative canonicals.

Attach a user-approved page sketch/thumbnail when one exists for that page.

---

## Previous-Page Continuity

The previous approved manga page may be attached only for local seam continuity such as:

- pose/facing direction
- temporary object state
- chapter-local neighbor identity
- ongoing camera/environment crop
- Chair B exact position
- ongoing motion/action

Previous-page art never overrides canonical character/environment WebPs.

A user-approved page sketch may override previous-page art for current-page composition while preserving continuity facts.

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

Each `page-###-production.md` must explicitly list the exact subset of approved WebPs required for that page.

When a page-production file contains stricter anti-cinematic / human-drawn rules, those page-specific rules are binding.
