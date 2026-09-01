# Chapter 1 — `manhwa-2d-production-auditor` Second Full Deep-Hardening Audit

Status: **SECOND FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

This record supersedes the first deep-hardening audit as the current prompt/preproduction authority.

The first hardening PASS was deliberately **not accepted as proof**. A second clean-room pass re-read Strip 001 through Strip 032, the global production workflow/template/layout/readiness rules, the strip manifest, and every high-risk cross-strip handoff with a narrower question:

> Could an image generator still technically “follow the words” while producing a physically wrong, reference-drifting, continuity-breaking, or visually ambiguous result?

Where the answer was yes, the prompt/control files were repaired again.

## Second-Pass Audit Focus

The second pass audited:
- attached reference precedence vs previous rendered strip
- whether permanent canonical drift could still propagate
- whether continuity-critical actions are **visually proved**, not merely described
- whether camera cuts can hide pickup/placement/contact mechanisms
- exact hand occupancy and contact points
- feet/chair/body support mechanics
- wall plug vs appliance-side cable behavior
- food/noodle/chopstick persistence
- exact tool return state
- exact wrist identity across knife-drop/contact sequence
- phone/tablet/bag physical realism
- key/manual/object transfer routes
- narration design **and placement** by scenario
- top-left `V-*` / production-label leakage
- final TV unplug state from Strip 006 through Strip 032
- attachment-map strength at powered aftermath/final TV sequence

## Second-Pass Finding 1 — Critical Actions Could Still Hide Their Mechanism

### Finding

The first hardening often required the correct action, but some prompts could still be satisfied by showing a before-state and later result while cropping the decisive contact point.

That leaves room for errors such as:
- `BEEP`/`CLICK` with no actual smart-lock/door operation
- key suddenly in hand/tray
- unplugged appliance with socket interaction offscreen
- knife suddenly sheathed/on floor
- cabinet already open
- standing body with no chair mechanics

### Repair

Added a global **MANDATORY ACTION-PROOF FRAMING** rule to:
- `../../generation-workflow.md`
- `../../prompt-template.md`
- `../../vertical-scroll-layout-guide.md`
- `../../production-readiness-gate.md`
- `Production-Strips/README.md`
- chapter manifest/checklist

Continuity-critical state changes must show the physical mechanism/contact point in the same slice or immediately adjacent causally continuous detail slice.

**PASS after repair.**

## Second-Pass Finding 2 — Previous Strip Needed Stronger Subordination To Permanent Canon

### Finding

Some strip wording said attached WebPs + previous approved strip were “binding,” which could be misread as equal permanent authority.

### Repair

Current rule:
- attached character/environment/object WebPs = permanent authority
- previous approved strip = temporary state/seam authority only

If previous art contains permanent drift, repair permanent face/hair/body/room/socket/appliance/object construction back to canon while preserving legitimate temporary pose/held-item/power/open-state/food/seam state.

**PASS after repair.**

## Second-Pass Finding 3 — Strip 001 Smart-Lock Entry Mechanism Was Under-Proven

### Finding

Strip 001 had the correct corridor→threshold route, but could still show `BEEP`/`CLICK` and jump from closed door to Nari inside without proving lock operation/door opening.

### Repair

Strip 001 now requires:
1. same box securely supported
2. real hand/finger contact with canonical smart lock
3. `BEEP`
4. latch release
5. physical door opening on canonical hinge
6. only then threshold crossing

No extra hand / box teleport / closed-door crossing permitted.

**PASS after repair.**

## Second-Pass Finding 4 — Strip 003 Conceptual Phone/Tablet Inserts Were Too Abstract

### Finding

The spoken warning `DON'T TRY TO REPLACE IT WITH A PHONE OR TABLET.` allowed optional conceptual device inserts. Those could become floating UI, holograms, unexplained devices, or non-real scenario imagery.

### Repair

Strip 003 now explicitly prefers **no phone/tablet visual at all**. The real hallway lamp + spoken dialogue carry the warning. Floating/conceptual device graphics are rejected.

**PASS after repair.**

