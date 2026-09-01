# Chapter 1 Manhwa Generation Checklist

Status: **THIRD FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

A third clean-room `manhwa-2d-production-auditor` pass was completed from Strip 001 through Strip 032. The second PASS was not accepted as proof.

## Why A Third Pass Was Necessary

The third pass looked for defects that can survive strong causality/action-proof language:
- impossible hand occupancy even when object routes are individually correct
- props with no real-world reason/source
- packet/wrapper provenance gaps across many strips
- same object suddenly changing floor/table location without pickup
- device handoffs hidden at strip seams
- relative prop positions swapping across reverse angles
- correct wall-unplug logic but drifting outlet location/height/faceplate
- stored-object packing that does not match its later reopening
- Nari/body position drifting during a power-state change
- writing tools disappearing when attention shifts to TV

## Third-Pass Findings And Repairs

1. **Strip 002 — Mrs. Na could still require three handheld objects in two hands.**
   - handbag now independently shoulder/forearm-supported
   - binder occupies one hand; key ring other
   - binder must be set/released first
   - freed hand then assists key detachment/placement

2. **Strip 005 — chopsticks had no believable physical context after food was removed.**
   - exactly one clean dry pair is in Nari's hand because she is tidying/putting them away
   - assistant/light interruption stops put-away
   - no visible food/noodles/bowl/packet
   - robot vacuum gag explicitly uses harmless non-plot cable, never speaker/TV/fridge/lamp cord

3. **Strip 006–007 — unplug mechanics were correct but outlet itself could still drift.**
   - speaker/TV outlets are frozen local environment landmarks
   - same wall, height, faceplate orientation, nearby furniture relation, cord-route family persist
   - reverse shots cannot invent convenient sockets

4. **Strip 008 / 028 — stored speaker arrangement was not exact enough to survive reopening.**
   - exact closed stack: TOWEL1 liner → speaker + attached coiled cord + loose plug → TOWEL2 cover → lid
   - Strip 028 reopens in reverse: lid off/set flat beside pot → TOWEL2 folded back → speaker/cord/plug exposed on TOWEL1
   - lid/towels remain at deterministic open positions while Nari walks away

5. **Strip 009→010 — phone/tablet handoff could still teleport.**
   - after second `SNAP`, phone visibly placed flat beside physical note; pen remains there
   - Nari leaves phone+pen and walks to desk/tablet
   - Strip 010 explicitly retrieves same phone from beside note before binder route

6. **Strip 009 — failed photo proof could degrade into generic black/error screen.**
   - captured image must preserve same surrounding surface/framing context while note/writing evidence is absent
   - no generic black/error/blur substitute

7. **Strip 010 — missing Section 17 was spoken but not physically demonstrated strongly enough.**
   - same binder physically shows Section 16
   - fingers contact page edge
   - physical page turn/advance
   - next relevant header Section 18
   - no normal Section17 page/tab
   - only then Nari states it is missing

8. **Strip 011 — return-home scene lacked entry/living visual authority.**
   - added `unit-2407-entry-living-wide-reference.webp`
   - smart-lock → `BEEP` → latch → door-open → both-bag threshold crossing must be visible
   - exactly six noodle packets; other pantry food cannot resemble a seventh noodle packet

9. **Strips 012–013 — Seungjae's phone/umbrella/watch/earbuds could require extra hands.**
   - Strip012 starts phone one hand, umbrella other
   - phone dies in same hand, then visibly pocketed before seam
   - Strip013 phone stays pocketed; folded umbrella one hand; free hand sequentially checks watch then earbuds

10. **Strips 017–019 — empty spicy-seafood packet appeared from nowhere in Strip019.**
    - Strip017 now establishes five unopened pantry packets + one used/empty spicy-seafood OUTER packet at fixed floor spot
    - separate small seasoning wrapper stays at fixed table spot
    - same outer packet persists through Strip018 and is the exact packet nudged in Strip019

11. **Strips 017–022 — prop existence was locked, but relative topology could still swap in reverse shots.**
    - pot/trivet, cloth hot-handle side, candle, seasoning wrapper, used chopsticks, empty packet, chair positions now treated as one conserved physical topology
    - reverse shots cannot swap story-world sides/order

12. **Strip 017→018 — used chopstick state was ambiguous.**
    - Strip017 ends with same chopsticks still in Hyun-woo's hand, lowered near pot
    - Strip018 visibly places/releases them at one fixed pot rest point before mask reseat

13. **Strip 021 — Hyun-woo's walk could switch to opposite side of table across camera cuts.**
    - first V94 movement slice establishes route side
    - all subsequent V94 movement continues same physical side/path

14. **Strip 025→026 — Nari could drift during Unit power return/seam.**
    - Strip025 freezes exact feet/table-edge position through V113–V118; power snap changes arms/light only
    - Strip026 begins at that exact position and only then walks to desk

