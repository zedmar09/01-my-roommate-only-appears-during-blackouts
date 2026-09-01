# Chapter 1 Manhwa Generation Checklist

Status: **PREPRODUCTION SCRIPT / CONTINUITY / PROMPT / REFERENCE GATE PASS — READY FOR SEQUENTIAL STRIP 001 PRODUCTION — NOT PRODUCTION COMPLETE**

Fresh `manhwa-2d-production-auditor` verification confirms:
- the 146-beat / 32-strip story package remains deterministic and coherent
- dialogue/narration/thought/device/note ownership remains locked
- SFX physical logic remains coherent at prompt level
- movement, object routes, power states, and seam handoffs remain coherent at prompt level
- approved Chapter 1 character/environment/object WebP authorities are present
- all 32 strip prompts now reference the exact current WebP filenames/paths

Rendered Strip 001–032 artwork and the final stitched chapter still do not exist, so actual strip-level visual/style/lettering/dead-space/seam approval remains pending.

## Scope

- one continuous vertical Chapter 1
- 146 internal read beats
- 32 technical strips
- historical P001–P018 labels are story shorthand only
- no active `Comics/` dependency

## Binding Global Gates — Absolute

Every strip inherits:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`

A strip may be stricter but may never loosen these rules.

## Repository Image Format Rule

Reference-image prompts may continue to generate PNG first as a local intermediate. After visual approval, manually convert that accepted PNG to WebP and store/use the exact WebP in GitHub.

Production-strip Markdown attaches the committed WebP, not the temporary/deleted PNG.

## Required Chapter 1 Character WebPs — PRESENT / APPROVED

- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

Nari uses the current long dark-plum mid-back design, loose by default. Retired short-hair Nari is invalid.

Seungjae is exactly 30, the same age as Nari, and must read as her same-generation peer.

## Required Unit 2407 WebPs — PRESENT / APPROVED

- `Manhwa/Environment-References/Unit-2407/unit-2407-floor-plan-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-entry-living-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-living-to-kitchen-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-kitchen-to-living-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-hallway-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-desk-zone-detail-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-fridge-cabinet-zone-detail-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-lighting-state-sheet-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-room-angle-atlas-reference.webp` when an intended camera angle is not sufficiently covered by the primary views

The full reusable Unit 2407 pack also contains Bedroom A, Bedroom B, and bathroom WebPs for later scenes/chapters.

## Required Building Shared-Area WebPs — PRESENT / APPROVED

- `Manhwa/Environment-References/Building-Shared-Areas/rainy-building-entrance-reference.webp`
- `Manhwa/Environment-References/Building-Shared-Areas/building-lobby-elevator-reference.webp`

`building-shared-areas-bible.webp` is not a required Chapter 1 strip attachment.

## Required Object WebPs — PRESENT / APPROVED

- `Manhwa/Object-References/smart-speaker-canonical-reference.webp`
- `Manhwa/Object-References/tv-canonical-reference.webp`
- `Manhwa/Object-References/refrigerator-canonical-reference.webp`
- `Manhwa/Object-References/electrical-operation-guide-canonical-reference.webp`
- `Manhwa/Object-References/brass-backup-key-canonical-reference.webp`

If an exact required WebP becomes missing, stale, wrong-path, or rejected: **STOP. Do not improvise a substitute.**

## Strip Prompt Completeness Gate — PASS

Every `strip-001` through `strip-032` now explicitly lists:
- exact visible-character WebP path(s)
- exact reusable environment WebP path(s)
- exact reusable object WebP path(s) when needed
- previous approved rendered strip for 002–032
- current prompt

The active strip package no longer relies on obsolete PNG paths or vague attachment labels.

## Strict Flat 2D Human-Drawn Style Gate — Absolute

Actual rendered images must be visually inspected for:
- strict flat 2D human-drawn Korean manhwa/webtoon appearance
- clean intentional line art
- flat colors
- restrained simple hard-edged cel shading only
- matte skin, hair, fabrics, architecture, furniture, appliances, screens, glass, floors, and props
- stable canonical anatomy/proportions and natural hands
- mobile-readable silhouettes/composition

Reject photoreal/semi-photoreal, 3D/CGI/game-render, glossy/plastic/wet, painterly, airbrushed, beauty-ad shine, cinematic grading, depth-of-field blur, bloom, lens flare, gratuitous rim light, mirror-like reflections, excessive specular highlights, or AI-polished over-rendering.

## Script / Ownership Gate

For every strip:
- exact locked wording only
- exact speaker/source ownership
- exact SFX/device/note text
- device text remains on correct device
- narration/thought never becomes dialogue
- no invented filler reader-facing text/SFX

## SFX Physical-Logic Gate

For every scripted sound verify:
`PHYSICAL SOURCE → ACTION → SOUND → TIMING → VISUAL PLACEMENT → STATE CHANGE → NEXT-BEAT CONSEQUENCE`.

## Critical Real-Scenario Continuity Locks

- same guide + same brass key arrive together; guide stays counter; key counter → Nari hand → entry tray
- guide title `UNIT 2407 / ELECTRICAL OPERATION GUIDE`; Section 16 → 18; no normal Section 17; south-wall note remains physical handwriting
- exactly one brass mechanical backup key; no fob/card/duplicate
- one chopsticks pair in Strip 005 falls once and remains through Strip 006 V26
- speaker counter plugged → unplugged → hidden in storage stockpot → later voice-only while still unplugged
- Nari visibly walks to TV outlet before unplugging it
- guarded fruit knife and practical sheathed blackout knife remain distinct
- six emergency noodle packets before Hyun-woo eats; five unopened afterward
- Strips 012–013: one Nari shoulder bag; tablet remains inside
- Seungjae: one phone/watch/earbuds/umbrella; age exactly 30
- Strip 014 onward: Nari long dark-plum hair loose; yellow scrunchie on wrist
- Strip 017→018: same mask temporarily clears mouth for eating, then chopsticks rest and same mask visibly reseats before `TCHK`
- practical knife sheath remains desk after draw; knife fixed floor spot until Strip 028 pickup
- Strip 023 exact order: short reach → `PFF` → `KIIIIII` → knife slip/fall → `CLANG` → only then wrist catch
- city power returns before Unit 2407; Hyun-woo remains physical until Unit itself powers on
- power-return beat shows no visible disappearance process
- post-blackout phone route: desk → pickup → entry/security/voicemail → kitchen counter
- Nari uses the other untouched dining chair in Strips 029–032
- A5 notebook physically desk → dining table
- final TV remains visibly unplugged and Unit 2407 remains powered

## Canonical Reference Priority

1. current user instruction
2. current strip/chapter story script
3. approved character WebP
4. approved environment WebP
5. approved object WebP
6. previous approved rendered strip temporary state

## Black Read-Slice / No-Dead-Space Gate

- small black gutter between distinct vertical slices
- diagonal/slanted black divider between distinct side-by-side camera slices
- no face/text/balloon/prop/background crosses divider
- no giant filler bands
- no visible black technical bar at A/E continuation seams
- lower 20–25% of each rendered strip must serve story/composition/seam purpose

## Current Fresh-Audit Result

- **Text/script/causality:** PASS
- **Dialogue/source ownership:** PASS
- **SFX script/source/action logic:** PASS at prompt level
- **Real-life movement/body mechanics:** PASS at prompt level
- **Spatial/object/character state continuity:** PASS at prompt level
- **Panel/strip planned continuity:** PASS at prompt level
- **Character/environment/object visual authority presence:** PASS
- **Exact Markdown visual reference paths:** PASS
- **Strict flat 2D instruction authority:** PASS; actual rendered pixels await generation
- **Rendered strip visual audit:** PENDING — Strip 001–032 artwork not yet present
- **Seam/stitch/dead-space/mobile-lettering visual audit:** PENDING — requires rendered/stitched artwork

### Current Gate Counts

- **BLOCKER: 0 pre-strip reference/script blockers**
- **MAJOR: 0 unresolved deterministic story/prompt issues**
- **MINOR requiring correction: 0 at pre-strip prompt/reference level**
- **WARNING requiring explanation: 0**

**PREPRODUCTION STATUS: REFERENCE GATE PASS — READY FOR SEQUENTIAL STRIP 001 PRODUCTION**

**FINAL STATUS: NOT PRODUCTION COMPLETE — RENDERED STRIP PRODUCTION / VISUAL QA / STITCHED FINAL AUDIT STILL REQUIRED**
