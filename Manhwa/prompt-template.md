# Technical Strip Prompt Template

Use this structure for every active Manhwa production strip.

```text
Create exactly ONE tall full-color 2D manhwa TECHNICAL STRIP belonging to the same continuous chapter scroll.

CONTINUOUS-CHAPTER LOCK
This is not a page, episode, or reader-visible part.

PRODUCTION AUTHORITY
Use the current chapter beat plan/manifest and this strip's exact locked reader-facing script. Legacy source-archive files are historical reference only.
The binding global production rules in `Manhwa/style-guide.md`, `Manhwa/lettering-sfx-guide.md`, `Manhwa/seam-continuity-protocol.md`, `Manhwa/vertical-scroll-layout-guide.md`, and `Manhwa/generation-workflow.md` always apply even if not repeated below. This strip may make them stricter but may never loosen them.

INTERNAL READ BEATS — PRODUCTION ONLY
V##–V## are planning IDs only. Never render them.
Never render `V##`, `V-##`, P-numbers, strip numbers, beat labels, scene labels, panel labels, or other technical metadata anywhere in the art, especially not at the top-left of a vertical slice.

ATTACH — REQUIRED
List EVERY exact visual reference required for this strip INSIDE this prompt:
- character canonical path(s)
- environment canonical path(s)
- object canonical path(s)
- previous approved strip for strip-002 onward
- current prompt
Do not force the production thread to infer visual attachments from another document.

REFERENCE AVAILABILITY — BLOCKING
If a listed canonical has not been generated and approved, STOP. Never substitute an improvised/rejected reference and never treat a reference-prompt Markdown file as an approved canonical image.

ATTACHED-REFERENCE OBEDIENCE — ABSOLUTE
Attached approved WebPs are binding identity/geometry/object-design authority, not inspiration. Do not alter face, hair, build, permanent accessories, room axis, fixed architecture/furniture/appliances, object body, cord/plug design, material identity, or recurring prop construction to improve composition. If the shot cannot fit canon, recompose the shot; never redesign the canon.

REFERENCE PRIORITY
Current user instruction > story/current strip > approved character identity > approved environment geometry > approved object identity/state vocabulary > previous strip temporary state.

START STATE — ABSOLUTE
List exact starting:
- character position/facing/pose/hand occupancy
- relevant object locations/states/counts
- food/noodle/chopstick state if present
- cord/plug/wall-socket state if present
- doors/cabinets/chairs open/closed/pushed state
- power/lighting state
- previous-strip seam state

ALLOWED CHANGES — ABSOLUTE
List only the physical changes that may occur in this strip. Anything not listed remains unchanged.

END STATE — ABSOLUTE
List exact state that must persist into the next strip. A camera change does not reset state.

MICRO-CONTINUITY — ABSOLUTE
Every object/body state from vertical slice X persists into X+1 unless a visible action changes it. Occlusion is not disappearance.
Track hands, held objects, food/noodle amount, bowl/pot/chopsticks, chair position, cords/plugs/sockets, key/manual/note/phone/tablet/bag, knife/sheath, candle, cabinet/stockpot/lid/towels, packet counts, pen/notebook, body position, eyeline, and distance.

REAL-SCENARIO CAUSALITY — ABSOLUTE
For every state change use:
START STATE → CAUSE → VISIBLE PHYSICAL ACTION → RESULT → PERSISTENT END STATE.
Do not use camera cuts or SFX to hide missing movement, pickup, placement, step, reach, sitting/standing, opening/closing, plugging/unplugging, drop/fall, or handoff mechanics.

CHARACTER ↔ ENVIRONMENT REALITY — ABSOLUTE
Verify feet/support, chair-body alignment, reachability, eyeline, door/cabinet hinge motion, walking route, collision clearance, object scale, and physically truthful reverse angles against the attached environment references. Never mirror a room to make a shot easier.

WALL-SOCKET RULE — WHEN APPLICABLE
If this strip says an appliance is unplugged, explicitly state whether the wall-end plug is removed. Unless the script explicitly specifies an appliance-side detachable cable, `unplug` means:
- wall-mounted outlet/socket is the target
- appliance-side cord remains attached
- hand removes plug from wall socket
- loose plug remains on same cord
- wall socket is visibly empty afterward
- disconnected wall-end state persists until explicit re-plug action
Reject appliance-side cable removal masquerading as unplugging.

