# Nari Apartment — Manga Reference Generation Prompt

## Status

**TEXT APPROVED — WAITING FOR SERIES STYLE WEBP APPROVAL.**

Do not generate apartment candidates until this final style authority exists and is approved:

`manga/01-style/reference-style/series-manga-style-reference.webp`

## Output Format Workflow

### Master Atlas

ChatGPT/image generation first produces:

`nari-apartment-master-atlas.png`

After visual approval, the user manually converts that exact PNG to the final repository authority:

`manga/02-references/environments/nari-apartment/nari-apartment-master-atlas.webp`

### Floor Plan

If a separate floor-plan image is needed, ChatGPT/image generation first produces:

`nari-apartment-floor-plan.png`

After visual approval, the user manually converts that exact PNG to:

`manga/02-references/environments/nari-apartment/nari-apartment-floor-plan.webp`

The PNGs are review candidates only. Do not ask the image generator to output WebP directly.

## Required Attachments / Authorities

- `manga/02-references/environments/nari-apartment/canon.md`
- `manga/01-style/manga-style-lock.md`
- approved `manga/01-style/reference-style/series-manga-style-reference.webp`

## Generation A — Master Environment Atlas

```text
Create exactly ONE reusable BLACK-AND-WHITE MANGA ENVIRONMENT MASTER ATLAS for NARI'S APARTMENT from "My Roommate Only Appears During Blackouts".

OUTPUT FORMAT
Return/generate the first review candidate as PNG. The user will manually convert the exact approved PNG to WebP after visual review. Do not treat the PNG as final repository canon.

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

VISUAL CONTINUITY
- keep all doors/windows/fixed furniture in the SAME positions across views
- keep scale believable
- no mirrored/reversed room insets unless explicitly presented as a reverse camera from the same geometry
- no impossible door/window changes
- no random furniture redesign between views

MANGA STYLE
Follow the attached approved series style reference:
- black-and-white ink linework
- human-drawn architectural lines
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

## Generation B — Floor Plan

Generate separately only if the master atlas cannot carry a legible floor plan itself. Generate after the master-atlas PNG candidate is acceptable enough to match.

```text
Create exactly ONE clean BLACK-AND-WHITE TOP-DOWN FLOOR-PLAN REFERENCE for the SAME approved Nari apartment geometry.

OUTPUT FORMAT
Return/generate the first review candidate as PNG. The user will manually convert the exact approved PNG to WebP after visual review. Do not treat the PNG as final repository canon.

Use the attached Nari apartment canon and the accepted master-atlas candidate as authority.

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

Do not redesign anything from the master atlas.

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

Each generated PNG enters `VISUAL REVIEW` first. Approve only when the atlas/floor-plan geometry agrees with `canon.md` and with each other. After approval, manually convert each exact accepted PNG to its matching final WebP path and commit the WebP before marking the package `APPROVED`.
