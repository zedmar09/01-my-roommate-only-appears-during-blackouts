# ChatGPT Comic Prompt Template

Use this file when creating new page prompts or compact KISAH support banner prompts for `My Roommate Only Appears During Blackouts`.

The goal is consistency: each Markdown prompt should be self-contained enough to paste into ChatGPT, while still pointing back to `characters.md` and `style-guide.md` as continuity references.

## Interior Page Prompt Template

Copy this structure into each `page-###-chatgpt-image-prompt.md` file, then replace the bracketed placeholders.

````markdown
# Page ### ChatGPT Image Prompt

Copy and paste the prompt below into ChatGPT to generate Chapter [CHAPTER_NUMBER], Page [PAGE_NUMBER]. Ask ChatGPT to generate a PNG. Save the approved PNG as `[PAGE_NUMBER].png`, then manually convert it to `[PAGE_NUMBER].webp`. If the previous approved page PNG or WebP exists, attach it as the visual style reference.

```text
Create a colored flat 2D human-drawn modern supernatural romance manga/manhwa comic page for Chapter [CHAPTER_NUMBER], Page [PAGE_NUMBER] of "My Roommate Only Appears During Blackouts".

IMPORTANT REFERENCES
Use `../../../characters.md` and `../../style-guide.md` as continuity references. The prompt must still be self-contained because it may be pasted into ChatGPT without the full folder context. Match the approved previous page if one is attached.

STYLE TARGET - COLORED FLAT 2D MODERN MANGA/MANHWA
Use colored flat 2D human-drawn manga/manhwa rendering with clean ink linework, matte cel colors, simple controlled shading, readable lettering, and consistent adult character designs. Apply the same flat matte 2D treatment to every character, object, prop, appliance, wall, floor, window, screen, countertop, furniture piece, city view, and background element. Use clean color blocks with visible line art. Keep light sources small and contained: candlelight is warm flat amber, device text is limited cool cyan-white, city lights are simple flat dots, and Hyun-woo's tattoo/electric effects are faint pale blue-white accents, not strong glow. No glossy effect, no cinematic effect, no bloom, no lens flare, no photorealism, no 3D render, no painterly concept-art rendering, no airbrushed skin, no mirror-like reflections, no glass glare, no wet-looking floors, no glossy counters, no glossy refrigerator doors, no plastic shine, and no over-rendered shiny surfaces.

ENVIRONMENT AND APPLIANCE MASTER LOCK
Whenever Unit 2407 is visible, keep the living room and matte black television on the left, pale-gray dining table near center, kitchen and matte cool-gray refrigerator on the right, hallway behind, and dark-panel windows on the exterior wall. Walls are flat light cool gray, lower cabinets muted eucalyptus green, counters matte pale gray, floors medium neutral gray, and two chairs muted dark burgundy. Refrigerator: 180 cm tall, two upper doors, one lower freezer drawer, recessed dark handles, one narrow black display on the upper-right door. Television: 110 cm wide, thin uniform bezel, one centered stand, low charcoal console. Smart speaker: 10 cm-tall screenless charcoal cylinder with one tiny cyan-white top indicator and black cord. Cooktop: matte black two-burner gas cooktop with manual dark knobs, no glass shine, and no digital display; it can be match-lit during a blackout. Keep all appliance bodies, dimensions, colors, doors, handles, bezels, stands, knobs, room positions, and camera-side orientations unchanged. A screen-content change must not redesign the appliance. Match approved previous pages for faces, room geometry, props, palette, line weight, and the correct power-state exposure.

LIGHTING AND EXPOSURE LOCK
Use flat cel-color exposure with ink outlines and solid fills. Powered scenes use one consistent medium-bright neutral baseline. Blackout scenes use readable deep charcoal and muted blue-gray blocks, never crushed black; silhouettes, appliance outlines, furniture edges, doors, and key props remain visible. A power-return beat may use one flat white accent but no bloom or flare rays, then must return to the powered baseline. Brightness changes only when the script explicitly changes a light or power state. Use at most one hard-edged cel-shadow tone per surface. No gradients, rim light, halos, volumetric beams, lens flare, bloom, color grading, airbrushed shading, specular highlights, white reflection streaks, glossy skin or hair, glossy appliances or counters, reflective floors or windows, or cinematic depth-of-field blur.

CHARACTER CONSISTENCY
[ONLY INCLUDE CHARACTERS WHO APPEAR OR ARE VISUALLY IMPLIED ON THIS PAGE.]
Nari: Korean woman, 30, short asymmetrical dark-plum shag, tired sharp eyes with faint under-eye shadows, tiny beauty mark beside the left corner of her mouth, yellow scrunchie around one wrist, oversized hoodie, cropped utility jacket, loose black trousers, canvas sneakers, headphones around neck, sticker-covered tablet. Adult game designer, not a teenager.
Hyun-woo: tall Korean man, early-to-mid 30s, broad shoulders, long black hair tied low, severe dark eyes, matte black modern lower-face technical mask, black sleeveless top, loose dark utility pants, worn boots, and matte black circuit-sigil tattoos with faint pale blue-white accents from neck across collarbones and down both arms. Modern engineer silhouette, not historical fantasy.
Mrs. Na / Na Young-sook: older Korean woman late 60s, silver hair in a tight twist, square jade earrings, tailored mauve coat, neat gloves, analog wristwatch, physical key ring.
Im Seungjae: Korean man, 33, neatly styled brown hair, fashionable office-casual clothing, smartwatch, wireless earbuds, pristine foldable phone, practiced smile.

SETTING AND PROP CONTINUITY
[Name the exact location and must-keep props: Unit 2407 kitchen, hallway lamp, smart refrigerator, brass key, notebook, candle, noodle pot, tablet, phone, speaker, etc.]
[For recurring props, name the exact position and state: on the table, under the pillow, inside the lower cabinet, in Nari's hand, dropped on the floor, extinguished/smoking, open/closed, full/half-empty, plugged/unplugged.]

OBJECT SCALE AND SPATIAL LOGIC
Keep every object at believable real-world scale relative to adult hands, bodies, furniture, doors, and rooms. State the approximate dimensions of important recurring props. Use a camera close-up instead of physically enlarging an object. Preserve each object's established position and show or clearly imply any movement. Do not print dimensions or scale labels in the artwork.

CONTINUITY
[Summarize only what the reader already knows by this page. Keep it short and specific.]

TIME AND SCENE CONTINUITY
[State whether this page directly continues the preceding page or uses an explicit time/location jump. Show arrivals, knocks, entrances, or movement into a new location before dialogue begins. State whether the page is present-day chronology or an explicitly labeled flashback. Never let the image generator invent a flashback.]

TIME TRANSITION CARD
[For every time jump, reserve a dedicated full-width quiet matte gutter strip before the resumed story panel. Put only the centered uppercase time caption in that strip. It has no panel-order number, character, object, scenery, dialogue, SFX, inset image, gradient, or decoration. For direct continuity write: `NO TIME CARD - this page directly continues the previous page. Do not invent a transition strip.`]

SPOILER BOUNDARY
Do not add any future-arc explanation, culprit answer, or endgame logic unless this exact page has already earned that reveal in the script. For early Arc 1 pages, keep the threat as something in the electrical system, not a full explanation.

PAGE FORMAT AND PACING
Create one vertical manhwa page with [PANEL_COUNT] panels. [Describe pacing: comedy montage, tense reveal, intimate darkness, clipped horror beat, etc.] Panel sizes may vary for readability, but keep the reading order clear.

PANEL ORDER NUMBERS
Add small clean circled panel-order numbers inside the artwork: 1, 2, 3, etc. Place each number near the upper-left corner of its panel or in the gutter margin. Keep them readable but subtle, and do not cover faces, speech bubbles, SFX, hands, props, or key clues.

PAGE LAYOUT AND SCRIPT
PANEL 1 - [Clear visual description with character acting, camera distance, lighting, and key props.]
[Character/caption/SFX/device/notebook text label]:
[SHORT UPPERCASE TEXT]

PANEL 2 - [Clear visual description.]
[Character/caption/SFX/device/notebook text label]:
[SHORT UPPERCASE TEXT]

PANEL 3 - [Clear visual description.]
[Character/caption/SFX/device/notebook text label]:
[SHORT UPPERCASE TEXT]

[Add or remove panels as needed.]

SFX AND TEXT BLENDING
Use SFX only where the action benefits from it. Blend each SFX into the situation: small soft SFX for quiet object movement, rounded playful SFX for comedy, thin jagged SFX for electrical/static danger, and restrained hand-lettered SFX for horror. Keep SFX readable, flat 2D, and integrated into the panel art. Do not place SFX over faces, speech bubbles, hands, recurring props, or key clues.

TEXT AND LETTERING RULES
Use only the specified speech, caption, SFX, notebook, screen, and device text. Keep all generated text short, uppercase, readable, and placed inside speech bubbles, caption boxes, screens, notebooks, or SFX areas. Blend text with the panel mood and material: speech bubbles should feel clean and readable, screen text should sit inside a real device screen, notebook text should look handwritten on the page, and SFX should follow the motion or sound source. A screenless smart speaker's audible dialogue must use a normal speech bubble with its tail pointing to the speaker; never print a sentence on the speaker body or inside its tiny indicator. When a device carries Hyun-woo's voice, use a clean white speech bubble with a restrained cyan outline or clean stable cool cyan-white screen text, with minimal static and no crawling black pixels. When the hostile system speaks, use stark white monospaced status text with broken or doubled glyph edges and crawling black pixels. Do not add fake extra writing, author names, art credits, signatures, or watermarks.

STORY CLARITY
The reader must understand: [one sentence describing the required story beat for this page.]

AVOID
Avoid black-and-white-only output, grayscale interiors, glossy webtoon shine, shiny apartment surfaces, mirror-like reflections, glass glare, wet floors, glossy counters, glossy refrigerator doors, plastic shine, excessive glow, cinematic lighting, painterly concept art, photorealism, 3D render, heavy gradients, school uniforms, teenage proportions, palace robes, historical masks, gothic styling, corporate revenge visuals, loyalty percentage UI, debt boxes, station-lantern motifs, cartography motifs, chibi overreaction, heavy gore, unreadable text, fake extra text, author names, art credits, signatures, watermarks, large page numbers, and panel-order numbers placed over faces, speech bubbles, hands, props, or key clues.
```
````

