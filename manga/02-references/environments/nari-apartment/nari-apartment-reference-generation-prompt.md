# Nari Apartment — Manga Reference Generation Prompt

## Status

**TEXT APPROVED — READY FOR MASTER-ATLAS PNG GENERATION.**

Approved style authorities already exist.

## Exact WebP Attachments — Master Atlas

Attach exactly these approved WebPs:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`

Also consult:

- `manga/02-references/environments/nari-apartment/canon.md`
- `manga/01-style/manga-style-lock.md`

Do **not** attach `nari-canonical.webp` for the master environment atlas. The apartment reference must lock architecture/furniture without a character sheet biasing or populating the scene.

See `manga/02-references/generation-attachment-map.md` before generation.

## Output Format Workflow

### Generation A — Master Atlas

Generate review candidate as:

`nari-apartment-master-atlas.png`

After visual approval, the user manually converts that exact accepted PNG to:

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

The PNG is review-only. Do not ask the image generator to output WebP directly.

### Generation B — Floor Plan — Only If Needed

Do not generate the floor plan until the master atlas is visually approved and converted.

If a separate floor-plan image is needed, attach:

1. `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
2. `manga/02-references/approved-webp/series-manga-style-reference-b.webp`
3. `manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Generate review candidate as:

`nari-apartment-floor-plan.png`

After approval, manually convert it to:

`manga/02-references/approved-webp/nari-apartment-floor-plan.webp`

If the master atlas itself contains a clear, reliable floor plan, do not create a redundant separate floor-plan image.

---

## Generation A — Master Environment Atlas

```text
Create exactly ONE reusable BLACK-AND-WHITE MANGA ENVIRONMENT MASTER ATLAS for NARI'S APARTMENT from "My Roommate Only Appears During Blackouts".

OUTPUT FORMAT
Return/generate the first review candidate as PNG. The user will manually convert the exact approved PNG to WebP after visual review. Do not treat the PNG as final repository canon.

ATTACHED VISUAL AUTHORITIES
- Style Reference A controls broad finished-manga ink, architectural line character, hatching, solid-black and detail language.
- Style Reference B complements it with ordinary domestic interior, adult-life, quiet-space, restrained suspense and background-density language.
- The generic apartment shown inside Style B is NOT Nari's apartment and must NOT be copied as geometry, furniture layout or decoration.
- Nari apartment canon.md is the spatial authority.

This is a spatial production reference, NOT a manga story page. Do not show story events, hidden people, ghosts, silhouettes, or supernatural effects.

ENVIRONMENT IDENTITY — ABSOLUTE
- modest modern Seoul one-bedroom apartment
- approximately 40–45 m²
- ordinary working-adult rental
- comfortable and believable, NOT luxury, NOT run-down horror, NOT hotel, NOT futuristic, NOT studio apartment

LOCKED SPATIAL RELATIONSHIPS
- front door → short entry hall → readable sightline toward living/dining
- compact bathroom near entry side
- compact kitchen adjoining dining zone
- small rectangular dining table with EXACTLY TWO MATCHING CHAIRS
- main living area toward exterior-window side
- one separate bedroom/private room connected off inner living/hall route
- small home work/activity zone inside living area
- main window or small balcony-side opening on living-room exterior wall

DINING CHAIRS — CRITICAL
Chair A = Nari habitual seat.
Chair B = continuity chair.

Chair B known/reference state:
- fully tucked at its designated side of the table
- back parallel to table edge
- leg/floor/table geometry gives a visually obvious alignment reference
- same chair design, same designated side, same scale in every atlas view

Do NOT create extra dining chairs.

COMMON-AREA COVERAGE
Include compact reference views for:
- Nari front door exterior
- immediate corridor outside her unit
- nearby elevator/common circulation point
These are the morning-complaint route. Do not design the entire building.

NEIGHBOR RELATIONSHIP
The complaining neighbor is directly BELOW Nari, not adjacent. The atlas does not need the neighbor's full unit, but do not imply a shared-wall complaint configuration.

