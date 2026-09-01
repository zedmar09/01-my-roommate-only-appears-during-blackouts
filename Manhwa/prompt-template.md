# Technical Strip Prompt Template

Use this structure for every active Manhwa production strip.

```text
Create exactly ONE tall full-color 2D manhwa TECHNICAL STRIP belonging to the same continuous chapter scroll.

CONTINUOUS-CHAPTER LOCK
This is not a page, episode, or reader-visible part.

PRODUCTION AUTHORITY
Use current chapter beat plan/manifest + this strip's exact locked reader-facing script. Legacy source archives are historical only.
Binding global rules in style/SFX/seam/layout/workflow always apply. Current strip may be stricter but never looser.

INTERNAL READ BEATS — PRODUCTION ONLY
V##–V## planning IDs only. Never render them.
Never render V/P/strip/beat/scene/panel/shot/technical metadata anywhere, especially top-left.

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
Approved WebPs are binding identity/geometry/object authority, not inspiration. Do not alter face/hair/build/accessories, room axis, fixed architecture/furniture/appliances, object body, cord/plug design, materials, or recurring construction for composition convenience. Recompose shot; never redesign canon.

PREVIOUS-STRIP LIMIT — ABSOLUTE
Previous approved strip controls temporary story state only. It does not override permanent canonical identity/geometry/object construction. Correct permanent previous-strip drift to attached canon while preserving legitimate temporary state.

DERIVED MICRO-DETAIL — WHEN NECESSARY / CANON-SUBORDINATE
If a continuity-critical practical detail is required but not clearly visible in attached canon—such as exact outlet faceplate or ordinary utensil storage:
- first exhaust attached floor plan/wides/details/object ref/angle atlas
- derive ONLY smallest necessary detail inside existing canonical geometry
- do not add/move wall, cabinet, counter, appliance, furniture, doorway, shelf, island, or other architecture
- choose physically plausible placement/function
- derived detail is temporary chapter continuity, NOT new permanent canon
- once approved, preserve it for current chapter continuity unless canonical explicitly resolves/supersedes it
- canonical always wins over derived detail
- if conflict appears later, deliberately correct affected strip; never silently propagate generated detail

Do not let production create new permanent architecture simply because a canonical image omitted a tiny functional detail.

REFERENCE PRIORITY
Current user instruction > story/current strip > approved character > approved environment > approved object > previous strip temporary state > canon-compatible derived micro-detail.

START STATE — ABSOLUTE
List exact starting:
- character position/facing/pose/feet/hand occupancy
- relevant object locations/states/counts
- food/noodle/chopstick state
- cords/plugs/wall sockets
- door/cabinet/chair state
- power/lighting/device display state
- previous-strip seam state

ALLOWED CHANGES — ABSOLUTE
List only physical changes allowed in this strip. Anything not listed remains unchanged.

END STATE — ABSOLUTE
List exact state that persists into next strip. Camera change does not reset state.

MICRO-CONTINUITY — ABSOLUTE
Every object/body state from slice X persists into X+1 unless visible action changes it. Occlusion is not disappearance.
Track hands, held objects, food/noodle amount, pot/bowl/chopsticks, chair, cords/plugs/sockets, key/manual/note/phone/tablet/bag, knife/sheath, candle, cabinet/stockpot/lid/towels, packet/wrapper, pen/notebook, body position, eyeline, distance.
A reaction close-up, reverse angle, gutter, diagonal split, or strip boundary never authorizes hidden reset.

TEMPORARY HAND IDENTITY — WHEN APPLICABLE
If a continuity-critical item remains in one hand across multiple slices/strips, assign a production-only hand identity at first clear action (for example `KNIFE HAND`) and preserve the SAME physical anatomical hand until a visible transfer/release occurs.
Reverse camera angles may flip screen-left/screen-right but may NOT swap the item to the other physical hand.
Never render the hand-identity label in artwork.

PROP TOPOLOGY / RELATIVE PLACEMENT — WHEN APPLICABLE
For continuity-critical local arrangements, explicitly list relative positions that must not swap:
- pot/trivet location
- cloth/handle side
- candle relative to pot/chair
- used/clean chopstick rest points
- packet/wrapper floor/table positions
- pushed chair angle/location
- knife impact point
- lid/towel/speaker positions

A reverse shot may change screen-left/screen-right but may NOT swap physical story-world sides/order. If an object is moved, require visible movement before topology changes.

REAL-SCENARIO CAUSALITY — ABSOLUTE
For every state change:
`START STATE → CAUSE → VISIBLE PHYSICAL ACTION → RESULT → PERSISTENT END STATE`.
Do not use camera cuts/SFX to hide movement, pickup, placement, step, reach, sit/stand, open/close, plug/unplug, drop/fall, handoff.

MANDATORY ACTION-PROOF FRAMING — ABSOLUTE
For every continuity-critical action identify exact contact point and require it visible in action slice or immediately adjacent causal detail.
Examples:
- hand + plug body + wall socket
- hand + key + old/new surface
- blade + sheath mouth
- fingers + falling knife + impact location
- body + actual chair
- hand + cabinet handle/hinge
- reach/breath + candle
- fingers + bag opening + tablet inside
- foot + packet before `CRINKLE`

Never crop decisive mechanism and jump to result. If mechanism cannot be shown clearly, change camera angle.

CHARACTER ↔ ENVIRONMENT REALITY — ABSOLUTE
Verify feet/support, chair alignment, reachability, eyeline, hinge motion, walking route, collision clearance, scale, and truthful reverse angles against attached environment. Never mirror room for convenience.

WALL-SOCKET RULE — WHEN APPLICABLE
Unless script explicitly specifies appliance-side detachable cable, `unplug` means:
- wall-mounted outlet is target
- appliance-side cord remains attached
- fingers grip plug BODY at wall
- hand removes plug from wall socket
- loose plug remains on same cord
- socket visibly empty afterward
- disconnected state persists until explicit re-plug
- unplug action visibly proves hand + plug + wall socket
Reject appliance-side disconnect or cable-pulling masquerading as unplugging.

LOCAL OUTLET CONTINUITY — CANON-SUBORDINATE
If attached canonical visibly establishes outlet, use exact canonical location.
If not visible:
- derive only smallest physically plausible outlet placement from already-canonical wall/counter/appliance geometry under DERIVED MICRO-DETAIL rule
- do not add/move architecture
- first correct approved depiction may freeze this micro-detail for current chapter continuity only
- same story-world wall/height/faceplate relation/furniture relation/cord-route family persists across later chapter shots
- this generated detail never becomes permanent canon and never outranks attached WebPs
- if later canonical evidence conflicts, canonical wins and affected strip is deliberately corrected

Reverse shots cannot move same outlet to another physical wall/height or invent a convenient socket.

STRICT FLAT 2D HUMAN-DRAWN STYLE — ABSOLUTE
Strict flat 2D human-drawn Korean manhwa/webtoon. Clean intentional line art, flat colors, restrained hard-edged cel shading only, matte materials, stable canonical anatomy/proportions, natural hands, mobile readability.
NO photoreal/semi-photoreal, 3D/CGI/game render, painterly, airbrushed, glossy/plastic/wet, beauty-ad shine, mirror-like specular, cinematic grading, DOF blur, bloom, rim light, lens flare, hyper-texture, AI-polished over-rendering.
Blackout/candle/rain/device effects stay controlled flat shapes/contained accents.
Never copy style drift from previous strip.

NARRATION DESIGN BY SCENARIO — ABSOLUTE
Keep wording exact; design caption treatment and placement according to beat function, not one repeated box/location.
Examples: time/location compact editorial; ordinary observation unobtrusive; warning utilitarian; investigation report-like; ominous realization sparse; suspense minimal footprint.
One coherent publication family. Never mimic speech/device UI/handwriting/production labels. Never cover continuity-critical evidence.
Do not default captions to top-left; legitimate story time captions may use upper area when compositionally appropriate but must not look like repetitive technical tags.

SEAM IN
State G/A/E seam and exact continuing anchors.

BLACK READ-SLICE DIVIDER — ABSOLUTE
Every DISTINCT vertical slice gets SMALL BLACK GUTTER.
Two independent camera slices sharing one row get DIAGONAL/SLANTED BLACK DIVIDER. Nothing important crosses slash.
No giant filler band. No black bar at A/E technical boundary when artwork/effect continues.

VERTICAL COMPOSITION
Continuous manhwa composition, not printed-page grid. Every camera change physically possible in canonical environment.

SCRIPT / SOURCE OWNERSHIP LOCK
List exact reader-facing lines/SFX/device/note text and source. Device text stays device; thoughts/narration do not become speech.

SFX PHYSICAL CHAIN — ABSOLUTE
SOURCE → ACTION → EXACT SOUND → TIMING → PLACEMENT → STATE CHANGE → NEXT-BEAT CONSEQUENCE.
No filler sounds.

NO DEAD BOTTOM — ABSOLUTE
No giant unused tail. Expand existing art/environment/reaction/atmosphere/action/reveal timing or compact seam buffer. Never invent filler text/SFX.

SEAM OUT
Define what continues into next strip.

AUTOMATIC REJECT IF
- wrong/missing/unapproved attachment
- attached-reference redesign
- previous-strip permanent drift propagated over canon
- derived micro-detail propagated over contradictory canonical
- identity/environment/object drift
- teleporting movement/object transfer
- adjacent-slice state disappears without cause
- critical hand silently swaps because camera reverses
- prop topology swaps physical sides because camera reverses
- impossible reach/support/route
- critical contact mechanism cropped/hidden
- appliance-side cable removed instead of wall plug
- cable pulled instead of plug body
- outlet detail moved/reinvented against canonical geometry
- generated outlet treated as permanent canon
- unplugged appliance silently replugged
- wrong text ownership
- any V/P/strip/beat/panel/scene/technical label appears
- narration generic/repetitive top-left tag
- unsupported SFX
- missing black divider/diagonal divider
- giant dead canvas
- visible technical seam
- strict flat 2D style violation
```

After any correction, re-audit corrected strip and both adjacent seams. After final strip, run fresh clean-room visual audit of stitched chapter instead of inheriting previous PASS labels.