## Chapter Support Banner Prompt Template

Use this structure for the reusable `../Covers/front-chatgpt-image-prompt.md` and `../Covers/back-chatgpt-image-prompt.md` files.

````markdown
# [Front KISAH Support Banner/Back KISAH Support Banner] ChatGPT Image Prompt

Copy and paste the prompt below into ChatGPT to generate the reusable compact [front/back] support banner. Ask ChatGPT to return the artwork itself as an exact 1024 x 768 landscape PNG. Save the approved PNG as `[front/back].png`, then manually convert it to `[front/back].webp`. Do not remove or replace any existing PNG or WebP until you approve the new one.

```text
SUPPORT PAGE COLOR RULE
This is a compact colored flat 2D human-drawn KISAH appliance promotional banner, not a story cover, not a full-height comic page, and not an interior comic panel. Use one locked story appliance and no characters.

Create a compact colored flat 2D human-drawn [FRONT SUPPORT BANNER/BACK SUPPORT BANNER] for KISAH readers.

PROMOTIONAL BANNER SIZE AND FORMAT
The delivered PNG itself must be exactly 1024 pixels wide by 768 pixels high in 4:3 landscape orientation. This is exactly half the height of a 1024 x 1536 vertical story page at the same width. The outer image boundary must be 1024 x 768. Never place a smaller banner inside a portrait, square, long-scroll, full-page, or full-height canvas. Return only the cropped 1024 x 768 banner artwork with no outer white margins.

IMPORTANT REFERENCES
Use the appliance and visual continuity of "My Roommate Only Appears During Blackouts" and the local `characters.md` and `style-guide.md` files when available. The prompt must still be self-contained if pasted alone.

STYLE TARGET - COLORED FLAT 2D SUPPORT PAGE
Use clean human-drawn line art, matte cel colors, simple controlled shading, restrained multi-color accents, and crisp promotional text hierarchy. Apply the same flat matte 2D treatment to the selected appliance, its screen/display, console if required, wall, floor, and one background accent. Use clean rectangular alignment inspired by a modern reading-site promotion, but do not draw an actual browser, website interface, or app screen. No glossy effects, no cinematic lighting, no bloom, no lens flare, no photorealism, no 3D rendering, no painterly concept-art rendering, no airbrushed shading, no mirror-like reflections, no glass glare, no glossy paper, no plastic shine, and no over-rendered shiny surfaces.

LIGHTING AND EXPOSURE LOCK
Use one consistent medium-bright neutral flat-color exposure across the entire banner. Keep the appliance, background, and promotional text clearly readable. Use at most one hard-edged cel-shadow tone per surface. No gradients, rim light, halos, volumetric beams, lens flare, bloom, color grading, airbrushed shading, specular highlights, white reflection streaks, dark cinematic exposure, blown-out whites, glossy appliance or screen treatment, reflective floors, or depth-of-field blur.

CHARACTER AND PROP CONTINUITY
[Do not show characters, people, faces, hands, bodies, human silhouettes, or character reflections.]
[FRONT: Use the locked matte cool-gray Unit 2407 smart refrigerator with two upper doors, one lower freezer drawer, recessed dark handles, and one narrow black display on the upper-right door.]
[BACK: Use the locked 110 cm-wide matte black Unit 2407 television with a thin uniform bezel and one small centered stand.]
[Keep the selected appliance at realistic size with no redesign, reflections, hostile glitch styling, or extra hero objects.]

SPOILER BOUNDARY
Do not add plot explanations, future-arc answers, threat forms, climax imagery, or story synopsis text. This banner is only a clean KISAH support or reader invitation.

SUPPORT PAGE COMPOSITION
[Describe an exact 1024 x 768 landscape composition with one locked appliance, one strong `SUPPORT KISAH` display, restrained flat promotional background visuals, and generous spacing. Keep it readable on a phone screen. Do not use panel borders, panel-order numbers, browser chrome, navigation bars, content cards, QR codes, URLs, or fake interface controls.]

SUPPORT PAGE TEXT
Use only this readable text:
[FRONT BANNER:]
SUPPORT KISAH
Optional smaller subtitle:
FOR MORE EXCITING LOVE STORIES.

[BACK BANNER:]
SUPPORT KISAH
Optional smaller subtitle:
FOR MORE EXCITING LOVE STORIES.

MOOD
[Describe 3-5 tone words: clean, modern, inviting, appliance-focused, confident, and reader-focused.]

AVOID
Avoid any outer canvas other than 1024 x 768, portrait or vertical output, square output, full-height page composition, a small banner floating inside a larger canvas, people, characters, faces, hands, bodies, human silhouettes, character reflections, multiple hero appliances, oversized appliances, appliance redesign, story-title cover layout, chapter title text, plot synopsis, hearts, flowers, rose petals, candles, wedding imagery, hostile glitch styling, black-and-white-only output, glossy webtoon shine, shiny surfaces, mirror-like reflections, glass glare, glossy paper, plastic shine, white highlight streaks, excessive glow, cinematic lighting, rim light, bloom, color grading, photorealism, 3D render, painterly concept art, browser UI, app UI, QR codes, URLs, fake logos, extra fake text, unreadable lettering, author names, art credits, signatures, watermarks, page numbers, and panel-order numbers.
```
````

