# Chapter 1 Manhwa Generation Checklist

Status: **FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

A fresh `manhwa-2d-production-auditor` hardening pass has now been completed from Strip 001 through Strip 032 after actual generation attempts exposed production-level failures that the earlier prompt audit did not constrain strongly enough.

## Why The Full Hardening Was Required

The prior generation attempts revealed concrete failures that are now explicit rejection gates:
- `unplugged` was sometimes interpreted as pulling a cable from the appliance body instead of removing the plug from the **wall-mounted socket/outlet**
- objects / food / noodles / chopsticks could disappear between adjacent vertical slices despite no physical action
- simple movement / reach / sitting / standing / handoff actions could be skipped by camera cuts
- narration could reuse one generic design regardless of scene function
- production markers such as `V-*` could appear in the top-left of generated art
- attached references could be treated as loose inspiration instead of immutable identity / geometry / object authority

These are now hardened at global, object-reference, seam, and individual-strip levels.

## Prior Generated Strip Attempts — REJECTED AS AUTHORITY

Do not reuse pre-hardening generated artwork as `APPROVED Strip N` for the new production run.

The retest starts from **new Strip 001**.

Only a strip generated under the current hardened package and passing current visual QA may become temporary continuity authority for the next strip.

## Scope

- one continuous vertical Chapter 1
- 146 internal read beats
- 32 technical strips
- historical P001–P018 and V01–V146 identifiers are production-only
- no active `Comics/` dependency

## Binding Global Gates — Absolute

Every strip inherits:
- `../../style-guide.md`
- `../../lettering-sfx-guide.md`
- `../../seam-continuity-protocol.md`
- `../../vertical-scroll-layout-guide.md`
- `../../generation-workflow.md`
- `../../production-readiness-gate.md`

Every current Strip 001–032 prompt additionally contains strip-specific hardening. A global rule cannot be used to weaken a stricter strip rule.

## Repository Image Format Rule

Reference-image prompts may generate PNG first as a local intermediate. After visual approval, manually convert the accepted PNG to WebP and commit/store the WebP.

Production-strip Markdown attaches the exact committed WebP, not the temporary/deleted PNG.

## Required Chapter 1 Character WebPs — PRESENT / CURRENT

- `Character-References/nari-canonical-flat2d.webp`
- `Character-References/hyunwoo-canonical-flat2d.webp`
- `Character-References/mrs-na-canonical-flat2d.webp`
- `Character-References/seungjae-canonical-flat2d.webp`

Character locks:
- Nari = exactly 30, long dark-plum hair approximately mid-back, loose by default, yellow scrunchie on one wrist, one beauty mark beside left mouth corner
- Hyun-woo = long low-tied black hair, broad build, same matte-black technical mask, same circuit-sigil tattoo map
- Mrs. Na = late 60s, silver twist, jade earrings, mauve coat, analog watch; Unit 2407 key remains separate object authority
- Seungjae = exactly 30, same age group as Nari, youthful contemporary coworker presentation

## Required Unit 2407 WebPs — PRESENT / CURRENT

Primary Chapter 1 set:
- `Manhwa/Environment-References/Unit-2407/unit-2407-floor-plan-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-entry-living-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-living-to-kitchen-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-kitchen-to-living-wide-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-hallway-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-desk-zone-detail-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-fridge-cabinet-zone-detail-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-lighting-state-sheet-reference.webp`
- `Manhwa/Environment-References/Unit-2407/unit-2407-room-angle-atlas-reference.webp` when an intended camera angle is not sufficiently covered by the primary views

Full reusable pack also includes Bedroom A, Bedroom B, and bathroom WebPs.

## Required Building Shared-Area WebPs — PRESENT / CURRENT

- `Manhwa/Environment-References/Building-Shared-Areas/rainy-building-entrance-reference.webp`
- `Manhwa/Environment-References/Building-Shared-Areas/building-lobby-elevator-reference.webp`

`building-shared-areas-bible.webp` is not a required Chapter 1 strip attachment and does not override the two named building authorities.

## Required Object WebPs — PRESENT / CURRENT

- `Manhwa/Object-References/smart-speaker-canonical-reference.webp`
- `Manhwa/Object-References/tv-canonical-reference.webp`
- `Manhwa/Object-References/refrigerator-canonical-reference.webp`
- `Manhwa/Object-References/electrical-operation-guide-canonical-reference.webp`
- `Manhwa/Object-References/brass-backup-key-canonical-reference.webp`

## Attached Reference Obedience Gate — Absolute

Approved attached WebPs are binding permanent authority, not inspiration.

