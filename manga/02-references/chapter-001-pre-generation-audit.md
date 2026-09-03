# Chapter 001 — Pre-Generation Reference Audit

## Audit Result

**HOLD — DO NOT GENERATE THE MINIMAL REFERENCE SET YET.**

The Chapter 001 story direction is approved and stable enough to define reference scope, but several visual/continuity authorities are still unresolved. Generating character/environment canonicals before these items are locked risks wasting image generations or creating references that immediately become obsolete.

## Story / Reveal Audit

**PASS.** Chapter 001 has a locked event order and reveal ceiling:

- Nari is verifiably away while activity is heard from her apartment.
- The neighbor complaint creates the first contradiction.
- Ordinary access/security logic does not resolve it.
- The dining chair becomes the physical continuity marker.
- The reader alone receives the final chair movement.
- Hyun-woo is not shown, heard, named, silhouetted, or attached as a Chapter 001 reference.
- No reader-facing blackout explanation appears.

The current story scope is safe for reference planning.

## Minimal Reference Scope Audit

### Required reusable references

1. series manga style reference
2. Yoon Nari canonical character package
3. Nari apartment environment package
4. Nari workplace environment package

### Required environmental coverage, preferably merged rather than multiplied

- Nari apartment interior
- apartment front-door / immediate corridor relationship
- elevator/common route used by the morning complaint
- dining chair exact design/count/reference position

Prefer covering the immediate common route inside the apartment/building master environment atlas when readability remains strong. Create a separate common-area package only if one atlas becomes too crowded or spatially ambiguous.

### Conditional references

- Koo Hyejin canonical — only if she is formally retained as the visible recurring coworker/friend.
- neighbor canonical — not required as a full reusable package for Chapter 001; preserve short-scene identity through sequential approved-page continuity unless the neighbor becomes recurring.

### Explicitly not required for Chapter 001

- Hyun-woo canonical
- building service/electrical-area atlas
- blackout visual-language atlas
- separate dining-chair object canonical
- separate smartphone canonical
- separate smart-lock canonical unless later story mechanics make the exact hardware plot-critical

## Blocking Decisions Before Reference Image Generation

### BLOCKER 1 — Nari final Chapter 001 baseline

Must be locked before `nari-canonical.webp` generation:

- exact age or approved age range
- final occupation / workplace function
- body-height/build identity
- face/hair design
- glasses/no-glasses decision
- primary work outfit
- primary home outfit or whether one canonical outfit can cover the chapter
- permanent identifiers/accessories
- expression baseline

Do not inherit the retired Manhwa design automatically.

### BLOCKER 2 — Nari apartment spatial canon

Must be locked before apartment atlas/floor-plan generation:

- apartment class / approximate size
- room count
- entry-door position and opening relationship
- living/dining/kitchen geometry
- work area
- bedroom/private-area route used at Chapter 001 end
- window positions
- major fixed furniture
- dining table and exact chair count/design
- one exact normal/known chair position that can be reproduced page to page
- immediate corridor/elevator/common-route coverage strategy

### BLOCKER 3 — Neighbor spatial relationship

Choose one and keep it permanent:

- **unit directly below Nari**; or
- adjacent unit.

Recommendation for Chapter 001 continuity: **directly below**, because footsteps and chair scraping have a simple physical sound path and do not require inventing a shared-wall explanation.

Do not encode either option into an environment reference until approved.

### BLOCKER 4 — Nari workplace identity

The chapter already uses the workplace in the cold open and daytime scenes, so the final occupation must be known before generating the workplace atlas.

Lock:

- Nari's occupation
- workplace type
- recurring desk/work zone
- whether late-night work in the opening naturally fits that job
- minimum background coworkers/equipment required

The opening should use the same workplace rather than introducing a separate one-off late-night location unless the story is intentionally changed.

### BLOCKER 5 — Original manga style-reference generation package

The textual style lock is usable, but no approved style-reference WebP currently exists.

Before generating Nari or environments, create and approve one **original** style-reference image derived only from the broad black-and-white hand-drawn manga language:

- ink/sketch character rendering
- variable line weight
- screentone density
- hatching/cross-hatching behavior
- solid-black usage
- background-detail balance
- panel-border feeling
- printed-manga texture

Do not copy the attached reference's characters, dialogue, logos, exact panels, or exact composition.

The approved style reference becomes the visual style authority for later reference generations.

## Non-Blocking Decisions That May Wait Until Page Production

These do not need to delay the first reference packages:

- final Chapter 001 title
- exact 36-page count versus a small refinement
- final dialogue wording
- exact per-page panel geometry
- exact page pixel dimensions / aspect ratio
- final reading direction
- exact late-night clock times
- exact smart-lock app UI

However, page canvas dimensions and reading direction must be locked before `page-001-production.md` is compiled.

## Continuity Risk Found During Audit

The series-level world-rule document still says several blackout mechanics must be defined before Chapter 1 locks, while Chapter 1 is now story-locked without showing the mechanic directly. The correct gate is before the first page that visibly depends on direct manifestation/power-restoration mechanics. Chapter 001 may keep its off-panel creator-only brief supplied-power interruption without explaining or visually depicting the rule.

## Required Order From Here

**Do not start with character image generation.**

First lock the five blocking decisions above. Then prepare the semantic Markdown + synchronized generation prompt for each reference package. Generate the original style-reference image first. Only after that style image is approved should Nari and environment reference images be generated.

## Audit Gate

Reference image generation becomes **READY** only when:

- Nari baseline = approved
- apartment spatial canon = approved
- neighbor relationship = approved
- workplace/occupation = approved
- original manga style-reference prompt/spec = approved
- reference register contains the planned packages

Until then, status remains **HOLD**.
