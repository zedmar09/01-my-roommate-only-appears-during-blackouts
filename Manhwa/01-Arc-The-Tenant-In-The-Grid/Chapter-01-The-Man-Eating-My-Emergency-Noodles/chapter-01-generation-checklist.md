# Chapter 1 Manhwa Generation Checklist

Status: **PREPRODUCTION SCRIPT / CONTINUITY / PROMPT AUDIT PASS — APPROVED CHARACTER / ENVIRONMENT / OBJECT WEBP AUTHORITIES PRESENT — REFERENCE-PATH MIGRATION REQUIRED BEFORE STRIP 001 — NOT PRODUCTION COMPLETE**

Fresh `manhwa-2d-production-auditor` verification confirms the deterministic story/script/dialogue/SFX/movement/state routes remain locked across the current 146-beat plan and 32 strip prompts. The reusable visual authorities required by Chapter 1 now exist as approved WebPs. The remaining pre-strip task is to ensure every active Markdown attachment reference resolves to the exact current WebP filename.

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

Production-strip Markdown must attach the committed WebP, not the temporary/deleted PNG.

## Required Visual Authorities — PRESENT

Before Strip 001 generation, the current strip package must resolve all exact required WebP paths below.

### Current Chapter 1 Character Cards — PRESENT

- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

Nari's active authority uses long dark-plum hair at approximately mid-back length, loose by default. The retired short-hair design is not valid production authority.

Seungjae is exactly 30, the same age as Nari, and must read as her same-generation peer.

### Required Unit 2407 Environment WebPs — PRESENT

Chapter 1 primary/optional reusable environment authorities:
- `Manhwa/Environment-References/Unit-2407/unit-2407-floor-plan-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-entry-living-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-living-to-kitchen-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-kitchen-to-living-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-hallway-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-desk-zone-detail-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-fridge-cabinet-zone-detail-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-lighting-state-sheet-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-room-angle-atlas-reference.webp` when an intended camera angle is not sufficiently covered by the listed primary views

The full Unit 2407 pack also contains approved Bedroom A, Bedroom B, and bathroom WebPs for later scenes/chapters. They are not required by the current Chapter 1 strip attachment map unless a future correction introduces those spaces.

### Required Building Shared-Area WebPs — PRESENT

- `Manhwa/Environment-References/Building-Shared-Areas/rainy-building-entrance-reference.webp`
- `Manhwa/Environment-References/Building-Shared-Areas/building-lobby-elevator-reference.webp`

`building-shared-areas-bible.webp` is not a required Chapter 1 strip attachment. The two files above are the active visual authorities for Strips 012–013.

### Required Object WebPs — PRESENT

- `Manhwa/Object-References/smart-speaker-canonical-reference.webp`
- `Manhwa/Object-References/tv-canonical-reference.webp`
- `Manhwa/Object-References/refrigerator-canonical-reference.webp`
- `Manhwa/Object-References/electrical-operation-guide-canonical-reference.webp`
- `Manhwa/Object-References/brass-backup-key-canonical-reference.webp`

If an exact required WebP is missing, stale, wrong-path, or later rejected: **STOP. Do not improvise a substitute.** A Markdown reference prompt is not the visual authority.

## Strip Prompt Completeness Gate — Absolute

Every one of `strip-001` through `strip-032` must explicitly list inside its own Markdown file:
- exact visible-character WebP path(s)
- exact reusable environment WebP path(s)
- exact reusable object WebP path(s) when needed
- previous approved rendered strip for 002–032
- current prompt

Reject vague labels such as `Nari canonical` or obsolete `.png`/`*-canonical` filenames in an attachment block.

## Strict Flat 2D Human-Drawn Style Gate — Absolute

Actual rendered images must be visually inspected for:
- strict flat 2D human-drawn Korean manhwa/webtoon appearance
- clean intentional line art
- flat colors
- restrained simple hard-edged cel shading only
- matte skin, hair, fabrics, architecture, furniture, appliances, screens, glass, floors, and props
- stable canonical anatomy/proportions and natural hands
- mobile-readable silhouettes/composition