15. **Strip 029 — empty outer packet teleported from floor to table.**
    - after knife is safely sheathed, Nari visibly picks up SAME floor packet and carries it to table
    - then places it beside seasoning wrapper

16. **Strip 029 — Nari's clean chopsticks appeared without physical source.**
    - Pair A = Hyun-woo used pair remains fixed pot rest point
    - Pair B = Nari clean pair visibly retrieved from ordinary kitchen utensil storage
    - after one bite Pair B is visibly placed at fixed Nari-side table spot

17. **Strips 030–032 — final table/cabinet state could still silently clean/reset.**
    - empty outer packet + seasoning wrapper remain table
    - Pair A and Pair B remain separate fixed spots
    - open speaker cabinet remains: lid flat beside pot, TOWEL1 liner, speaker+cord/plug, TOWEL2 folded back

18. **Strip 031→032 — pen state was ambiguous when Nari turns toward TV.**
    - after hypothesis Nari physically places/release same pen horizontally across lower/open notebook page/margin
    - only then turns toward TV
    - Strip032 inherits notebook+pen state unchanged

## Prior Generated Strip Attempts — REJECTED AS AUTHORITY

Do not reuse old attempts as `APPROVED Strip N` unless freshly audited against current third-pass gates and actually passed. Intended retest starts from **new Strip 001**.

## Core Chapter Scope

- one continuous vertical Chapter 1
- 146 internal read beats
- 32 technical strips
- P/V identifiers production-only
- no active page-grid pipeline

## Current Canonical Visual Authorities

Characters:
- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

Core objects:
- `Manhwa/Object-References/smart-speaker-canonical-reference.webp`
- `Manhwa/Object-References/tv-canonical-reference.webp`
- `Manhwa/Object-References/refrigerator-canonical-reference.webp`
- `Manhwa/Object-References/electrical-operation-guide-canonical-reference.webp`
- `Manhwa/Object-References/brass-backup-key-canonical-reference.webp`

Environment packs:
- Unit 2407 approved WebPs
- Building Shared-Areas approved WebPs

PNG-first local generation remains allowed for reference prompts; committed WebP remains production authority.

## Third-Pass Mandatory Gates

### Permanent Canon Gate
Attached WebPs permanent authority. Previous strip temporary state only.

### Start / Allowed / End Gate
Anything not visibly/scriptedly changed persists.

### Action-Proof Gate
Critical contact mechanism must be shown, not implied only through SFX/result.

### Hand-Occupancy Gate
Every handheld object must fit actual two-hand/body support. Bags/phones/umbrellas/binders/key rings/devices cannot silently require extra hands.

### Prop Provenance Gate
A story-critical object cannot appear at a new location without a visible/source-valid route. This includes packet, chopsticks, phone, pen, lid, towels, key, knife, notebook.

### Prop Topology Gate
Reverse shots cannot swap physical story-world sides/order of conserved local arrangements.

### Fixed Outlet Landmark Gate
Once outlet is canonically/finally established, wall/height/faceplate/furniture relation remains fixed.

### Wall-Unplug Gate
Plug BODY removed from WALL socket; appliance-side cord remains attached; loose plug + empty socket persist. No cable-pulling or silent replug.

### Narration Gate
Scenario-specific design+placement; no generic identical box or repetitive top-left tag. No V labels.

### Flat 2D Pixel Gate
Strict flat matte human-drawn visual target must pass actual image inspection.

## Third-Pass High-Risk Handoffs

- 002→003: physically valid handbag/binder/key-ring state
- 005→006: one clean dry chopstick pair floor; no food; vacuum gag cable non-plot
- 006→007: fixed TV outlet landmark + loose plug/empty socket
- 008→009: exact closed speaker stack
- 009→010: phone+pen+note at note area; tablet desk
- 011→012: six noodles, real entry canonical attached
- 012→013: dead phone pocketed; umbrella hand + free hand
- 017→018→019: same empty outer packet floor + seasoning wrapper table + five pantry packets
- 018→019: used chopsticks fixed pot rest point
- 021 route: same chosen side around table
- 025→026: exact Nari feet position persists
- 028→029: lid flat beside pot; TOWEL2 folded back; speaker/cord/plug exposed
- 029→030: outer packet now table; Pair A pot rest; Pair B Nari-side table rest
- 030→031: table/cabinet topology unchanged
- 031→032: pen released on notebook; mandatory TV wall-unplug proof persists

## Current Third-Pass Gate Counts

At prompt / preproduction authority level after third clean-room repairs:
- **BLOCKER: 0**
- **MAJOR: 0 unresolved deterministic prompt/canon issues**
- **MINOR requiring correction: 0**
- **WARNING requiring explanation: 0**

These counts do **not** certify rendered strips. Actual pixel gates remain pending.

## Current Verdict

**THIRD FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

Next action: generate a **new Strip 001**, deep-audit actual pixels against the third-pass package, repair/regenerate until it passes, then proceed sequentially.