## Required Prompt Blocks

Every interior page prompt should include these blocks in this order:

1. `IMPORTANT REFERENCES`
2. `STYLE TARGET - COLORED FLAT 2D MODERN MANGA/MANHWA`
3. `ENVIRONMENT AND APPLIANCE MASTER LOCK`
4. `LIGHTING AND EXPOSURE LOCK`
5. `CHARACTER CONSISTENCY`
6. `SETTING AND PROP CONTINUITY`
7. `OBJECT SCALE AND SPATIAL LOGIC`
8. `CONTINUITY`
9. `TIME AND SCENE CONTINUITY`
10. `TIME TRANSITION CARD`
11. `SPOILER BOUNDARY`
12. `PAGE FORMAT AND PACING`
13. `PANEL ORDER NUMBERS`
14. `PAGE LAYOUT AND SCRIPT`
15. `SFX AND TEXT BLENDING`
16. `TEXT AND LETTERING RULES`
17. `STORY CLARITY`
18. `AVOID`

Every shared support prompt should include:

1. `SUPPORT PAGE COLOR RULE`
2. `PROMOTIONAL BANNER SIZE AND FORMAT`
3. `IMPORTANT REFERENCES`
4. `STYLE TARGET - COLORED FLAT 2D SUPPORT PAGE`
5. `LIGHTING AND EXPOSURE LOCK`
6. `CHARACTER AND PROP CONTINUITY`
7. `SPOILER BOUNDARY`
8. `SUPPORT PAGE COMPOSITION`
9. `SUPPORT PAGE TEXT`
10. `MOOD`
11. `AVOID`