Reject photoreal/semi-photoreal, 3D/CGI/game-render, glossy/plastic/wet, painterly, airbrushed, beauty-ad shine, heavy gradients, cinematic grading, depth-of-field blur, bloom, lens flare, gratuitous rim light, mirror-like reflections, excessive specular highlights, or AI-polished over-rendering.

Blackout/candle/rain/device effects remain controlled flat shapes/contained accents. Do not propagate style drift from a previous strip.

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

Reject unclear source, premature/late sound, impossible action, filler SFX, or a sound used to hide a missing movement/state transition.

## Real-Scenario Movement / Object Gate

Verify every character begins where the previous strip physically left them unless a legal time/location cut occurs.
Verify every carried object has a visible/explicit route; nothing appears/disappears from hands without placement/pickup.
Verify recurring prop count/state/location is stable.

Specific Chapter 1 locks:
- Mrs. Na: SAME electrical-operation guide + SAME brass backup key arrive together; guide remains kitchen counter; key physically counter → Nari hand → entry tray
- guide: exact title `UNIT 2407 / ELECTRICAL OPERATION GUIDE`; same binder body; `SECTION 16` physically jumps to `SECTION 18`; no normal visible Section 17; south-wall diagram handwriting stays physical paper
- brass key: exactly one mechanical brass key; stable bow/head + blade/notch identity; never keycard/fob; never duplicates
- Strip 005→006 chopsticks: one pair established in Nari's hand before flicker, falls once, remains same kitchen-floor spot through Strip 006 V26; may be absent only after explicit later time cut
- speaker: kitchen counter plugged → unplugged → remains counter → hidden in storage stockpot/lower cabinet → later voice-only while still unplugged
- Strip 006 TV route: Nari established in open-plan area, then visibly walks to TV/outlet before unplugging; no invented bathroom/rinsing/cleanup action
- guarded fruit knife and practical sheathed blackout knife are TWO distinct objects
- six emergency noodle packets before Hyun-woo eats; five unopened after spicy-seafood packet is used
- Strips 012–013: Nari has exactly ONE shoulder bag; tablet stays physically inside; opening may be parted/angled for private glance but tablet never leaves bag
- Seungjae: one phone, one smartwatch, one pair earbuds, one umbrella
- Strip 014 onward: Nari's current canonical long dark-plum hair stays loose at canonical length; yellow scrunchie remains on one wrist
- Strip 017→018: SAME technical mask remains attached but temporarily clears Hyun-woo's mouth while eating; lower face stays concealed; Strip 018 rests chopsticks first, then visibly reseats/locks SAME mask with `TCHK`; no eating through mask
- practical knife draw leaves sheath at desk; knife floor impact spot remains fixed until Strip 028 pickup
- Strip 023: Nari makes one short visible half-step/lean to realistic blowing distance before `PFF`; preserve that table-edge-adjacent geometry through shriek → knife slip → `CLANG` → wrist catch and Strip 024
- phone after blackout: desk → Nari pickup → entry/security/voicemail → kitchen counter before cabinet opening
- Strips 029–032: Nari uses the OTHER untouched dining chair; Hyun-woo's pushed-back chair remains pushed back
- A5 notebook physically desk → dining table; no teleport/digital substitution

## Canonical Reference Gate

Priority:
1. current user instruction
2. current strip/chapter story script
3. current approved character WebP
4. approved reusable environment WebP
5. approved reusable object WebP
6. previous approved rendered strip temporary state

Reject stale/wrong-path references, room-axis flips, impossible camera angles, moved fixed architecture/furniture/appliances, object redesign, or propagation of previous-strip drift against permanent canon.

## Black Read-Slice Gate — Absolute