REQUIRED ATLAS VIEWS
Show enough consistent views to reconstruct the apartment from different manga camera angles:
1. entry looking toward living/dining
2. living area looking back toward dining/kitchen/entry
3. dining/kitchen relationship with both chairs clearly visible
4. living-to-bedroom/private-route view
5. bedroom/private-route looking toward living if spatially useful
6. main window/exterior-side view
7. Nari home work/activity-zone relationship
8. front-door exterior + immediate corridor
9. elevator/common-route view
10. close detail of dining table + Chair A + Chair B in their normal positions, with Chair B alignment especially clear
11. OPTIONAL: one compact top-down or axonometric layout inset only if it can remain fully consistent and legible without sacrificing the main views

VISUAL CONTINUITY
- keep all doors/windows/fixed furniture in the SAME positions across views
- keep scale believable
- no mirrored/reversed room insets unless explicitly presented as a reverse camera from the same geometry
- no impossible door/window changes
- no random furniture redesign between views

MANGA STYLE
Follow both attached approved series style references:
- black-and-white ink linework
- finished published-manga drawing, not rough construction sketch
- human-drawn architectural line character
- screentone/hatching only where useful
- clean readable perspective
- ordinary material textures without glossy CGI rendering
- no cinematic bloom/light shafts

LIVED-IN LEVEL
Nari has lived here roughly two weeks:
- normal practical personal items may appear
- light believable small clutter is acceptable
- do not fill the apartment with moving boxes unless composition needs one or two ordinary traces of recent occupancy
- no suspicious clues, occult props, horror decoration, logos, readable documents, or invented story evidence

TEXT
Prefer ZERO readable labels/text. No room labels, fake signs, watermarks, UI, dialogue, or metadata.

AUTOMATIC REJECT IF
- the generic apartment from Style B is copied as the actual layout
- chair count is not exactly two
- Chair B changes designated side/design
- layout contradicts itself across views
- bedroom, bathroom, kitchen, windows, or front door move between views
- apartment becomes luxury, giant, studio, horror ruin, hotel, cyberpunk, or futuristic
- common corridor/elevator looks like a luxury hotel
- hidden human/silhouette/ghost appears
- color/glossy/photoreal/3D/painterly/cinematic rendering appears

FINAL GOAL
A production-safe black-and-white manga PNG review candidate for the apartment atlas. After approval and manual conversion to WebP, it must preserve Nari's apartment geometry for hundreds of pages and make the Chapter 001 dining-chair movement provable through stable spatial continuity.
```

---

## Generation B — Floor Plan

Generate separately only if the approved master atlas cannot itself provide a legible reliable floor plan.

```text
Create exactly ONE clean BLACK-AND-WHITE TOP-DOWN FLOOR-PLAN REFERENCE for the SAME approved Nari apartment geometry.

OUTPUT FORMAT
Return/generate the first review candidate as PNG. The user will manually convert the exact approved PNG to WebP after visual review.

ATTACHED VISUAL AUTHORITIES
- Style Reference A and B control only rendering language.
- The approved Nari apartment master atlas is the visual spatial authority.
- Nari apartment canon.md is the semantic spatial authority.

REQUIRED
- portrait/vertical sheet with one primary top-down plan
- approximately 40–45 m² one-bedroom layout
- front door and short entry hall
- compact bathroom near entry
- compact kitchen adjoining dining
- rectangular dining table + exactly two matching chairs
- living area at exterior/window side
- separate bedroom/private room
- home work/activity zone
- window / small balcony-side opening
- clear door swings/openings where visually useful
- Chair A and Chair B both visible in their normal positions
- Chair B known/reference alignment visually obvious

Do not redesign anything from the approved master atlas.

Use clean manga/architectural ink lines with minimal tone. Prefer no readable text labels; spatial interpretation comes from the canon MD.

AUTOMATIC REJECT IF
- plan contradicts master atlas
- chair count or designated continuity-chair side changes
- geometry is impossible
- extra rooms appear
- unit becomes luxury/oversized
- color, 3D render, painterly, or photoreal treatment appears
```

## Approval Gate

Master atlas must pass visual/spatial audit first. After approval, manually convert it to:

`manga/02-references/approved-webp/nari-apartment-master-atlas.webp`

Only then decide whether a separate floor plan is still necessary.
