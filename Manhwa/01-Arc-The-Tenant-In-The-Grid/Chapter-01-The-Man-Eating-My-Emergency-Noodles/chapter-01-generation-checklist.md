# Chapter 1 Manhwa Generation Checklist

Status: **SECOND FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

A second clean-room `manhwa-2d-production-auditor` pass was completed from Strip 001 through Strip 032. The first hardening PASS was not accepted as proof. This second pass searched specifically for remaining wording that could still let image generation skip physical mechanisms, invent non-story props, propagate permanent drift from the previous strip, reuse ambiguous object states, or fall back to repetitive top-left caption/tag behavior.

## Second-Pass Findings That Required Additional Repair

1. **Critical actions could still be described without requiring the decisive contact point to be visible.**
   - Added mandatory action-proof framing: plug/socket, key pickup/placement, blade/sheath, knife release/fall/impact, chair/body, cabinet handle/hinge, candle reach/blow, bag opening/tablet, phone pickup/latch, and similar state-changing contacts.

2. **Previous-strip artwork could still be read as co-equal with permanent canon.**
   - Clarified that previous approved strip controls temporary story/seam state only. Permanent face/hair/body/room/socket/appliance/object construction always returns to attached canonical WebPs if prior art drifted.

3. **Strip 001 did not prove the smart-lock/door entry mechanism strongly enough.**
   - Now requires smart-lock contact → `BEEP` → latch release → physical door opening → threshold crossing with the same box.

4. **Strip 003 allowed conceptual phone/tablet inserts that could become floating UI or ungrounded props.**
   - Removed that freedom. The phone/tablet warning is spoken dialogue; safest/default visual is the real hallway lamp + characters only.

5. **Strip 004 key route still allowed pickup/placement to be hidden by montage framing.**
   - Now requires visible counter pickup contact, empty old location, same-key carry, tray contact/release, and `CLINK` at tray.

6. **Strip 005 still invited unnecessary visible food/snack imagery.**
   - Visible food/noodles/bowl/packet are now forbidden. Only the scripted chopstick pair is established and tracked into Strip 006.

7. **Strip 015 left failed flashlight/radio end positions ambiguous.**
   - Now requires flashlight test → exact tray return → radio test → exact tray return; knife remains untouched. Strip 016 starts from those exact positions.

8. **Strip 016 knife draw needed deterministic tool handoff from Strip 015.**
   - Flashlight/radio stay exact tray positions while only the sheathed knife is reached, lifted, visibly drawn, and leaves empty sheath behind.

9. **Strip 023 hand/ear/knife/wrist biomechanics were still too open.**
   - Free hand goes toward one ear; knife hand reflexively rises toward the other ear and loses grip; same former knife-hand wrist is caught only after `CLANG`.

10. **Strip 024 did not lock the exact wrist identity strongly enough.**
    - It now begins with that same former-knife-hand wrist held and requires visible same-wrist release before refrigerator clicks.

11. **Strip 026 preserved TV wall-unplug evidence without attaching the TV object canonical.**
    - TV canonical is now attached; any visible TV/cord state must match it plus the persistent loose-plug/empty-wall-socket state.

12. **Strip 030 carries the TV state into the final activation without previously attaching TV object authority.**
    - TV canonical is now attached to lock body/cord/socket continuity into Strips 031–032.

13. **Strip 031 treated final wall-unplug proof as optional/framing-dependent.**
    - Now mandatory: same-moment active TV plus causally adjacent proof of TV-side cord attached, same loose plug, and empty wall socket.

14. **Strip 032 needed explicit inheritance of the proven Strip 031 state.**
    - Final reveal may not reinterpret or silently reconnect the TV; if plug zone is off-frame, the already-proven wall-disconnected state remains binding.

## Prior Generated Strip Attempts — REJECTED AS AUTHORITY

Do not reuse pre-hardening or first-pass generated artwork as `APPROVED Strip N` for the new production run unless it is freshly re-audited against the current second-pass gates and actually passes. The intended retest starts from **new Strip 001**.

Only a strip generated under the current second-pass hardened package and passing current visual QA may become temporary continuity authority for the next strip.

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

Every current Strip 001–032 prompt additionally contains strip-specific hardening. A global rule cannot weaken a stricter strip rule.

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
- `Manhwa/Environment-References/Unit-2407/unit-2407-room-angle-atlas-reference.webp` when an intended camera angle is not sufficiently covered by primary views

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
- propagates previous-strip permanent drift against canonical WebPs

If a camera/action does not fit attached canon, **recompose the shot**. Never rewrite canon to fit the shot.

## Previous-Strip Authority Gate — Absolute

Previous approved strip controls temporary state only: pose, facing, held items, temporary prop placement, food amount, open/closed state, chair pushed state, current lighting/power, and seam composition.

It does NOT override permanent face, hair, body proportions, architecture, wall-socket location, furniture/appliance body, or recurring object construction.