Reject if production:
- redesigns face / hair / build / permanent accessories
- mirrors or relocates Unit 2407 architecture / furniture / appliances / wall sockets
- redesigns TV / speaker / refrigerator / binder / key / mask / recurring prop
- changes object scale/material identity for visual convenience
- propagates previous-strip drift against permanent canon

If a camera/action does not fit the attached canon, **recompose the shot**. Never rewrite the canon to fit the shot.

## START / ALLOWED CHANGE / END State Gate — Absolute

Every hardened strip explicitly defines or enforces:
1. START state inherited from approved prior strip or legal cut
2. only the scripted ALLOWED changes
3. persistent END state for the next strip

Anything not explicitly changed remains unchanged.

A camera cut, reverse angle, close-up, black gutter, or technical file boundary is not a state reset.

## Real-Scenario Cause / Action / Consequence Gate — Absolute

For every meaningful change verify:

`START STATE → PHYSICAL CAUSE → VISIBLE ACTION → RESULT → PERSISTENT END STATE`

Audit even simple mechanics:
- walking from one zone to another
- pickup / placement / handoff
- sitting / standing / chair clearance
- reaching a candle / key / cabinet / wall plug
- opening / closing hinge actions
- eating / lowering noodles
- knife release / fall / impact
- mask lowering / reseating

Reject a result shown without believable cause/action when that transition matters.

## WALL-SOCKET Unplugging Gate — Absolute

Unless a script explicitly states otherwise, `UNPLUGGED` means:
- electrical plug removed from **WALL-MOUNTED socket/outlet**
- appliance-side cord remains attached to the appliance body
- same cord ends in same loose wall plug
- wall socket remains empty
- disconnected wall-end state persists until an explicit re-plug action

Reject:
- cable pulled from TV / speaker / appliance body
- empty appliance power port used as unplug proof
- missing / moved wall socket
- disappearing loose plug
- changed cord side / count / routing without cause
- silent re-plug

Chapter 1 hard lock:
- Strip 006 speaker unplugged FROM WALL
- Strip 006 TV unplugged FROM WALL
- Strip 007 inherits exact loose plug + empty wall socket
- TV remains physically unplugged until the final Strips 031–032 activation
- stored speaker remains unplugged with attached cord + loose plug physically accounted for inside its stockpot/towel state

## Adjacent-Slice Micro-Continuity Gate — Absolute

Between every vertical slice X and X+1 verify persistence of:
- hands and held objects
- feet / facing / distance / seated-standing state
- food / noodle amount and path
- pot / bowl / chopstick pair identity and location
- packet / wrapper count and location
- cords / plugs / wall sockets
- key / binder / note / pen / notebook / phone / tablet / bag
- knife / sheath / fixed floor impact spot
- candle / holder / flame / wick state
- chair position / occupancy
- cabinet / stockpot / lid / exactly two towels / speaker
- device display / power / lighting state

Occlusion is not disappearance. Close-ups do not erase props.

Food/noodles visible in one slice may change only through visible/physically unmistakable eating, slurping, lowering, placement, spill, or legal time cut.

## Character ↔ Environment Physical Gate — Absolute

Verify:
- feet/body support
- seated body matches actual chair seat/back
- reach distance is plausible
- eyeline points to real target location
- door/cabinet motion respects hinges/walls
- walking path respects canonical circulation
- bodies do not pass through furniture/appliances/walls
- scales match references
- reverse angles are derivable from floor plan, never mirrored for convenience

## Narration Design Gate — Scenario-Driven

Narration wording is locked but visual treatment must follow scenario/function instead of one repeated design.

Allowed coherent variants:
- time/location transition → compact editorial
- ordinary observation / dry comedy → restrained unobtrusive
- warning / procedural → firmer utilitarian
- investigation / evidence → report-like
- ominous realization → sparse higher-contrast
- suspense / listening / reveal → minimal footprint

Reject narration that:
- uses one generic identical box everywhere regardless of function
- imitates device UI / handwriting / speech / production metadata
- covers hands, food paths, plugs/sockets, device clues, or key continuity evidence
- invents new narration to explain a physical action that should be drawn

## NO Production Metadata Gate — Automatic Reject

Reader-facing art must never contain, especially at top-left:
- `V01`, `V-01`, V IDs
- P IDs
- strip IDs
- BEAT / PANEL / SCENE / SHOT labels
- prompt/reference/QA/layout headers
- circled production numbers / crop marks / technical notes

Scripted reader-facing times such as `12:43 A.M.` are allowed only as story narration and must not resemble technical labels.

