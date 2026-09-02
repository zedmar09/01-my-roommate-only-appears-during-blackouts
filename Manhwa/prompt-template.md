# Technical Strip Prompt Template

Use this structure for every active Manhwa production strip.

```text
Create exactly ONE tall full-color 2D manhwa TECHNICAL STRIP belonging to the same continuous chapter scroll.

CONTINUOUS-CHAPTER LOCK
This is not a page, episode, or reader-visible part.

PRODUCTION AUTHORITY
Use current chapter beat plan/manifest + this strip's exact locked reader-facing script. Legacy source archives are historical only.
Binding global style/SFX/seam/layout/workflow rules always apply. Current strip may be stricter, never looser.

INTERNAL READ BEATS — PRODUCTION ONLY
V##–V## planning IDs only. Never render them.
Never render V/P/strip/beat/scene/panel/shot/QA/temporary-state metadata anywhere, especially top-left.

ATTACH — REQUIRED
List EVERY exact required visual reference:
- character canonical path(s)
- environment canonical path(s)
- object canonical path(s)
- previous approved strip for 002 onward
- current prompt
Do not infer attachments from another file.

REFERENCE AVAILABILITY — BLOCKING
Missing/stale/wrong-path/unapproved canonical → STOP. Never substitute improvised/rejected reference or Markdown prompt as visual canonical.

ATTACHED-REFERENCE OBEDIENCE — ABSOLUTE
Approved WebPs are binding permanent identity/geometry/object authority, not inspiration. Do not alter face/hair/build/accessories, room axis, fixed architecture/furniture/appliances, object body, cord/plug design, materials, proportions, orientation, hinges/handles, or recurring construction for composition convenience. Recompose shot; never redesign canon.

PREVIOUS-STRIP LIMIT — ABSOLUTE
Previous approved strip controls temporary story state only. It does not override permanent canon. Correct permanent previous-strip drift to attached canon while preserving legitimate temporary state.

DERIVED MICRO-DETAIL — WHEN NECESSARY / CANON-SUBORDINATE
If a required practical detail is not clearly visible in attached canon:
- exhaust floor plan/wides/details/object ref/angle atlas first
- derive ONLY smallest necessary detail inside existing canonical geometry
- do not add/move architecture/furniture/appliances
- detail is temporary chapter continuity, not permanent canon
- canonical always wins
- if conflict appears later, deliberately correct affected strip

REFERENCE PRIORITY
Current user instruction > story/current strip > approved character > approved environment > approved object > previous strip temporary state > canon-compatible derived micro-detail.

LEGAL TIME / LOCATION CUT — ABSOLUTE
State what the cut may legitimately change and what story-critical evidence must survive.
A time cut is not permission to erase evidence, duplicate objects, or reset canon.
If an ordinary object receives a new post-cut location, state that location explicitly.

START STATE — ABSOLUTE
List exact starting:
- character position/facing/pose/feet/hand occupancy
- worn accessories + anatomical side when relevant
- relevant object locations/states/counts/orientation/scale
- food/noodle/chopstick state
- cords/plugs/wall sockets/slack
- doors/cabinets/elevator mechanisms/hinges/handles
- chairs/table support geometry
- power/lighting/device display
- previous-strip seam state

ALLOWED CHANGES — ABSOLUTE
List only physical changes allowed. Anything not listed remains unchanged.

DETERMINISTIC SINGLE-MECHANISM — ABSOLUTE
If a continuity-critical action needs one physical solution, choose ONE authoritative mechanism. Do not give mutually incompatible alternatives that produce different hand/body/object states.

END STATE — ABSOLUTE
List exact state that persists into next strip. Camera change does not reset state.

MICRO-CONTINUITY — ABSOLUTE
Every object/body state persists slice X→X+1 unless visible/legal change occurs. Occlusion is not disappearance.
Track hands, feet, worn accessories, food/noodles, pot/bowls/chopsticks, packet/wrapper, cords/plugs/sockets, key/manual/note/pen/notebook, phone/tablet/bag/pockets, knife/sheath, candle, chair, cabinet/stockpot/lid/towels/speaker, facing/distance/depth/power/device state.

TEMPORARY ANATOMICAL-SIDE IDENTITY — WHEN APPLICABLE
When reverse-shot drift could break continuity, assign a production-only identity to the physical side at first clear action, e.g.:
- KNIFE HAND / PHONE HAND / WRITING HAND
- SCRUNCHIE WRIST
- STEP FOOT / CANDLE FOOT
- BAG SHOULDER / UMBRELLA HAND / PHONE POCKET
Preserve same anatomical side until visible transfer/release/expiry. Screen-left/right may reverse; body side may not. Never render the label.

WORN-ACCESSORY PERSISTENCE — WHEN APPLICABLE
If no removal/transfer is scripted, worn accessory remains on same body location. Partial occlusion is allowed; disappearance/side swap/duplication is not.

ORIENTATION / HINGE / HANDLE CONSERVATION — ABSOLUTE
Preserve physical orientation from canon/established state:
- door hinge side, handle/lock side, opening arc, interior/exterior face
- cabinet hinge/handle side and opening direction
- elevator/glass-door sliding vs swinging mechanism
- object front/back, appliance cord-origin side
- binder spine/rings/page-turn direction
- knife blade/handle/sheath-mouth orientation
- pot handle + cloth side
- chair front/back and pushed angle
Reverse shots may flip screen-left/right but not story-world mechanics.

OBJECT SCALE / FIT CONSERVATION — ABSOLUTE
Recurring objects keep stable world-space size/thickness.
Verify containers/surfaces actually fit contents without hidden resizing:
- speaker/cord/towels/lid must fit real stockpot/cabinet
- flashlight/radio/sheathed knife must fit emergency tray
- A5 notebook must fit tabletop zone at true scale
- pot/chairs/packets/devices retain scale across close-ups
Perspective may change apparent size; world-space scale may not.

DEPTH-ORDER / OCCLUSION / CONTACT PROOF — ABSOLUTE
2D overlap is not automatically physical contact.
For critical contact, show readable surface/contour relationship: fingers wrap/grip, foot shares floor plane with packet, body aligns with chair, hand truly holds wrist/handle/mask hardware.
A blocking character must be physically between protected character and threat in floor-plan space—not merely layered in front on the page.
Do not use foreground occlusion to fake contact or hidden relocation.

FLEXIBLE-OBJECT / GRAVITY / NO-CLIPPING — ABSOLUTE
Cords/plugs/towels/cloth/hair/straps/packets/paper/clothing obey support, gravity and collision.
- loose plug hangs/rests with believable slack; never floats
- cords do not pass through walls/stands/cabinets/counters/furniture/appliance bodies
- cord length/slack does not grow/shrink for convenience
- coiled cord/towels fit inside containers without solid-volume overlap
- falling props follow clear unobstructed paths
- loose surface props do not hover
Flat graphic simplification is allowed; broken physical topology is not.

PROP TOPOLOGY / RELATIVE PLACEMENT — WHEN APPLICABLE
List continuity-critical relative positions that cannot swap:
- pot/trivet
- cloth/handle side
- candle relative to pot/chair
- used/clean chopstick rest points
- packet/wrapper floor/table positions
- pushed chair angle
- knife impact point
- separate floor obstacles
- lid/towel/speaker arrangement/support plane
- notebook/table zone
Reverse shot may flip screen direction but NOT story-world sides/order.

REAL-SCENARIO CAUSALITY — ABSOLUTE
For every state change:
`START STATE → CAUSE → VISIBLE PHYSICAL ACTION → RESULT → PERSISTENT END STATE`.
Do not use camera cuts/SFX to hide movement, pickup, placement, step, reach, sit/stand, open/close, plug/unplug, drop/fall, or handoff.

MANDATORY ACTION-PROOF FRAMING — ABSOLUTE
Identify exact contact point and require visible action or immediately adjacent causal detail.
Examples:
- hand + plug body + wall socket
- hand + key + old/new surface
- blade + sheath mouth
- fingers + falling knife + impact location
- body + actual chair
- hand + cabinet handle/hinge
- reach/breath + candle
- fingers + bag opening + tablet inside
- foot + packet
Never crop decisive mechanism and jump to result.

SAME-OBJECT REPRESENTATION / INSERT — ABSOLUTE
A close-up/inset/device-screen/page/plug detail does NOT create another physical copy.
Same-moment wide/detail views must show compatible state of SAME object/person.
A later action slice may advance state exactly once.
Reject duplicate key/plug/phone/binder/knife/notebook/person caused by representational inserts.

CHARACTER ↔ ENVIRONMENT REALITY — ABSOLUTE
Verify feet/support, chair alignment, reachability, eyeline, hinge/track motion, walking route, collision clearance, floor obstacles, scale, depth order, truthful reverse angles. Never mirror room for convenience.

WALL-SOCKET RULE — WHEN APPLICABLE
Unless script explicitly specifies appliance-side detachable cable, `unplug` means:
- wall-mounted outlet target
- appliance-side cord remains attached
- fingers grip plug BODY
- hand removes plug from wall socket
- loose plug remains on same cord
- socket visibly empty afterward
- state persists until explicit re-plug
- action proves hand + plug + socket
- loose plug/cord obey gravity and do not clip through geometry
Reject appliance-side disconnect/cable pull/floating plug/impossible cord path.

LOCAL OUTLET CONTINUITY — CANON-SUBORDINATE
If canonical visibly establishes outlet, use exact. Otherwise derive smallest physically plausible placement inside canonical geometry; do not add/move architecture. Preserve chapter continuity after approval, but generated outlet detail never becomes permanent canon and never outranks WebPs.

LETTERING / BALLOON / SFX EVIDENCE SAFETY — ABSOLUTE
Reader-facing text must not cover/sever continuity proof:
- hand/foot/object contact
- plug/socket
- key transfer
- knife/sheath/fall/impact
- chair mechanics
- cabinet hinge
- candle action
- noodle/chopstick path
- packet action
- phone/notebook pickup/placement
- device/environment route clues
Reflow text/composition instead of hiding mechanism. Balloon tails must identify exact speaker.

STRICT FLAT 2D HUMAN-DRAWN STYLE — ABSOLUTE
Strict flat 2D human-drawn Korean manhwa/webtoon. Clean line art, flat colors, restrained hard-edged cel shading, matte materials, stable anatomy, natural hands, mobile readability.
NO photoreal/semi-photoreal, 3D/CGI, painterly, airbrushed, glossy, cinematic, DOF, bloom, rim light, lens flare, hyper-texture, AI-polished over-rendering.

NARRATION DESIGN BY SCENARIO — ABSOLUTE
Keep wording exact; treatment/placement follows beat function, not one repeated box/location.
Never mimic speech/device UI/handwriting/production labels. Do not default top-left. Never cover continuity evidence.

SEAM IN
State G/A/E seam and exact continuing anchors.

BLACK READ-SLICE DIVIDER — ABSOLUTE
Every DISTINCT vertical slice gets SMALL BLACK GUTTER.
Two independent views sharing one row get DIAGONAL/SLANTED BLACK DIVIDER. Nothing important crosses slash.
No giant filler band. No black bar at A/E technical boundary when artwork/effect continues.

VERTICAL COMPOSITION
Continuous manhwa composition, not page grid. Every camera change physically possible in canonical environment.

SCRIPT / SOURCE OWNERSHIP LOCK
List exact reader-facing lines/SFX/device/note text and source. Device text stays device; thoughts/narration do not become speech.

SFX PHYSICAL CHAIN — ABSOLUTE
SOURCE → ACTION → EXACT SOUND → TIMING → PLACEMENT → STATE CHANGE → NEXT-BEAT CONSEQUENCE.
No filler sounds.

NO DEAD BOTTOM — ABSOLUTE
No giant unused tail. Use existing art/environment/reaction/atmosphere/action/reveal timing or compact seam buffer. Never invent filler text/SFX.

SEAM OUT
Define exact state continuing into next strip.

AUTOMATIC REJECT IF
- wrong/missing/unapproved attachment
- attached-reference redesign
- previous/derived detail overrides canon
- illegal time-cut reset
- contradictory physical alternatives
- teleporting movement/object transfer
- adjacent-slice state disappears
- same-object insert creates duplicate/incompatible state
- anatomical side silently swaps
- worn accessory disappears/swaps
- hinge/handle/spine/track mechanism flips
- recurring object scale changes or container fit is faked by resizing
- contact is only ambiguous 2D overlap instead of physical contact
- depth order contradicts floor-plan blocking
- flexible object/cord/cloth clips through solids or floats against gravity
- cord slack/length changes impossibly
- prop topology swaps physical sides
- impossible reach/support/route/floor collision
- critical contact cropped/hidden
- lettering/SFX hides evidence
- appliance-side cable removed instead of wall plug
- outlet moved/reinvented against canon
- silent re-plug
- wrong text ownership
- any production/temp-state label appears
- narration generic/repetitive top-left
- unsupported SFX
- missing black/diagonal divider
- giant dead canvas
- visible technical seam
- strict flat 2D style violation
```

After any correction, re-audit corrected strip and both adjacent seams. After final strip, run fresh clean-room visual audit of stitched chapter instead of inheriting previous PASS labels.