## START / ALLOWED CHANGE / END State Gate — Absolute

Every hardened strip explicitly defines or enforces:
1. START state inherited from approved prior strip or legal cut
2. only the scripted ALLOWED changes
3. persistent END state for next strip

Anything not explicitly changed remains unchanged. Camera cut, reverse angle, close-up, black gutter, or technical file boundary is not a reset.

## Mandatory Action-Proof Gate — Absolute

For each continuity-critical state change, verify the mechanism/contact point is actually shown.

Required examples:
- smart-lock / door operation
- key pickup / placement
- plug body / wall socket
- blade / sheath mouth
- knife fingers / fall / impact
- body / chair during sit/stand/push-back
- cabinet handle / hinge
- candle reach / blow
- bag opening / tablet physically inside
- phone pickup / latch contact
- notebook pickup / same-chair return

Reject a result shown only through SFX, reaction, narration, or later state if the physical mechanism is important.

## WALL-SOCKET Unplugging Gate — Absolute

Unless script explicitly states otherwise, `UNPLUGGED` means:
- electrical plug removed from **WALL-MOUNTED socket/outlet**
- appliance-side cord remains attached to appliance body
- fingers grip plug BODY rather than pulling cable
- same cord ends in same loose wall plug
- wall socket remains empty
- disconnected wall-end state persists until explicit re-plug action
- critical unplug action visibly shows hand + plug + wall socket

Reject appliance-side disconnect, cable-pulling, hidden socket action, moved socket, missing loose plug, cord redesign, or silent re-plug.

Chapter 1 hard lock:
- Strip 006 speaker unplugged FROM WALL
- Strip 006 TV unplugged FROM WALL
- Strip 007 inherits exact loose plug + empty wall socket
- TV remains physically unplugged until final Strips 031–032 activation
- Strip 031 must visibly prove active TV + TV-side cord attached + loose plug + empty wall socket in same moment
- stored speaker remains unplugged with attached cord + loose plug physically accounted for inside stockpot/towel state

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

## Character ↔ Environment Physical Gate — Absolute

Verify:
- feet/body support
- seated body matches actual chair seat/back
- reach distance plausible
- eyeline points to real target location
- door/cabinet motion respects hinges/walls
- walking path respects canonical circulation
- bodies do not pass through furniture/appliances/walls
- scales match references
- reverse angles are derivable from floor plan, never mirrored for convenience

## Narration Design Gate — Scenario-Driven

Narration wording is locked but visual treatment **and placement** must follow scenario/function instead of one repeated design.

Allowed coherent variants:
- time/location transition → compact editorial
- ordinary observation / dry comedy → restrained unobtrusive
- warning / procedural → firmer utilitarian
- investigation / evidence → report-like
- ominous realization → sparse higher-contrast
- suspense / listening / reveal → minimal footprint

Reject narration that:
- uses one generic identical box everywhere regardless of function
- repeatedly defaults to small top-left tag placement across strips
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

## Second-Pass High-Risk Handoffs

- 001→002: smart-lock/door entry physically proven; Unit canon persists
- 003→004: no invented conceptual phone/tablet inserts; binder/key stay counter
- 004→005: key visibly transferred to tray; binder counter; speaker plugged
- 005→006: one chopstick pair only; no invented visible food; same floor spot through V26
- 006→007: TV-side cord attached; loose wall plug; empty wall socket; no silent re-plug
- 014→015: blackout and exact desk/tool states persist
- 015→016: flashlight/radio returned to exact tray positions; sheathed knife untouched until draw
- 023→024: same former-knife-hand wrist caught after `CLANG`, then same wrist visibly released
- 025→026: TV remains wall-unplugged; TV canonical attached if visible as evidence
- 029→030: TV state remains wall-unplugged; TV canonical attached before final sequence
- 031→032: Strip 031 visually proves active TV + loose plug + empty wall socket; Strip 032 cannot reinterpret/replug

## Strict Flat 2D Human-Drawn Style Gate — Absolute

Actual rendered pixels must visibly satisfy current style guide. Prompt wording alone cannot pass this gate.

## Current Second-Pass Gate Counts

At **prompt / preproduction authority level** after the second clean-room audit and repairs:
- **BLOCKER: 0**
- **MAJOR: 0 unresolved deterministic prompt/canon issues**
- **MINOR requiring correction: 0**
- **WARNING requiring explanation: 0**

These counts do **not** certify rendered strips. New Strip 001–032 images still require sequential actual-pixel QA under this second-pass package.

## Current Verdict

**SECOND FULL HARDENED PREPRODUCTION GATE PASS — READY TO RETEST FROM STRIP 001 — NOT PRODUCTION COMPLETE**

Next action: generate a **new Strip 001**, deep-audit actual pixels against every second-pass gate, repair/regenerate until it passes, then move sequentially to Strip 002.
