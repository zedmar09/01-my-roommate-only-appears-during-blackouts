# Chapter 001 — Pre-Generation Reference Audit

## Audit Result

**PASS — CORE TEXT BASELINES APPROVED.**

The Chapter 001 story direction, Nari baseline, apartment spatial baseline, neighbor relationship, workplace identity, and style-reference concept are now approved for reference preparation.

**Important generation gate:** the first generated image must be the original series manga style-reference **PNG candidate**. Nari and environment PNG candidates remain blocked until that style candidate is approved, manually converted to WebP, committed, and marked `APPROVED`.

## Image Format Workflow — Locked

All reference image generation follows:

1. ChatGPT/image generator creates `.png`.
2. PNG enters visual review.
3. If approved, the user manually converts that exact PNG to `.webp`.
4. Only the WebP becomes final repository visual authority.

Never treat a generated PNG as final canon, and do not ask the image generator to output WebP directly.

See `manga/02-references/image-format-workflow.md`.

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

**TEXT SPEC APPROVED / PNG NOT YET GENERATED.**

Create one original black-and-white manga visual-language calibration PNG before any story-character/environment image.

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

1. Generate `series-manga-style-reference.png`.
2. Review the PNG. If rejected, do not proceed.
3. If approved, manually convert that exact PNG to `series-manga-style-reference.webp`, commit it, and mark the style package `APPROVED`.
4. Generate `nari-canonical.png`.
5. Generate `nari-apartment-master-atlas.png`; generate a separate `nari-apartment-floor-plan.png` only if needed.
6. Generate `nari-workplace-master-atlas.png`.
7. For each accepted reference PNG, manually convert the exact approved candidate to its final WebP before marking the package `APPROVED`.
8. Add Hyejin only after her rebuilt role/design is separately approved if Chapter 001 visibly uses her.

## Audit Gate

### READY NOW

- **series manga style-reference PNG generation**

### WAITING FOR FINAL STYLE WEBP APPROVAL

- Nari PNG candidate generation
- Nari apartment PNG candidate generation
- Nari workplace PNG candidate generation

The reference register moves each package from `TEXT APPROVED` → `VISUAL REVIEW` when the PNG candidate exists → `APPROVED` only after the approved PNG has been manually converted and the final WebP exists in the repository.