## Second-Pass Finding 5 — Strip 004 Key Transfer Needed Visible Pickup/Placement Contacts

### Finding

The correct counter→hand→tray route was written, but pickup and tray-contact could still be hidden by montage framing.

### Repair

Strip 004 now requires:
- hand contacts same key at counter
- key leaves counter; old location visibly/logically empty
- same key carried to entry
- fingers lower key into real tray
- key contacts tray
- fingers release
- `CLINK` at tray
- no duplicate remains

**PASS after repair.**

## Second-Pass Finding 6 — Strip 005 Still Invited Unscripted Food

### Finding

The first hardening said any snack/food shown must persist. That still gave generation permission to invent food/noodles, creating unnecessary continuity burden before the actual emergency-noodle sequence.

### Repair

Strip 005 now forbids visible:
- noodles
- noodle bowl
- food packet/wrapper
- plated snack
- cup/bowl that introduces new food continuity

Only the scripted single chopstick pair is established/tracked through Strip 006 V26.

**PASS after repair.**

## Second-Pass Finding 7 — Strip 015 Failed-Tool End State Was Ambiguous

### Finding

`flashlight + radio failed and remain near/in tray according to visible handling` was not deterministic enough for Strip 016.

### Repair

Exact sequence now:
1. flashlight leaves tray
2. tests twice
3. returns to SAME tray position
4. radio then leaves tray
5. tests once
6. returns to SAME tray position
7. knife remains sheathed/untouched

Strip 016 starts from those exact positions and only reaches/draws the knife.

**PASS after repair.**

## Second-Pass Finding 8 — Strip 023 Hand / Ear / Knife / Wrist Mechanics Were Still Too Open

### Finding

`Nari brings hands toward ears; knife slips` could create impossible hand occupancy or wrist swapping.

### Repair

Current exact body chain:
- free hand goes toward one ear
- knife hand reflexively rises toward other ear
- grip in knife hand begins failing
- same knife fully leaves those fingers
- same knife falls
- same knife impacts one floor spot `CLANG`
- only afterward Hyun-woo catches the wrist of that SAME former knife arm

Strip 024 begins with that same wrist held and visibly releases that same wrist before fridge clicks.

**PASS after repair.**

## Second-Pass Finding 9 — Powered Evidence TV State Needed TV Canonical Attachment

### Finding

Strip 026 explicitly preserves the TV wall-unplug evidence state but did not attach the TV object canonical. Strip 030 similarly carries that state directly into the final TV sequence.

### Repair

Added `Manhwa/Object-References/tv-canonical-reference.webp` to:
- Strip 026
- Strip 030
- manifest attachment map

Permanent TV body/cord construction can no longer be inferred from prior render alone at those points.

**PASS after repair.**

## Second-Pass Finding 10 — Strip 031 Wall-Unplug Proof Was Still Optional

### Finding

The first hardening said the final activation should ideally show the loose plug/empty socket. That is too weak given the observed generation failure.

### Repair

Strip 031 now MANDATES same-moment proof using either:
- one composition showing active TV + TV-side cord attached + loose plug + empty wall socket; OR
- two immediately adjacent causally continuous slices proving the same state

A hidden second power cable is forbidden.

Strip 032 inherits that already-proven state and may not reinterpret/re-plug it.

**PASS after repair.**

# Second Clean-Room Strip 001→032 Re-Audit

## Strips 001–004 — Entry / Mrs. Na / Rule / Key Transfer

Verified after second repair:
- Strip 001 physically proves smart-lock contact, latch release, door opening, threshold crossing, and one-box route
- Strip 002 physically establishes Mrs. Na entrance, binder placement, key detachment, and counter state
- Strip 003 no longer invents conceptual phone/tablet inserts; actual hallway lamp + dialogue remain real-world anchors
- Strip 004 visibly proves key pickup and tray placement; binder remains counter
- narration/time captions cannot default to repetitive technical-tag placement
- no reader-visible V/P/strip labels

**PASS at second-hardened prompt level.**

