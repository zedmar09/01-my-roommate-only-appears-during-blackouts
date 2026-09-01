# Chapter 1 — `manhwa-2d-production-auditor` Full Deep-Hardening Audit

Status: **FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

This audit supersedes the earlier prompt/reference pass. It was initiated because actual strip-generation attempts exposed visual-production failures that were not sufficiently prevented by the previous prompt wording.

No prior PASS label was accepted as proof. The current package was reworked from Strip 001 through Strip 032 and then re-read at the high-risk causal/seam points.

## Trigger Findings From Actual Generation Attempts

The hardening pass specifically addresses these failures:

### 1. Incorrect appliance unplugging
Generation could interpret `unplugged` as disconnecting a cable from the TV/speaker body instead of removing the electrical plug from the wall outlet.

Current absolute rule:
- plug is removed from a **WALL-MOUNTED socket/outlet**
- appliance-side cord remains attached to appliance
- same cord ends in same loose wall plug
- wall socket remains empty
- unplugged state persists until explicit re-plug

For Chapter 1 TV, that state begins Strip 006 and persists through Strip 007 and final Strips 031–032.

### 2. Adjacent vertical-slice object / food disappearance
Generation could show food/noodles/chopsticks/props in vertical slice X and omit/reset them in X+1 without physical cause.

Current absolute rule:
- a camera cut does not erase objects
- occlusion is not disappearance
- food/noodle amount changes only through visible/physically unmistakable eating, slurping, lowering, spill, placement, or legal time cut
- hand/object/table states persist until visible change

### 3. Skipped simple physical mechanics
Generation could jump from intention to result without real movement: standing without chair mechanics, reaching distant props, object transfers without pickup/placement, cabinet already open, etc.

Current rule:
`START STATE → PHYSICAL CAUSE → VISIBLE ACTION → RESULT → PERSISTENT END STATE`.

### 4. Attached references treated too loosely
Generation could reinterpret reference-controlled identity/geometry/object design for composition convenience.

Current rule:
approved WebPs are binding authority. If intended shot conflicts with canon, recompose the shot; never modify canon.

### 5. Repetitive narration design
Narration could be forced into one repeated box regardless of event/function.

Current rule:
use one coherent publication family with scenario-driven variants for time/location, observation, procedural warning, investigation/evidence, ominous realization, and suspense/listening.

### 6. Reader-visible production labels
Generation could render `V-*` / V numbers at the top-left.

Current rule:
any V/P/strip/beat/panel/scene/shot/QA/layout production metadata in reader art—especially top-left—is an automatic rejection.

## Repair Scope

The following production authorities were hardened:
- `Production-Strips/README.md`
- `../../generation-workflow.md`
- `../../prompt-template.md`
- `../../production-readiness-gate.md`
- `../../lettering-sfx-guide.md`
- `../../vertical-scroll-layout-guide.md`
- `../../seam-continuity-protocol.md`
- `../../Object-References/core-object-bible.md`
- `../../Object-References/tv-canonical-reference-prompt.md`
- `../../Object-References/smart-speaker-canonical-reference-prompt.md`
- `chapter-01-master-scroll-prompt.md` deep-hardening binding note
- `chapter-01-generation-checklist.md`
- `chapter-01-strip-manifest.md`
- every individual `Production-Strips/strip-001` through `strip-032` prompt

## Individual Strip Rewrite Result

Every Strip 001–032 now includes or explicitly enforces:
- exact current WebP attachments
- attached-reference obedience
- no reader-visible production IDs
- START / ALLOWED CHANGE / END state ledger
- strip-specific micro-continuity
- physical character↔environment interaction rules
- scenario-appropriate narration/text-type handling
- expanded automatic rejection conditions

Story wording, speaker/source ownership, and Chapter 1 event order remain unchanged by the hardening pass.

## Clean-Room High-Risk Re-Audit

### Strips 001–004 — Entry / Mrs. Na / Key Route

Verified hardened:
- same move-in box crosses threshold before being placed
- Mrs. Na enters once and physically walks to counter
- one binder + one Unit 2407 key
- key visibly detaches from ordinary ring before counter placement
- binder stays counter
- key counter → Nari hand → entry tray
- time-cut narration is visually distinguished from ordinary observation
- no production labels allowed

**PASS at hardened prompt level.**

### Strips 005–007 — Chopsticks / Speaker / TV Wall-Unplug / Fridge / Key