STRICT FLAT 2D HUMAN-DRAWN STYLE — ABSOLUTE
STRICT FLAT 2D HUMAN-DRAWN KOREAN MANHWA/WEBTOON ILLUSTRATION.
Clean intentional line art; flat colors; restrained simple hard-edged cel shading only; matte skin, hair, fabric, walls, floors, furniture, screens, appliances, and props; stable canonical anatomy/proportions; natural hands; mobile-readable silhouettes and composition.
DO NOT render photorealistic, semi-photorealistic, 3D/CGI/game-render, painterly, airbrushed, glossy/plastic/wet, beauty-ad shine, mirror-like, excessively specular, cinematic, depth-of-field blurred, bloom-heavy, rim-lit, lens-flared, heavily graded, hyper-textured, or AI-polished over-rendered art.
Blackout/candle/rain/device effects remain controlled flat shapes and contained accents, never room-flooding cinematic glow.
Never copy style drift from the previous strip.

NARRATION DESIGN BY SCENARIO — ABSOLUTE
Keep narration wording exact, but design its caption treatment according to the beat's function and situation rather than using one identical box style throughout the chapter.
Examples: neutral time/location = compact editorial; ordinary observation = unobtrusive; warning/procedure = firmer utilitarian; investigation/evidence = report-like; ominous realization = sparse higher-contrast; suspense/listening = minimal footprint.
Narration must remain within one coherent publication typography family and must never imitate speech balloons, device UI, handwritten notes, or production labels. Never cover faces, hands, food continuity, plug/socket evidence, or key clues.

SEAM IN
State G/A/E seam type and exact continuing anchors.

BLACK READ-SLICE DIVIDER — ABSOLUTE
Every DISTINCT vertical slice gets a SMALL BLACK GUTTER before the next distinct slice.
If two independent camera slices share one horizontal row, separate them with a DIAGONAL/SLANTED BLACK DIVIDER. No face, text, balloon, prop, or background crosses the slash.
The black divider is compact visual grammar, never huge dead space.
Do not insert a black bar at an A/E technical file boundary when artwork/effect must stitch continuously.

VERTICAL COMPOSITION
Use continuous Manhwa composition, not a printed-page grid. Every camera change must remain physically possible in the canonical environment.

SCRIPT / SOURCE OWNERSHIP LOCK
List exact reader-facing lines/SFX/device/note text and who/what owns each one. Device text stays on its device; thoughts/narration do not become speech.

SFX PHYSICAL CHAIN — ABSOLUTE
For every scripted sound verify:
SOURCE → PHYSICAL ACTION → EXACT SOUND → EXACT TIMING → VISUAL PLACEMENT → STATE CHANGE → NEXT-BEAT CONSEQUENCE.
Do not invent filler footsteps, ambience, impacts, or device sounds.

NO DEAD BOTTOM — ABSOLUTE
Do not leave a giant unused black/white/neutral tail. Expand existing art/environment/reaction/atmosphere/action/reveal timing or use a compact seam buffer. Never invent filler text/SFX.

SEAM OUT
Define what continues into the next technical strip.

AUTOMATIC REJECT IF
List strip-specific continuity failures plus:
- wrong/missing/unapproved attachments
- any attached-reference redesign
- identity/environment/object drift
- teleporting movement or object transfer
- adjacent-slice object/food/hand state disappearing without cause
- impossible reach/body support/room route
- appliance-side cable removed when the story requires unplugging from a wall socket
- unplugged appliance silently plugged back in
- wrong text ownership
- any V/P/strip/beat/panel/scene/technical label appears in art
- narration forced into one generic repeated design regardless of scenario
- unclear/unsupported SFX
- missing black slice separators
- merged side-by-side shots without diagonal divider
- giant dead canvas
- visible technical seam
- any violation of strict flat 2D human-drawn style
```

After any correction, re-audit the corrected strip and both adjacent seams before approval. After the final strip, run a fresh clean-room visual audit of the stitched chapter rather than inheriting previous PASS labels.
