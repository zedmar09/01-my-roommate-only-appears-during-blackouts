# Chapter 001 — Pre-Generation Reference Audit

## Audit Result

**PASS — CORE TEXT BASELINES APPROVED.**

The Chapter 001 story direction, Nari baseline, apartment spatial baseline, neighbor relationship, workplace identity, and style-reference concept are now approved for reference preparation.

**Important generation gate:** the first image generation must be the original series manga style-reference image. Nari and environment WebPs remain blocked until that style image is visually approved.

## Story / Reveal Audit

**PASS.** Chapter 001 has a locked event order and reveal ceiling:

- Nari is verifiably at her publishing-company workplace while activity is heard from her apartment.
- The complaint comes from the resident **directly below Nari**.
- The neighbor complaint creates the first contradiction.
- Ordinary access/security logic does not resolve it.
- The second dining chair becomes the physical continuity marker.
- The reader alone receives the final chair movement.
- Hyun-woo is not shown, heard, named, silhouetted, or attached as a Chapter 001 reference.
- No reader-facing blackout explanation appears.

## Minimal Reference Scope Audit

### Required reusable references

1. series manga style reference
2. Yoon Nari canonical character package
3. Nari apartment environment package
4. Nari workplace environment package

### Environmental coverage

The Nari apartment master atlas should cover:

- apartment interior
- front-door relationship
- immediate corridor
- elevator/common route
- dining table and exact two-chair configuration
- second-chair known/reference position

Prefer one coherent apartment/building package rather than multiplying environment references.

### Conditional reference

- Koo Hyejin canonical — only after her rebuilt non-technical role/design is separately approved and only if Chapter 001 visibly uses her.

### Explicitly deferred for Chapter 001

- Hyun-woo canonical
- building service/electrical-area atlas
- blackout visual-language atlas
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical
- full neighbor character atlas unless the neighbor becomes recurring

## Resolved Decision 1 — Nari Chapter 001 Baseline

**APPROVED.**

- Korean woman, age 30
- editor at a mid-sized publishing company
- approximately 165 cm
- natural slim-average adult build
- mature but approachable adult face
- expressive eyes; slightly tired resting expression when overworked
- dark mid-back hair with restrained natural wave
- hair normally loose; simple low tie acceptable during concentrated work
- no permanent glasses
- practical publishing-office workwear: blouse/knit, cardigan/simple jacket, straight slacks, simple shoes
- relaxed home clothing: loose T-shirt/long-sleeve + lounge pants
- grounded, observant, dry humor, low-glamour everyday presentation
- no automatic carryover of retired Manhwa accessories/design

Semantic authority: `manga/02-references/characters/nari/canon.md`.

## Resolved Decision 2 — Nari Apartment Spatial Baseline

**APPROVED.**

- modest modern Seoul one-bedroom apartment
- approximately 40–45 m²
- ordinary working-adult rental, neither luxury nor horror-run-down
- short entry hall with readable sightline to living/dining
- compact bathroom near entry
- compact kitchen adjoining dining zone
- separate bedroom/private-room route
- main living area at exterior/window side
- home work/activity zone within living area
- small rectangular dining table
- exactly two matching chairs
- second chair is Chapter 001 continuity chair
- second chair known state: fully tucked at designated side, back parallel to table edge, legs aligned to clear floor/table geometry
- immediate corridor/elevator/common route merged into master atlas when possible

Semantic authority: `manga/02-references/environments/nari-apartment/canon.md`.

## Resolved Decision 3 — Neighbor Relationship

**APPROVED: directly below Nari.**

This gives Chapter 001 a straightforward physical sound path for footsteps and chair scraping without requiring special shared-wall acoustics.

Do not revert to an adjacent-unit interpretation unless story continuity is deliberately revised later.

## Resolved Decision 4 — Nari Workplace Identity

**APPROVED.**

Nari works as an editor at a mid-sized publishing company.

The workplace must support:

- normal editorial desk work
- manuscripts and printed proofs
- reference/bookshelves
- coworker desks
- small review/meeting space
- normal daytime activity
- quiet late-night deadline work

The Chapter 001 cold open uses the same publishing office; no separate late-night work location is needed.

Semantic authority: `manga/02-references/environments/nari-workplace/canon.md`.

## Resolved Decision 5 — Original Manga Style Reference

**TEXT SPEC APPROVED / IMAGE NOT YET GENERATED.**

Create one original black-and-white manga visual-language calibration image before any story-character/environment image.

It should establish:

- hand-drawn ink/sketch character rendering
- variable line weight
- screentone density
- hatching/cross-hatching behavior
- solid-black usage
- background-detail balance
- panel-border feeling
- simplified reaction rendering
- printed-manga texture

Use only generic original subjects. Do not copy a reference manga's characters, dialogue, logos, exact panels, or exact composition.

Generation authority: `manga/01-style/reference-style/series-manga-style-reference-generation-prompt.md`.

## Page Format Decision

Reference generation only needs the **portrait manga-page family** locked at this stage.

Exact production pixels, final page aspect ratio, safe margins, and reading direction remain page-production decisions and must be approved before `page-001-production.md` is compiled.

## Generation Order

1. Generate `series-manga-style-reference.webp`.
2. Review it. If rejected, do not proceed to story references.
3. After style approval, generate Nari canonical.
4. Then generate apartment master atlas and floor plan.
5. Then generate workplace master atlas.
6. Add Hyejin only after her rebuilt role/design is separately approved if Chapter 001 visibly uses her.

## Audit Gate

### READY NOW

- **series manga style-reference image generation**

### WAITING FOR STYLE WEBP APPROVAL

- Nari canonical image generation
- Nari apartment image generation
- Nari workplace image generation

The reference register should move each package from `TEXT APPROVED` → `VISUAL REVIEW` → `APPROVED` only after the corresponding visual is generated and reviewed.