## Strips 005–007 — Chopsticks / Speaker Wall-Unplug / TV Wall-Unplug / Fridge / Key

Verified:
- Strip 005 contains no invented visible food/noodles; only one chopstick pair persists
- V24 shows hand→chopstick release→fall before `CLATTER`
- same pair remains floor through Strip 006 V26 until legal time cut
- speaker unplug action targets plug BODY at wall socket; appliance-side cord remains attached
- TV route physically open-plan→wall outlet
- TV unplug proves hand + plug + wall socket; no cable-pulling/appliance-side disconnect
- V30 proves TV ON + TV-side attached cord + loose wall plug + empty wall socket
- Strip 007 inherits exact state; no silent re-plug
- key tray→hand→fridge route→tray remains physical

**PASS at second-hardened prompt level.**

## Strips 008–010 — Speaker Storage / Note / Digital Failure / Binder

Rechecked without new required correction:
- speaker counter→cabinet→same stockpot with cord/plug accounted for
- one lid / exactly two towels
- guarded fruit knife distinct from blackout knife
- same paper/pen persist
- phone capture failure does not erase physical note
- tablet route remains physical
- binder counter→hand→open/page sequence→close→counter remains physical
- no normal Section 17
- actual south-wall panel remains closed

**PASS at second-hardened prompt level.**

## Strip 011 — Blackout Kit

Rechecked without new required correction:
- exactly two shopping bags on return
- exactly six unopened noodle packets
- one practical sheathed blackout knife distinct from guarded fruit knife
- tray fixed right of keyboard
- hallway lamp on

**PASS at second-hardened prompt level.**

## Strips 012–013 — Seungjae / Building / Bag / Tablet

Rechecked without new required correction:
- Seungjae exactly 30
- one phone/watch/earbud pair/umbrella
- Nari one shoulder bag
- tablet remains physically inside bag
- bag opening must be actually parted; no X-ray visibility
- lobby route remains entrance behind / elevator ahead
- Seungjae turns back only at V64

**PASS at second-hardened prompt level.**

## Strips 014–016 — Outage / Failed Tools / Knife / Approach

Verified after second repair:
- powered baseline and hallway lamp established before outage
- outage changes power only, not geometry
- Nari long loose hair / wrist scrunchie remain
- phone stays dark
- Strip 015 exact flashlight pickup→failure→tray return, then radio pickup→failure→tray return
- knife remains untouched until Strip 016
- Strip 016 starts flashlight/radio in exact tray positions, then visibly reaches/draws only knife
- blade/sheath separation must be shown; empty sheath remains tray
- desk→hallway→kitchen route remains physical
- Hyun-woo teaser remains seated in correct chair

**PASS at second-hardened prompt level.**

## Strips 017–018 — Food / Chopsticks / Mask

Rechecked without new required correction:
- same pot/noodles/broth/chopsticks/trivet/cloth/candle persist through close-ups
- visible noodle strand cannot disappear without completed bite/slurp/lowering
- mask remains same attached hardware in eating state
- Strip 018: resolve visible food → chopsticks leave mouth → rest at/in pot → free hand → mask rises → full seat → `TCHK`
- no position reset / no early lower-face reveal

**PASS at second-hardened prompt level.**

## Strips 019–022 — One Step / Chair Rise / Crossing / Fridge / Candle

Rechecked without new required correction:
- exactly one Nari step with weight shift→foot→packet contact→`CRINKLE`
- closer mark persists
- Hyun-woo seated→feet support→chair push→`SKRRK`→stand beside same chair
- pushed chair remains
- Strip 021 physical walk around table, no teleport
- `YOON NARI` remains while `IDENTITY LOCKING` is added
- same candle/holder remains fixed; no early reach

**PASS at second-hardened prompt level.**

## Strips 023–024 — Candle / Knife / Same Wrist

Verified after second repair:
- V103 realistic half-step/lean → candle out; knife still in same knife hand
- V104 free hand→one ear; knife hand→other ear; grip begins failing
- V105 same knife fully leaves former knife-hand fingers
- V106 same knife hits one floor spot `CLANG`
- V107 only afterward Hyun-woo catches SAME former-knife-hand wrist
- Strip 024 starts that same wrist still held
- visible same-wrist release occurs before fridge `TIK. TIK. TIK.`
- knife remains floor spot; no arm/wrist reset

