# Chapter 1 Manhwa Generation Checklist

Status: **PREPRODUCTION SCRIPT / CONTINUITY / PROMPT AUDIT PASS — VISUAL PRODUCTION BLOCKED BY MISSING REQUIRED CANONICAL PNGS — NOT PRODUCTION COMPLETE**

Fresh `manhwa-2d-production-auditor` pass performed against the current 146-beat plan and all 32 current strip prompts. The deterministic story/script/dialogue/SFX/movement/state routes below are locked. Visual-only gates remain blocked until the required approved canonical PNGs and rendered strip images exist.

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

## Required Visual Authorities — BLOCKING

Before Strip 001 generation begins, every canonical PNG listed by the active strip package must exist and be approved.

Required reusable environment canonicals referenced by Chapter 1 include:
- `unit-2407-floor-plan-canonical.png`
- `unit-2407-entry-living-wide-canonical.png`
- `unit-2407-living-to-kitchen-wide-canonical.png`
- `unit-2407-kitchen-to-living-wide-canonical.png`
- `unit-2407-hallway-canonical.png`
- `unit-2407-desk-zone-detail-canonical.png`
- `unit-2407-fridge-cabinet-zone-detail-canonical.png`
- `unit-2407-lighting-states-canonical.png`
- `unit-2407-room-angle-atlas-canonical.png` when required by an uncovered camera angle
- `rainy-building-entrance-canonical.png`
- `building-lobby-elevator-canonical.png`

Required reusable object canonicals referenced by Chapter 1 include:
- `smart-speaker-canonical-states.png`
- `tv-canonical-states.png`
- `refrigerator-canonical-states.png`
- `electrical-operation-guide-canonical.png`
- `brass-backup-key-canonical.png`

If any required PNG is missing/stale/unapproved: **STOP. Do not improvise a substitute.** A Markdown reference prompt is not an approved PNG.

## Strip Prompt Completeness Gate — Absolute

Every one of `strip-001` through `strip-032` must explicitly list inside its own Markdown file:
- visible-character canonical(s)
- exact reusable environment canonical(s)
- exact reusable object canonical(s) when needed
- previous approved strip for 002–032
- current prompt

Reject a prompt that tells production to infer visual attachments only from the manifest.

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
3. current approved character canonical
4. approved reusable environment canonical
5. approved reusable object canonical
6. previous approved strip temporary state

Reject room-axis flips, impossible camera angles, moved fixed architecture/furniture/appliances, object redesign, or propagation of previous-strip drift against approved permanent canon.

## Character-State Gate

Nari:
- current canonical adult identity and left-mouth beauty mark fixed
- long dark-plum hair at canonical length; no short/bob redesign
- Strip 014 onward: hair loose, yellow scrunchie on one wrist

Mrs. Na:
- mature silver twist, jade earrings, mauve coat, gloves, analog watch

Seungjae:
- same office-casual identity; one foldable phone/watch/earbuds/umbrella

Hyun-woo:
- broad build, long low-tied black hair, same technical mask hardware, same tattoo map
- Strip 017 temporary eating position is a state change of the SAME mask, not redesign/removal

## Manual / Key Canonical Gate

Manual:
- same one binder across all appearances
- exact cover/title `UNIT 2407 / ELECTRICAL OPERATION GUIDE`
- ordinary physical paper/ring/tab construction
- `SECTION 16` → `SECTION 18` jump readable; no normal Section 17
- handwritten `KEEP ONE MAINS-POWERED LIGHT ON AFTER MIDNIGHT.` remains old physical handwriting on south-wall diagram page

Key:
- same one brass mechanical backup key
- initially on Mrs. Na key ring, detached to counter, then Nari to entry tray
- Strip 007 tray → Nari hand → tray
- remains tray during powered evidence sequence unless explicitly moved
- no duplicate, keycard, smart fob, fantasy key, silver/chrome redesign

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

**Text/script/causality:** PASS

**Dialogue/source ownership:** PASS

**SFX script/source/action logic:** PASS at prompt level; actual lettering placement awaits rendered strips

**Real-life movement/body mechanics:** PASS at prompt level

**Spatial/object/character state continuity:** PASS at prompt level

**Panel/strip planned continuity:** PASS at prompt level

**Strict flat 2D human-drawn instructions:** PASS after global authority repair; actual pixel compliance awaits rendered strips

**Environment/object canonical visual authority:** BLOCKED — required approved PNGs are not currently present in the repository package

**Rendered strip visual audit:** BLOCKED — no Strip 001–032 artwork files are currently present

**Seam/stitch/dead-space/mobile-lettering visual audit:** BLOCKED — requires rendered/stiched artwork

**FINAL STATUS: NOT PRODUCTION COMPLETE — REQUIRED VISUAL AUTHORITY / RENDER ASSETS MISSING**

See `chapter-01-real-scenario-continuity-audit.md` for the fresh audit record.