## High-Risk Chapter 1 Continuity Locks — Re-Hardened

### Strips 001–004
- one moving box route through threshold
- Mrs. Na physical door→counter route
- one manual + one brass key
- key counter→Nari hand→entry tray
- binder remains counter

### Strips 005–007
- one chopstick pair established before fall; same floor spot through Strip 006 V26
- any visible snack/food persists until physical change/time cut
- speaker unplugged from WALL in Strip 006
- TV open-plan→wall-outlet walking route visible
- TV plug removed from WALL socket; appliance-side cord stays attached
- V30 proof = TV ON + attached cord + loose plug + empty wall socket
- Strip 007 preserves exact unplugged wall-end state
- key tray→hand→tray with visible movement

### Strips 008–010
- speaker counter→cabinet/stockpot by visible route
- same speaker cord + loose wall plug remain physically accounted for in storage
- one stockpot / one lid / exactly two towels
- physical note/pen do not reset
- phone photos fail but real note remains
- binder counter→hand→open inspection→close→counter physically
- Section 16→18; no normal Section 17

### Strip 011
- exactly two shopping bags on return
- exactly six emergency noodle packets
- blackout knife remains distinct from guarded fruit knife
- emergency tray fixed right of keyboard

### Strips 012–013
- one Nari shoulder bag; tablet never leaves bag
- one Seungjae phone/watch/earbuds/umbrella
- Seungjae age 30
- entrance behind/elevator ahead after entry
- turn toward exit only V64

### Strips 014–016
- hallway lamp ON before outage
- actual one power-loss event
- Nari long loose hair / wrist scrunchie
- phone remains dark
- flashlight/radio fail; knife remains sheathed until Strip 016
- knife draw leaves sheath desk
- desk→hallway→kitchen route visible
- Hyun-woo teaser only in correct chair

### Strips 017–018
- same pot/noodles/chopsticks/trivet/cloth/candle persist across dialogue cuts
- visible noodle strand must complete bite/slurp or lower before next state
- mask remains attached while mouth cleared
- Strip 018: stop eating → resolve noodles → chopsticks rest → mask reseat → `TCHK`

### Strips 019–022
- exactly one cautious step in Strip 019
- chair seated→push back→`SKRRK`→rise in Strip 020
- physical chair→around-table→blocking route in Strip 021
- `YOON NARI` persists; `IDENTITY LOCKING` is added beneath it
- candle stays same holder/table location; no early reach

### Strip 023
Exact separate states:
1. short half-step/lean
2. `PFF`; candle out; knife still held
3. `KIIIIII`; knife only loosens
4. knife fully leaves hand
5. `CLANG` at one fixed floor spot
6. only afterward wrist catch

### Strips 024–025
- Strip 024 begins wrist still held; visible release first
- knife remains floor spot
- city power returns before Unit power
- Hyun-woo remains physical until Unit 2407 power returns
- no visible disappearance effect
- power return does not reset scene evidence

### Strips 026–030
- phone desk→pickup→entry→security→voicemail→counter
- two cabinet chimes from same CLOSED cabinet
- Strip 028: approach→phone placement→kneel→open cabinet
- stored speaker remains unplugged with attached cord/loose plug
- knife exact old floor spot→handle pickup→desk→same sheath before food
- Nari sits OTHER untouched chair by real body mechanics
- food inspected before one complete cautious noodle bite
- clean Nari chopsticks distinct from Hyun-woo pair
- notebook/pen desk→same chair/table physically

### Strips 031–032
- notebook remains physical; exact handwriting
- Nari stays same untouched chair
- TV remains unplugged FROM WALL since Strip 006
- appliance-side cord still attached; loose wall plug; empty wall socket
- `NEW TENANT CONFIRMED` appears only in Strip 032
- one `FZZT` while Unit remains powered
- no Hyun-woo, no second blackout, no extra ending copy

## Strict Flat 2D Human-Drawn Style Gate — Absolute

Actual rendered pixels must visibly satisfy the current style guide. Prompt wording alone cannot pass this gate.

## Current Post-Hardening Gate Counts

At the **prompt / preproduction authority level** after the clean-room hardening re-audit:
- **BLOCKER: 0**
- **MAJOR: 0 unresolved deterministic prompt/canon issues**
- **MINOR requiring correction: 0**
- **WARNING requiring explanation: 0**

These counts do **not** mean the rendered chapter passes. New Strip 001–032 images have not yet been generated and approved under this hardened package.

## Current Verdict

**FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

Next action: generate a **new Strip 001**, deep-audit its actual pixels, repair/regenerate until it passes, then move sequentially to Strip 002.