Verified hardened:
- same chopstick pair established before fall
- same pair remains floor through Strip 006 V26 until explicit later time cut
- if any snack/food/noodles is shown, it cannot vanish between adjacent slices without physical change
- speaker unplug action targets wall-mounted socket; speaker-side cord remains attached
- TV starts away from Nari, requiring physical walk to outlet
- TV unplug action explicitly targets wall-mounted socket
- V30 physical proof requires TV active + TV-side cord attached + loose wall-end plug + empty wall socket
- Strip 007 inherits exact wall-unplug state with no silent re-plug
- key physically tray → hand → tray
- TV helpful and refrigerator hostile effect languages remain distinct

**PASS at hardened prompt level.**

### Strips 008–010 — Speaker Storage / Note / Digital Failure / Binder

Verified hardened:
- speaker counter → cabinet/stockpot by visible route
- same attached speaker cord + loose wall plug remain physically accounted for in storage
- one stockpot / one lid / exactly two towels
- note/pen remain same physical objects
- phone capture can fail without erasing real note
- same binder physically counter → pickup → open inspection → page state → close → counter
- Section 16 → Section 18 jump remains physical; no normal Section 17
- handwriting/device/phone/speech text systems remain distinct

**PASS at hardened prompt level.**

### Strip 011 — Blackout Inventory

Verified hardened:
- exactly two shopping bags on return
- exactly six emergency noodle packets
- practical blackout knife distinct from guarded fruit knife
- emergency tray remains right of keyboard

**PASS at hardened prompt level.**

### Strips 012–013 — Seungjae / Bag / Lobby

Verified hardened:
- Seungjae exactly 30 / same age group as Nari
- one phone / one watch / one pair earbuds / one umbrella
- Nari one shoulder bag
- tablet remains inside bag; no X-ray through closed bag; no tablet in hand
- entrance behind / elevator ahead after entry
- Seungjae turns toward exit only at V64

**PASS at hardened prompt level.**

### Strips 014–016 — Outage / Tools / Knife / Approach

Verified hardened:
- powered baseline visibly established before outage
- hallway lamp ON before actual supply loss
- Nari loose long dark-plum hair / wrist scrunchie preserved
- phone remains dark
- flashlight/radio hand tests physically accounted for
- knife remains sheathed until Strip 016
- knife draw leaves empty sheath at desk
- desk → hallway → kitchen route physically bridged
- Hyun-woo teaser only, seated in correct chair

**PASS at hardened prompt level.**

### Strips 017–018 — Eating / Noodles / Chopsticks / Mask

Verified hardened:
- same pot/noodle/chopstick/trivet/cloth/candle/pantry evidence persists across dialogue close-ups
- a visible noodle strand cannot simply disappear; bite/slurp/lowering must resolve it
- same attached technical mask clears mouth only enough to eat
- Strip 018 exact causal sequence:
  1. stop eating
  2. resolve any visible noodles
  3. same chopsticks leave mouth area
  4. chopsticks rest at/in same pot
  5. free hand reaches same mask
  6. same mask visibly reseats
  7. only then `TCHK`
- no position reset

**PASS at hardened prompt level.**

### Strips 019–022 — One Step / Chair / Crossing / Fridge / Candle

Verified hardened:
- exactly one cautious step in Strip 019 via weight shift → foot → packet `CRINKLE`
- new closer Nari position persists
- Strip 020 exact seated → chair push → `SKRRK` → stand mechanics
- pushed chair remains pushed
- Strip 021 physically bridges chair → around table → blocking position
- `YOON NARI` remains while `IDENTITY LOCKING` is added beneath it
- candle/holder stay fixed; no early reach

**PASS at hardened prompt level.**

### Strip 023 — Candle / Knife / Wrist Sequence

Verified the prompt now separates every physical state:
- V103: short realistic half-step/lean → `PFF`; candle out; knife still in hand
- V104: fridge `KIIIIII`; knife only starts loosening; no wrist contact
- V105: knife fully leaves fingers; hand empty
- V106: knife reaches one fixed floor spot → `CLANG`
- V107: only after impact, Hyun-woo catches one wrist
- candle does not move or relight
- knife floor spot becomes persistent authority

**PASS at hardened prompt level.**

### Strips 024–025 — Release / Power Return