## Prompt Audit Checklist

Before pasting a prompt into ChatGPT, verify:

- The page says colored flat 2D human-drawn modern manga/manhwa.
- The page forbids glossy, cinematic, photorealistic, 3D, and painterly rendering.
- The page includes the exact Unit 2407 environment/appliance lock and preserves refrigerator, television, speaker, room-layout, and palette details.
- The page includes a fixed powered/blackout exposure rule and forbids gradients, rim light, bloom, color grading, reflection streaks, and unmotivated brightness shifts.
- Nari's dark-plum hair, yellow scrunchie, beauty mark, headphones, stickered tablet, and adult silhouette are preserved when she appears.
- Hyun-woo's black lower-face mask, low-tied long hair, matte circuit-sigil tattoos with faint pale blue-white accents, sleeveless dark clothing, and modern engineer silhouette are preserved when he appears.
- Hyun-woo is not physically drawn on pages where the script says he is voice-only after power returns.
- New recurring characters are added to `../characters.md` before final page prompts are generated.
- Every interior page includes small panel order numbers and says not to place them over faces, speech bubbles, hands, props, or clues.
- Dialogue, captions, SFX, notebook text, and device text are short, uppercase, and explicitly listed.
- SFX are included only when useful and the page includes `SFX AND TEXT BLENDING`.
- Recurring props keep exact position and state unless the script clearly moves or changes them.
- Every important prop has believable scale relative to adult hands and furniture; close-ups change camera framing rather than object size.
- Every character entrance and room change has a visual bridge.
- Every meaningful time jump has a dedicated unnumbered full-width time-card gutter before the resumed story panel; direct-continuation pages explicitly say `NO TIME CARD`.
- Flashbacks are never invented. When a future script explicitly uses one, it has both a written time caption and a distinct double-line border/muted-color treatment.
- The prompt does not reveal long-range mystery mechanics before the reader has earned them.
- The `STORY CLARITY` line names exactly what the reader must understand from the page.
