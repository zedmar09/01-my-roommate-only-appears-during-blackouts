# ChatGPT Comic Prompt Template

Use this file when creating new page prompts or compact KISAH support banner prompts for `My Roommate Only Appears During Blackouts`.

The goal is consistency: each Markdown prompt should be self-contained enough to paste into ChatGPT while still pointing back to `characters.md` and `style-guide.md` as continuity references.

## Interior Page Prompt Template

Copy this structure into each `page-###-chatgpt-image-prompt.md` file, then replace the bracketed placeholders.

````markdown
# Page ### ChatGPT Image Prompt

Copy and paste the prompt below into ChatGPT to generate Chapter [CHAPTER_NUMBER], Page [PAGE_NUMBER]. Ask ChatGPT to generate a PNG. Save the approved PNG as `[PAGE_NUMBER].png`, then manually convert it to `[PAGE_NUMBER].webp`. If the previous approved page PNG or WebP exists and the page depends on it, attach only that approved page as the scene-continuity reference.

```text
Create a colored flat 2D human-drawn modern supernatural romance manga/manhwa comic page for Chapter [CHAPTER_NUMBER], Page [PAGE_NUMBER] of "My Roommate Only Appears During Blackouts".

IMPORTANT REFERENCES
Use `../../../characters.md` and `../../style-guide.md` as continuity references. The prompt must still be self-contained because it may be pasted without full folder context. Character identity comes from approved canonical character references; the immediately previous approved page controls scene/object/environment continuity only.

STYLE TARGET - COLORED FLAT 2D MODERN MANGA/MANHWA
Use 100% flat 2D human-drawn colored manga/manhwa rendering with clean ink linework, matte cel colors, simple controlled hard-edged shading, readable lettering, and consistent adult character designs. Apply the same flat matte treatment to every character, object, prop, appliance, wall, floor, window, screen, countertop, furniture piece, city view, and background element. Keep light effects small and contained. No glossy effect, cinematic effect, bloom, lens flare, photorealism, 3D render, painterly concept-art rendering, airbrushed skin, mirror-like reflections, glass glare, wet-looking floors, glossy counters, glossy refrigerator doors, plastic shine, or over-rendered shiny surfaces.

ENVIRONMENT AND APPLIANCE MASTER LOCK
Whenever Unit 2407 is visible, keep the living room and matte-black television on the left, pale-gray dining table near center, kitchen and matte cool-gray refrigerator on the right, hallway behind, and matte dark-panel windows on the exterior wall. Preserve exact appliance bodies and locations. Refrigerator: two upper doors, one lower freezer drawer, recessed dark handles, narrow upper-right display. Television: thin uniform bezel, one centered stand, low charcoal console, nonreflective. Smart speaker: screenless matte-charcoal cylinder with tiny cyan-white indicator and black cord. Cooktop: matte-black two-burner gas cooktop with manual dark knobs. Match the approved previous page for geometry, props, subject positions, palette, line weight, and power state. A screen-content change must never redesign or relocate the appliance.

LIGHTING AND EXPOSURE LOCK
Use flat cel-color exposure with ink outlines and solid fills. Powered scenes use a consistent medium-bright neutral baseline. Blackout scenes use readable deep charcoal and muted blue-gray blocks, never crushed black. Candlelight remains small and local. A power-return beat may use one contained flat-white accent without bloom or flare; the next powered panel returns to neutral baseline. No gradients, rim light, halos, volumetric beams, lens flare, bloom, cinematic color grading, specular highlights, reflection streaks, glossy skin/hair/appliances/counters, reflective floors/windows, or depth-of-field blur.

POWER AND SUPERNATURAL RULE LOCK
Ordinary supplied building/grid power is different from supernatural current. After midnight, Hyun-woo can be physical only while Unit 2407 has lost ordinary supplied power. Switching off a mains lamp while supply still exists does not imitate an outage or create his body. A mains-powered household light satisfies Mrs. Na's powered-night rule; a phone screen does not. Battery devices can exist but may be drained/interfered with by the hostile system. A disconnected corded device may operate only briefly through effortful supernatural current. During an outage, visible screens and open flame can help the hostile system locate someone; local darkness temporarily denies it a visual target. When Unit 2407 power returns, show the power-on beat and then Hyun-woo already absent; never depict dissolution, particles, a portal, or a transformation.

CHARACTER CONSISTENCY
[ONLY INCLUDE CHARACTERS WHO ARE VISUALLY PRESENT OR EXPLICITLY REQUIRED ON THIS PAGE.]
Nari: Korean woman, 30, short asymmetrical dark-plum shag, tired sharp eyes, tiny beauty mark beside the left corner of her mouth, yellow scrunchie, adult game-designer silhouette and current scripted outfit.
Hyun-woo: tall Korean man, early-to-mid 30s, broad shoulders, long black hair tied low, severe dark eyes, matte-black modern lower-face technical mask, dark utility clothing, and the established dense matte-black circuit-sigil tattoo map with only faint restrained pale blue-white accents when scripted.
Mrs. Na: older Korean woman late 60s, silver hair in a tight twist, square jade earrings, tailored mauve coat, neat gloves, analog wristwatch, physical key ring.
Im Seungjae: Korean man, 33, neatly styled brown hair, fashionable office-casual clothing, smartwatch, wireless earbuds, pristine foldable phone.
Never attach or depict a character as a positive visual reference on a page where the script says they are voice-only or physically absent.

SETTING AND PROP CONTINUITY
[Name the exact location and all must-keep props.]
[For recurring props, state exact position and state: table/counter/entry tray/desk/cabinet/floor, open/closed, plugged/unplugged, lit/extinguished, sheathed/drawn, full/used, etc.]
[If anything moves, state who moves it, from where, to where, and in which panel.]

OBJECT SCALE AND SPATIAL LOGIC
Keep every object at believable real-world scale relative to adult hands, bodies, furniture, doors, and rooms. Use a close-up instead of physically enlarging an object. Preserve established positions and show or clearly imply movement. Objects must not float, duplicate, resize, clean themselves up, or teleport. Never print dimensions or scale labels in the artwork.

CONTINUITY
[Summarize only what the reader already knows by this page. Keep it short and specific.]

TIME AND SCENE CONTINUITY
[State whether this page directly continues the previous page or uses an explicit time/location jump. Show arrivals, walking routes, knocks, door openings, elevator/lobby transitions, or other visual bridges before dialogue begins. Never let the generator invent a flashback.]

TIME TRANSITION CAPTION
[For a meaningful time jump, place a LARGE, HIGH-CONTRAST uppercase narration caption inside the first establishing story panel of the new time period. Make it noticeable, not tiny. Do NOT create a separate blank time-card gutter or transition strip unless this exact page explicitly requests one. For direct continuity write: `NO TIME CAPTION - direct continuation. Do not invent a transition strip.`]

SPOILER BOUNDARY
Do not add future-arc explanation, culprit answers, endgame logic, Hyun-woo origin, Black Surge origin, restoration rules, memory cost, or climax content unless the exact page has earned it.

PAGE FORMAT AND PACING
Create one vertical manhwa page with exactly [PANEL_COUNT] panels when the script/checklist locks a count. Vary panel sizes only within that count to improve readability and pacing.

PRODUCTION PANEL LABELS
`PANEL 1`, `PANEL 2`, etc. below are prompt-production labels only. NEVER render panel numbers, circled numbers, page numbers, production labels, layout labels, or counting marks in the finished artwork.

PAGE LAYOUT AND SCRIPT
PANEL 1 - [Clear visual description with character acting, camera distance, lighting, position, and key props.]
[Character/caption/SFX/device/notebook label]: [SHORT UPPERCASE TEXT]

PANEL 2 - [Clear visual description.]
[Character/caption/SFX/device/notebook label]: [SHORT UPPERCASE TEXT]

PANEL 3 - [Clear visual description.]
[Character/caption/SFX/device/notebook label]: [SHORT UPPERCASE TEXT]

[Add/remove panels only to match the approved locked count.]

SFX AND TEXT BLENDING
Use SFX only where useful. Source-align every SFX to the correct physical event. Keep quiet object sounds small, electrical danger thin/jagged, and horror restrained. Do not place SFX over faces, speech bubbles, hands, recurring props, or key clues.

TEXT AND LETTERING RULES
Use only the specified speech, caption, SFX, notebook, screen, and device text. Keep generated text short, uppercase, readable, and exact—do not paraphrase or add filler. Speech belongs in bubbles, device text inside actual screens, notebook text on paper, and audible screenless-speaker dialogue in a speech bubble whose tail points to the hardware. Never print sentences on the speaker body or indicator. Hyun-woo/helpful device communication uses clean stable cool cyan-white treatment with minimal static and no crawling black pixels. Hostile communication uses stark broken/doubled white glyphs with crawling black pixels. Do not invent brands, logos, advertising, promotional Korean copy, fake slogans, prices, author names, credits, signatures, or watermarks.

STORY CLARITY
The reader must understand: [one sentence describing the exact required story beat.]

AVOID
Avoid black-and-white-only output, grayscale interiors, glossy webtoon shine, shiny apartment surfaces, mirror-like reflections, glass glare, wet floors, excessive glow, cinematic lighting, painterly concept art, photorealism, 3D rendering, strong gradients, teenage proportions, historical masks/robes, chibi overreaction, heavy gore, unreadable text, unscripted text, extra brands/logos, character identity drift, environment resets, object teleportation, reader-facing page numbers, reader-facing panel numbers, circled production numbers, and future spoilers.
```
````