Verified hardened:
- Strip 024 begins with same wrist still held
- visible wrist release occurs before refrigerator quiet-click sequence
- knife stays exact floor spot
- city power recovery occurs before Unit recovery
- Hyun-woo remains physical until Unit 2407 supplied power returns
- no visible fade/dissolve/portal/glitch disappearance
- power return does not clean/reset props

**PASS at hardened prompt level.**

### Strips 026–028 — Evidence / Phone / Cabinet / Speaker / Knife

Verified hardened:
- same phone physically desk → pickup → entry → archive/security → voicemail → counter
- two chimes originate from same still-closed cabinet
- Strip 028 exact approach → phone placement → kneel → cabinet open sequence
- same stockpot/lid/exactly two towels/unplugged speaker
- speaker-side cord remains attached; same loose wall plug remains stored/accounted for
- borrowed supernatural voice does not physically reconnect speaker
- knife remains exact old floor spot until visible handle pickup

**PASS at hardened prompt level.**

### Strips 029–030 — Knife Sheath / Food / Chair / Notebook

Verified hardened:
- same knife physically goes to same desk sheath before food
- Nari returns dining area empty-handed
- food is inspected before eating
- Nari sits in OTHER untouched chair through real chair/body mechanics
- clean Nari chopsticks remain distinct from Hyun-woo used pair
- one complete cautious noodle-bite path; food strand cannot vanish mid-action
- pot/food/chopsticks persist into dialogue
- first missing-section question receives no invented answer / ellipsis / SFX / narration
- notebook + one pen physically desk → same chair/table

**PASS at hardened prompt level.**

### Strips 031–032 — Notebook / Final TV Wall-Unplug State

Verified hardened:
- one physical notebook + one pen persist
- exact notebook handwriting preserved
- Nari remains same untouched chair
- TV remains physically unplugged FROM WALL since Strip 006
- TV-side cord remains attached
- same cord ends in loose plug
- wall-mounted socket remains empty
- hostile activation occurs despite physical wall disconnection
- `NEW TENANT CONFIRMED` only Strip 032
- one `FZZT` while Unit remains powered
- no Hyun-woo / second blackout / extra ending copy

**PASS at hardened prompt level.**

## Narration Re-Audit

The hardened package no longer treats narration as one fixed visual box.

Narration design is now explicitly scenario-driven while retaining one coherent publication family:
- neutral time/location
- ordinary/dry observation
- procedural warning
- investigation/evidence
- ominous realization
- suspense/listening/reveal restraint

Production is also explicitly forbidden from inventing narration to fill dead space or explain a physical transition that should be drawn.

**PASS at hardened instruction level. Actual typography remains to be visually inspected in new renders.**

## Production-Metadata Re-Audit

Every hardened strip and supporting guide now treats V/P/strip/beat/panel/scene/shot IDs as production-only.

Any top-left `V-*` or other technical label in actual art is an automatic rejection.

**PASS at hardened instruction level. Actual rendered images remain to be checked.**

## Attached Reference Re-Audit

All current strip attachment lists continue to use exact current WebP authorities. The hardening pass now says references are binding permanent visual authority rather than loose inspiration.

**PASS at prompt/reference-authority level.**

## Rendered Visual Status

The previous generated attempts are rejected for this retest and are not current continuity authority.

New Strip 001–032 artwork has not yet been generated/approved under the fully hardened package.

Therefore these gates remain **PENDING / UNEXECUTED**, not PASS:
- actual character identity fidelity
- actual environment/reference fidelity
- actual wall-socket rendering correctness
- actual adjacent-slice food/object micro-continuity
- actual narration typography quality/variation
- actual no-production-label compliance
- actual lettering/SFX placement
- actual seam/dead-space/mobile readability
- final stitched chapter audit

## Post-Hardening Gate Counts — Prompt / Preproduction Level Only

- **BLOCKER: 0**
- **MAJOR: 0 unresolved deterministic prompt/canon issues**
- **MINOR requiring correction: 0**
- **WARNING requiring explanation: 0**

These counts apply only to the current hardened textual/reference authority package. They do not certify any rendered strip.

## Final Current Verdict

**FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

Next production action:
1. generate a NEW Strip 001 using its exact hardened prompt and exact WebP attachments
2. deep-audit the actual pixels against all current gates
3. reject/fix/regenerate until Strip 001 passes
4. only then use it as APPROVED previous-strip authority for Strip 002
5. repeat sequentially through Strip 032
6. stitch and run a fresh final clean-room visual audit
