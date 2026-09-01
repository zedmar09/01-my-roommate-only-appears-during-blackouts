# Technical Strip Prompt Template

Use this structure for every active Manhwa production strip.

```text
Create exactly ONE tall full-color 2D manhwa TECHNICAL STRIP belonging to the same continuous chapter scroll.

CONTINUOUS-CHAPTER LOCK
This is not a page, episode, or reader-visible part.

PRODUCTION AUTHORITY
Use the current chapter beat plan/manifest and this strip's exact locked reader-facing script. Legacy source-archive files are historical reference only.
The binding global production rules in `Manhwa/style-guide.md`, `Manhwa/lettering-sfx-guide.md`, `Manhwa/seam-continuity-protocol.md`, `Manhwa/vertical-scroll-layout-guide.md`, and `Manhwa/generation-workflow.md` always apply even if not repeated below. This strip may make them stricter but may never loosen them.

INTERNAL READ BEATS
V##–V## are planning IDs only. Never render them.

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

REFERENCE PRIORITY
Current user instruction > story/current strip > approved character identity > approved environment geometry > approved object identity/state vocabulary > previous strip temporary state.

STRICT FLAT 2D HUMAN-DRAWN STYLE — ABSOLUTE
STRICT FLAT 2D HUMAN-DRAWN KOREAN MANHWA/WEBTOON ILLUSTRATION.
Clean intentional line art; flat colors; restrained simple hard-edged cel shading only; matte skin, hair, fabric, walls, floors, furniture, screens, appliances, and props; stable canonical anatomy/proportions; natural hands; mobile-readable silhouettes and composition.
DO NOT render photorealistic, semi-photorealistic, 3D/CGI/game-render, painterly, airbrushed, glossy/plastic/wet, beauty-ad shine, mirror-like, excessively specular, cinematic, depth-of-field blurred, bloom-heavy, rim-lit, lens-flared, heavily graded, hyper-textured, or AI-polished over-rendered art.
Blackout/candle/rain/device effects remain controlled flat shapes and contained accents, never room-flooding cinematic glow.
Never copy style drift from the previous strip.

SEAM IN
State G/A/E seam type and exact continuing anchors.

BLACK READ-SLICE DIVIDER — ABSOLUTE
Every DISTINCT vertical slice gets a SMALL BLACK GUTTER before the next distinct slice.
If two independent camera slices share one horizontal row, separate them with a DIAGONAL/SLANTED BLACK DIVIDER. No face, text, balloon, prop, or background crosses the slash.
The black divider is compact visual grammar, never huge dead space.
Do not insert a black bar at an A/E technical file boundary when artwork/effect must stitch continuously.

VERTICAL COMPOSITION
Use continuous Manhwa composition, not a printed-page grid. Every camera change must remain physically possible in the canonical environment.

REAL-SCENARIO CONTINUITY
Explicitly state character start/end positions, object routes, carried-object count/state, environment axes, lighting/power state, and any movement that must be visibly bridged.
Use CAUSE → ACTION → CONSEQUENCE for every physical state change.

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
List strip-specific continuity failures plus: wrong/missing/unapproved attachments, identity/environment/object drift, teleporting, duplicated props, wrong text ownership, unclear/unsupported SFX, missing black slice separators, merged side-by-side shots without diagonal divider, giant dead canvas, visible technical seam, or any violation of strict flat 2D human-drawn style.
```

After any correction, re-audit the corrected strip and both adjacent seams before approval. After the final strip, run a fresh clean-room visual audit of the stitched chapter rather than inheriting previous PASS labels.