## Chapter Support Banner Prompt Template

Use this structure for reusable `Covers/front-chatgpt-image-prompt.md` and `Covers/back-chatgpt-image-prompt.md` files.

````markdown
# [Front KISAH Support Banner/Back KISAH Support Banner] ChatGPT Image Prompt

```text
SUPPORT PAGE COLOR RULE
This is a compact colored flat 2D human-drawn KISAH appliance promotional banner, not a story cover, full-height comic page, or interior comic panel. Use one locked story appliance and no characters.

PROMOTIONAL BANNER SIZE AND FORMAT
The delivered PNG itself must be exactly 1024 x 768 in 4:3 landscape orientation with no outer white margin or larger surrounding canvas.

IMPORTANT REFERENCES
Use the appliance and visual continuity of "My Roommate Only Appears During Blackouts" and the local `characters.md` / `style-guide.md` when available.

STYLE TARGET - COLORED FLAT 2D SUPPORT PAGE
Use 100% flat 2D human-drawn colored manga/manhwa artwork with matte cel colors, controlled hard-edged shading, clean line art, restrained accents, and crisp promotional text. No glossy effects, cinematic lighting, bloom, lens flare, photorealism, 3D rendering, painterly rendering, mirror-like reflections, glass glare, glossy paper, or plastic shine.

LIGHTING AND EXPOSURE LOCK
Use one medium-bright neutral flat-color exposure. No gradients, rim light, halos, volumetric beams, bloom, color grading, reflection streaks, dark cinematic exposure, or blown-out whites.

CHARACTER AND PROP CONTINUITY
Do not show characters, people, faces, hands, bodies, silhouettes, or character reflections.
[FRONT: locked Unit 2407 refrigerator.]
[BACK: locked Unit 2407 television.]
Keep the appliance at realistic scale with no redesign, reflection, hostile glitch styling, or extra hero objects.

SPOILER BOUNDARY
Do not add plot explanations, future-arc answers, threat forms, climax imagery, or synopsis text.

SUPPORT PAGE COMPOSITION
[Describe exact 1024 x 768 landscape composition with one locked appliance and large `SUPPORT KISAH` typography. Do not use panel borders, production numbers, browser chrome, app UI, QR codes, URLs, or fake interface controls.]

SUPPORT PAGE TEXT
SUPPORT KISAH
Optional smaller subtitle:
FOR MORE EXCITING LOVE STORIES.

MOOD
[clean, modern, inviting, appliance-focused, confident, reader-focused]

AVOID
Avoid any canvas other than exact 1024 x 768, portrait/square output, people/characters, silhouettes/reflections, multiple hero appliances, appliance redesign, story-title cover layout, chapter-title text, plot synopsis, hearts/flowers/candles/wedding imagery, hostile glitch styling, glossy/cinematic/photoreal/3D/painterly rendering, browser/app UI, QR codes, URLs, fake logos, extra text, unreadable lettering, signatures/watermarks, page numbers, and panel numbers.
```
````