**PASS at second-hardened prompt level.**

## Strip 025 — City Return / Unit Return

Rechecked without new required correction:
- city recovery and Unit power return remain distinct
- Hyun-woo remains physical until Unit supplied power returns
- no visible disappearance effect
- power return does not clean/reset evidence

**PASS at second-hardened prompt level.**

## Strips 026–030 — Evidence / Phone / Cabinet / Speaker / Knife / Food / Notebook

Verified after second repair:
- Strip 026 now attaches TV canonical while preserving loose-plug/empty-wall-socket evidence
- phone desk→contact/pickup→entry→archive/security route physically proven
- latch test uses real hardware/contact
- cabinet chimes remain same CLOSED source
- Strip 028 exact phone placement before kneel/cabinet open
- speaker cord + loose wall plug remain accounted for in stockpot/two towels
- knife remains same old floor spot until handle pickup
- Strip 029 same knife physically sheathes before food
- Nari sits OTHER untouched chair through real body/chair mechanics
- one complete cautious bite; clean chopsticks distinct
- Strip 030 now attaches TV canonical and visibly proves notebook pickup + same-chair return

**PASS at second-hardened prompt level.**

## Strips 031–032 — Final TV

Verified after second repair:
- one physical notebook + one pen
- Nari remains same untouched chair
- TV object canonical controls permanent body/cord construction
- TV remains wall-unplugged from Strip 006
- Strip 031 must visually prove SAME active TV + TV-side cord attached + loose plug + empty wall socket in same moment / adjacent causal detail
- no second cable/power source
- final message still withheld until Strip 032
- Strip 032 inherits proven wall-disconnected state and cannot reinterpret/re-plug
- one `FZZT`; Unit remains powered
- no Hyun-woo / second blackout / extra ending copy

**PASS at second-hardened prompt level.**

# Narration / Placement Second Re-Audit

Current package now locks both **design and placement** by scenario.

Reject:
- one narration box design everywhere
- repeated small top-left caption/tag treatment across the chapter
- time captions that resemble production IDs
- narration that covers action-proof evidence
- narration invented to explain an action that should be drawn

No scripted wording was rewritten.

**PASS at instruction level. Actual typography must still be visually inspected.**

# Production-Label Second Re-Audit

Every strip continues to prohibit reader-visible:
- V IDs
- P IDs
- strip/beat/panel/scene/shot labels
- technical headers/QA/layout markers

Top-left V-label generation is an automatic rejection.

**PASS at instruction level. Actual renders remain unverified.**

# Second-Pass Prompt Gate Counts

After all second-pass repairs and clean-room re-read:
- **BLOCKER: 0**
- **MAJOR: 0 unresolved deterministic prompt/canon issues**
- **MINOR requiring correction: 0**
- **WARNING requiring explanation: 0**

These counts apply only to the current textual/reference authority package. They do **not** certify any rendered image.

# Rendered Visual Status

All earlier problematic strip attempts remain rejected as continuity authority for the intended retest.

The following gates remain **PENDING / UNEXECUTED** until new renders are inspected:
- actual reference fidelity
- actual smart-lock/door mechanics
- actual wall-socket unplugging
- actual adjacent-slice object/food/tool/wrist continuity
- actual narration typography/placement variation
- actual no-production-label compliance
- actual lettering/SFX placement
- actual flat-2D style fidelity
- actual seams/dead-space/mobile readability
- final stitched chapter audit

# Final Current Verdict

**SECOND FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

Next production action:
1. generate a NEW Strip 001 from its current second-pass hardened prompt and exact approved WebPs
2. deep-audit actual pixels against the second-pass gates
3. reject/fix/regenerate until Strip 001 passes
4. only then use it as temporary continuity authority for Strip 002
5. continue sequentially through Strip 032
6. stitch and run a fresh final clean-room visual audit