Inspect every distinct slice:
- SMALL BLACK GUTTER between consecutive distinct vertical slices
- diagonal/slanted BLACK DIVIDER between distinct camera slices sharing one row
- no face/balloon/text/prop/background crosses divider
- compact intentional separators only
- slightly larger spacing only for purposeful suspense/time cuts
- no giant filler bands
- no black technical bar at A/E seam where art/effect must continue across files

## No-Dead-Space Gate

Inspect lower 20–25% of every rendered strip. Large space is allowed only for existing narration/time transition, meaningful silence, reveal delay, scripted SFX, reaction hold, canonical environment/atmosphere, or controlled seam. Small black gutters never excuse a huge unused canvas.

## Outage / Hyun-woo Gate — Strips 014–025

- no phone-screen activation during outage
- Nari loose-hair/wrist-scrunchie state persists
- first `SLURP` offscreen
- knife draw leaves sheath desk
- Strip 016 ends with Nari stop/shock + partial canonical Hyun-woo teaser in correct chair
- Strip 017 continues exact geometry; SAME mask clears mouth only enough to eat; no noodles through mask
- Strip 018 visibly stops eating before same mask reseat/lock `TCHK`
- Nari stays entrance until exactly one cautious step Strip 019
- chair push/rise/crossing visible, no teleport
- fridge `YOON NARI` then `IDENTITY LOCKING`
- Strip 023 short physical reach to fixed candle before `PFF`
- candle out → shriek → knife slip → floor impact → wrist catch, exact order
- post-candle-reach geometry carries into Strip 024
- city power may return while Unit remains dark
- Hyun-woo physical until Unit 2407 ordinary power returns
- no visible disappearance process

## Powered Aftermath Gate — Strips 026–032

- normal powered baseline
- no physical/reflected/silhouetted Hyun-woo
- evidence chain door → lock history → camera → security preserved
- same phone continues through voicemail, then counter before cabinet opening
- same storage stockpot/towels/unplugged speaker
- practical knife floor → hand → desk sheath before food
- food inspected before one cautious bite with clean chopsticks
- Nari sits untouched chair, not Hyun-woo pushed-back chair
- paper-only / south-wall warning preserved
- A5 notebook physical route preserved
- TV visibly unplugged at final activation
- brass backup key remains entry tray unless explicitly moved

## Final Gate

Strip 032 ends on hostile `NEW TENANT CONFIRMED` + one `FZZT` light flicker while Unit 2407 remains powered. No physical Hyun-woo, no second blackout, no extra chapter-end copy, and no giant bottom tail.

## Current Fresh-Audit Result

- **Text/script/causality:** PASS
- **Dialogue/source ownership:** PASS
- **SFX script/source/action logic:** PASS at prompt level
- **Real-life movement/body mechanics:** PASS at prompt level
- **Spatial/object/character state continuity:** PASS at prompt level
- **Panel/strip planned continuity:** PASS at prompt level
- **Strict flat 2D instruction authority:** PASS; actual strip pixels await generation
- **Character/environment/object visual authority presence:** PASS — approved WebPs present
- **Exact Markdown reference paths:** UNDER REPAIR / must resolve to actual WebPs before Strip 001
- **Rendered strip visual audit:** BLOCKED — Strip 001–032 artwork not yet present
- **Seam/stitch/dead-space/mobile-lettering visual audit:** BLOCKED — requires rendered/stitched artwork

### Current Gate Counts Before Reference-Path Repair Completes

- **BLOCKER: 1 category** — stale/ambiguous/obsolete Markdown visual attachment paths must be migrated to exact approved WebPs
- **MAJOR: 0 unresolved deterministic story/script issues**
- **MINOR requiring correction: 0 in Chapter 1 story logic**
- **WARNING requiring explanation: 0**

**FINAL STATUS: NOT PRODUCTION COMPLETE — REFERENCE-PATH MIGRATION IN PROGRESS; RENDERED STRIP PRODUCTION NOT YET COMPLETE**