## Required Prompt Blocks

Every interior page prompt should include, in this order:

1. `IMPORTANT REFERENCES`
2. `STYLE TARGET - COLORED FLAT 2D MODERN MANGA/MANHWA`
3. `ENVIRONMENT AND APPLIANCE MASTER LOCK`
4. `LIGHTING AND EXPOSURE LOCK`
5. `POWER AND SUPERNATURAL RULE LOCK`
6. `CHARACTER CONSISTENCY`
7. `SETTING AND PROP CONTINUITY`
8. `OBJECT SCALE AND SPATIAL LOGIC`
9. `CONTINUITY`
10. `TIME AND SCENE CONTINUITY`
11. `TIME TRANSITION CAPTION`
12. `SPOILER BOUNDARY`
13. `PAGE FORMAT AND PACING`
14. `PRODUCTION PANEL LABELS`
15. `PAGE LAYOUT AND SCRIPT`
16. `SFX AND TEXT BLENDING`
17. `TEXT AND LETTERING RULES`
18. `STORY CLARITY`
19. `AVOID`

## Prompt Audit Checklist

Before pasting an interior prompt into ChatGPT, verify:

- Colored flat 2D human-drawn modern manga/manhwa is explicit.
- Glossy, cinematic, photorealistic, 3D, painterly, reflective rendering is rejected.
- Unit 2407/appliance geometry and the correct powered/blackout exposure are locked where applicable.
- Ordinary supplied power is distinguished from supernatural current.
- Required approved canonical character references are specified; absent/voice-only characters are not drawn.
- Previous approved page is used only for scene/object/environment continuity and never overrides canonical identity.
- Recurring props have exact positions/states and any movement is physically shown or clearly implied.
- Dialogue, captions, SFX, notebook text, and device text are copied exactly and remain short/readable.
- Hyun-woo/helpful device signature and hostile broken-white/black-pixel signature are visibly distinct.
- Every meaningful time jump uses a LARGE in-panel narration caption; no separate blank time-card gutter is invented unless explicitly requested.
- Direct-continuation pages do not invent a time caption or transition strip.
- `PANEL 1`, `PANEL 2`, etc. remain production labels only; NO reader-facing panel/circled/page numbers are rendered.
- Every entrance/location change has a visual bridge.
- No object, character, or environment teleports/resets without scripted movement.
- No unscripted brand/logo/advertising/promotional Korean/filler text is added.
- No future lore is revealed before the script earns it.
- `STORY CLARITY` names exactly what the reader must understand.
