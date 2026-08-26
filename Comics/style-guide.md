# Comics Style Guide

Use this file as the visual lock for generated comic pages.

## Color Production Rule

- The reusable KISAH front and back assets are compact colored flat 2D human-drawn promotional banners, not chapter covers or full-height comic pages.
- Interior comic pages are also colored flat 2D human-drawn modern supernatural romance manga/manhwa pages.
- Keep the story cover, promotional banners, and interiors visually related, but let each asset serve its purpose: the story cover identifies the series, the banners promote KISAH, and interior pages prioritize clear storytelling.

## Compact KISAH Promotional Banner Rule

- Format both reusable `front` and `back` assets as exact 1024 x 768 PNG banners in 4:3 landscape orientation. This is half the height of a 1024 x 1536 story page at the same width.
- The outer image boundary itself must be 1024 x 768. Never place the banner inside a portrait, square, long-scroll, full comic page, or full-height cover canvas, and do not add outer white margins.
- Do not show Nari, Hyun-woo, another character, a person, a face, a hand, a body, a human silhouette, or a character reflection on either support banner.
- Use one locked Unit 2407 appliance as the hero object on each banner: the matte cool-gray smart refrigerator on the front and the matte black television on the back.
- Keep backgrounds simple, flat, and promotional. Do not use hearts, flowers, rose petals, candles, wedding imagery, romantic scenery, hostile glitch effects, or character imagery.
- Keep both banners at one medium-bright neutral flat-color exposure with visible ink outlines, solid fills, and at most one hard-edged cel-shadow tone per surface. Do not use gradients, rim light, bloom, color grading, reflection streaks, glossy screens, dark cinematic exposure, or blown-out whites.
- Front text: `SUPPORT KISAH`, with optional smaller line `FOR MORE EXCITING LOVE STORIES.`
- Back text: `SUPPORT KISAH`, with optional smaller line `FOR MORE EXCITING LOVE STORIES.`
- Do not draw an actual website, browser, app interface, navigation bar, content card, QR code, URL, product screenshot, or fake logo.

## Colored Flat 2D Modern Supernatural Romance Manga Style Lock

- Format: colored flat 2D human-drawn modern Korean manga/manhwa page.
- Page feel: adult supernatural romantic comedy with modern mystery, matte modern apartment interiors, candlelit domestic intimacy, haunted smart-home glitches, rooftop city views, and sudden electrical horror.
- Linework: clean hand-drawn ink lines, expressive adult faces, strong silhouettes, consistent facial features, controlled line weight, and polished panel composition.
- Rendering: matte cel colors, simple controlled shading, clean color blocking, flat candle color, limited cool device text, dead-screen blacks, static texture, glitch borders, and faint pale blue-white electric accents.
- Global matte rule: apply the same flat 2D treatment to characters, objects, props, appliances, walls, floors, windows, screens, counters, furniture, city views, and backgrounds. Modern does not mean shiny. Use visible line art and clean color blocks for everything.
- No glossy or cinematic look: do not generate glossy webtoon shine, bloom, lens flare, dramatic film lighting, heavy gradients, photorealism, 3D render, painterly concept art, airbrushed skin, mirror-like reflections, glass glare, wet-looking floors, glossy counters, glossy refrigerator doors, plastic shine, or over-rendered reflective surfaces.
- Color-coded story elements stay consistent: Nari's hair is dark plum, her scrunchie is yellow, candlelight is warm matte amber, phone and device text is limited cool cyan-white, and Hyun-woo's tattoos use faint pale blue-white accents over matte black ink. These accents should not cast strong light across the room.
- Detail level: keep smart-home panels, refrigerator displays, phone screens, high-rise windows, instant noodle props, candles, tattoo patterns, and facial acting at consistent modern manhwa detail density.
- Avoid: school-life comedy, teen proportions, historical fantasy robes, palace half-masks, gothic coffins, corporate revenge debt boxes, loyalty percentage UI, supernatural train stations, coastal cartography motifs, chibi comedy, heavy gore, photorealism, 3D render, western superhero comics, muddy color palettes, glossy effects, cinematic effects, and unreadable text.

## Unit 2407 Environment And Appliance Master Lock

- Whenever Unit 2407 is visible, preserve one open-plan layout: living room and television on the left, dining table near the center, kitchen and refrigerator on the right, hallway and bedroom doors behind, and floor-to-ceiling windows along the exterior wall.
- Walls are flat light cool gray, lower cabinets are muted eucalyptus green, counters are matte pale gray, floors are medium neutral gray, the rectangular dining table is matte pale gray, and the two chairs are muted dark burgundy. Never change these colors merely to create mood.
- Smart refrigerator: 180 cm tall, matte cool-gray rectangular body, two upper doors, one lower freezer drawer, recessed dark handles, and one narrow black rectangular display on the upper-right door. No chrome, shine, reflective highlights, or alternate door arrangement.
- Television: 110 cm-wide matte black flat screen, thin uniform bezel, one small centered stand, and a low matte charcoal console. It is not reflective glass and must not mirror characters or the room.
- Smart speaker: 10 cm-tall screenless matte charcoal cylinder, one tiny cyan-white indicator on top, black power cord, and no words printed on its body.
- Cooktop: one fixed matte black two-burner gas cooktop with manual dark knobs on the kitchen counter. It can be lit with a match during a blackout; it has no glossy glass surface, digital display, or automatic redesign.
- Windows are matte dark panels with simple flat city-color dots. They never act as mirrors and never receive white glare streaks.
- Match approved previous-page references for character faces, room geometry, appliance shape, prop placement, line weight, palette, and the correct powered or blackout brightness state. Do not copy an earlier panel's action or dialogue into the new page.
- When a screen changes content, only the display content and scripted effect may change. The appliance body, dimensions, doors, handles, bezel, stand, color, room position, and camera-side orientation must stay unchanged.

## Lighting And Exposure Lock

- Use flat cel-color exposure, not cinematic exposure. Every object remains defined by ink outlines and solid color fills; lighting never replaces the line art.
- Powered baseline: use consistent medium-bright neutral interior colors. Light-gray walls remain light gray, eucalyptus cabinets remain readable, neutral-gray floors remain medium value, and faces keep natural flat skin colors. Do not overexpose white areas.
- Blackout baseline: use readable deep charcoal and muted blue-gray color blocks, not crushed black. Character silhouettes, appliance outlines, table edges, doors, and important props must remain visible through flat color separation. Candle amber stays small and local.
- Power-return transition: use one flat white panel accent without bloom, flare rays, halos, gradient wash, or reflected light. The next powered panel returns immediately to the powered baseline.
- Keep the same brightness across panels that share the same power state. Brightness may change only when the script explicitly turns power on or off, lights a candle, extinguishes it, or shows the power-return beat.
- Use at most one hard-edged cel-shadow tone per surface. No soft gradients, rim lighting, backlit halos, volumetric beams, lens flare, bloom, color grading, airbrushed shading, specular highlights, white reflection streaks, glossy skin, glossy hair, glossy appliances, glossy counters, reflective floors, or cinematic depth-of-field blur.

## Prompt Workflow

For new comic work, use the arc/season-first structure. Keep the prose chapter file and all comic production files inside this path shape:

```text
Comics/<NN-Arc-Or-Season-Name-In-Camel-Case>/README.md
Comics/<NN-Arc-Or-Season-Name-In-Camel-Case>/<Chapter-NN-Title-Of-The-Chapter-In-Camel-Case>/chapter.md
Comics/<NN-Arc-Or-Season-Name-In-Camel-Case>/<Chapter-NN-Title-Of-The-Chapter-In-Camel-Case>/page-###-chatgpt-image-prompt.md
```

Use the next arc or season number for each new arc, and use the prose chapter title in the chapter folder name. The arc/season `README.md` stores the readable arc title, synopsis notes, and chapter list. Do not add bare chapter-number folders directly under `Comics`.

The prompt must be self-contained so it can be copied into ChatGPT to generate the image. After approval and external conversion, save the final story-page WebP images in the chapter folder as `1.webp`, `2.webp`, `3.webp`, etc. Keep the reusable story cover and compact KISAH front/back promotional banners in `../Covers/` as `story_cover.webp`, `front.webp`, and `back.webp`, with their PNG source files beside them.

Use `prompt-template.md` as the reusable production template for new interior pages and KISAH promotional banners. Every new page prompt should include the environment/appliance master lock, lighting/exposure lock, local character consistency, setting/prop continuity, time-transition-card rule, spoiler boundary, panel order numbers, text rules, story clarity, and avoid-list blocks so it can stand alone when pasted into ChatGPT.

Early Arc 1 page prompts should not explain Hyun-woo's full origin, the complete Black Surge mechanics, body-restoration rules, memory-transfer cost, human culprit, late-arc titles, or climax logic. Keep those reveals in `../series-plan.md` or creator-only notes until the exact chapter earns them on-page.

## Panel Pacing Rule

Panel order and panel count can change when it improves supernatural romance pacing, blackout suspense, comedy timing, or readability. Prompts should define the required story beats and emotional progression, but the layout may rearrange panels as long as the blackout logic stays clear.

For blackout transitions, smart-home screen reveals, black surge effects, roommate appearances, emergency-noodle comedy beats, and chapter-ending danger clues, use fewer larger panels when stronger. A full-page splash, two-panel page, or one dominant reveal panel is allowed if it makes the reveal easier to feel.

Do not mechanically reuse the same page grid. Compose each page like a real manhwa page: apartment banter can use smaller timing panels, while supernatural surges, silence, and first-touch moments should breathe in larger panels.

## Object Scale And Spatial Logic

- Draw every prop at believable real-world scale relative to adult hands, bodies, furniture, doors, and rooms. Never enlarge a manual, key, phone, knife, candle, noodle pot, speaker, or notebook merely to fill a panel.
- Use camera distance and close-up framing to make a small object readable. A close-up changes the crop, not the object's physical size inside the story world.
- Default recurring dimensions: electrical manual is standard A4 size, about 30 x 22 cm and 3 cm thick; brass key is about 6 cm long; smart speaker is about 10 cm tall; stockpot is about 24 cm wide; practical knife is about 20 cm long; battery flashlight is about 15 cm long; candle is about 15 cm tall; noodle pot is about 18 cm wide; chopsticks are about 23 cm long; Nari's notebook is A5 size, about 21 x 15 cm.
- Keep Unit 2407 furniture at adult residential scale: counters about waist height, dining table about 100 x 70 cm, chair seats about knee height, refrigerator about 180 cm tall, and doors about 210 cm tall.
- Preserve object position between panels. If an object moves, show or clearly imply the character moving it. Hands must grip, place, carry, or release objects naturally; objects must not float, resize, or teleport.
- Dimensions are production guidance only. Never print measurements or scale labels in the generated artwork.

## Time, Entrance, And Flashback Rules

- Do not begin a new interaction after a location or character change without a visual bridge. Show the arrival, knock, door opening, entrance, walk, or an explicit establishing panel before the conversation begins.
- Every meaningful time jump must use a dedicated full-width time-card gutter before the resumed story panel. Reserve a quiet matte strip of blank space, separate from all story panels, with one centered uppercase caption such as `LATER THAT EVENING`, `ONE WEEK LATER`, `THE NEXT MORNING`, or `ON THE THIRTEENTH NIGHT`.
- A time-card gutter is not a story panel: do not give it a panel-order number, character, object, scenery, dialogue bubble, SFX, inset image, flashback picture, gradient, or decorative illustration. Resume the numbered story panels only after the strip.
- For a mid-page time jump, place the dedicated time-card gutter between the final panel of the old time period and the first panel of the new time period. Do not overlay the time caption on either panel.
- If a page directly continues the previous page without a time jump, do not insert a time-card gutter. State `NO TIME CARD` in that page prompt so the generator does not invent one.
- Chapter 1 is chronological and contains no flashback. Do not invent flashback panels, memory images, dream borders, or past-event inserts.
- If a future script explicitly requests a flashback, begin it with a readable time caption such as `THREE YEARS EARLIER`, use a thin double-line panel border and a muted flat-color overlay, and return to normal borders and full matte color when the present resumes. Never rely on color alone to communicate a flashback.


## Lettering Rule

The prompt may request readable speech bubbles, captions, SFX, device text, notebook text, and glitch text directly in the generated image. Keep dialogue and on-screen text short and uppercase so they have the best chance of rendering cleanly.

Blend lettering into the situation instead of placing it like random labels. Speech bubbles should be clean and easy to read. Captions should sit in quiet caption boxes. Device text should be centered inside screens or speaker-display areas. Notebook text should feel handwritten on the page. SFX should follow the motion or sound source: soft and small for object handling, rounded and playful for comedy, thin and jagged for electrical/static danger, and restrained for horror. Do not let any text cover faces, hands, recurring props, or clues.

For a screenless smart speaker, audible dialogue must use a normal speech bubble with its tail pointing to the speaker. Never print a sentence on the speaker body or squeeze it inside the tiny indicator light. Hyun-woo's speaker dialogue may use a restrained cyan outline or small clean static accent while keeping dark, high-contrast lettering readable.

Device text should usually be short, centered, and readable:

- Hyun-woo's device messages: clean, stable cool cyan-white lettering with minimal static and no crawling black pixels.
- Hostile system messages: stark white monospaced status lettering, broken or doubled glyph edges, crawling black pixels, or a distorted screen silhouette.
- The two signatures may appear before the reader knows why, but they must remain visibly different so mystery does not read as contradiction.

```text
OUR APARTMENT
```

```text
TENANT PROFILE: PENDING
```

```text
NEW TENANT CONFIRMED
```

```text
IDENTITY LOCKING
```

```text
STOP DOCUMENTING ME
```

Notebook text can be short and handwritten:

```text
UNIT 2407 BUG REPORT
```

```text
CRITICAL ISSUE 001: ROOMMATE BECOMES PHYSICAL ONLY DURING BLACKOUTS.
```

## Yoon Nari Visual Lock

Nari must stay consistent: Korean woman, 30 years old, medium height, slim but sturdy build, short asymmetrical dark-plum shag, sharp tired eyes, faint under-eye shadows, tiny beauty mark beside the left corner of her mouth, yellow scrunchie around one wrist, oversized graphic hoodie, cropped utility jacket, loose black trousers, canvas sneakers, and noise-cancelling headphones around her neck.

Her strongest recurring props are a sticker-covered tablet, pixel-ghost keychain, grocery-list notebook, emergency candles, and a practical knife. She should feel like an adult game designer: sleep-deprived, funny, observant, and stubborn.

Do not give her imperial robes, station uniform, red scarf, crescent hair clip, transparent umbrella mystery styling, cartographer coat, school uniform, or glamorous chaebol fashion.

## Joo Hyun-woo Visual Lock

Joo Hyun-woo, usually addressed as Hyun-woo, must stay consistent: tall Korean man appearing early-to-mid 30s, broad shoulders, long black hair tied low at the nape, severe dark eyes, matte black modern technical mask covering the lower half of his face, intricate circuit-sigil tattoos from neck down both arms and across collarbones, black sleeveless top, loose dark utility pants, worn boots, and old engineer's jacket when needed.

His tattoos should combine circuit traces, waveform lines, breaker symbols, and talisman-like brush geometry. In colored interior pages, they glow pale blue-white against matte black ink whenever power flickers or the entity pushes against him.

Do not make Hyun-woo look like an imperial half-mask prince, vampire, gothic warlord, corporate revenge lead, school delinquent, xianxia cultivator, or ordinary office worker.

## The Black Surge Visual Rules

- The entity should appear through devices and electrical effects rather than as a normal ghost.
- Use dead screens that turn on without power, black pixels crawling across matte dark screens, flat distorted screen silhouettes, waveform mouths, delayed camera feeds, static fingerprints, and glitch text.
- Its messages use the hostile system signature: stark white monospaced status text with broken or doubled glyph edges and crawling black pixels. Never render these messages with Hyun-woo's clean cyan-white device lettering.
- Its current marks may mimic Hyun-woo's tattoos, but they should move incorrectly and feel invasive.
- Electrical effects should be graphic and restrained: thin lines, small static marks, flat screen text, and faint cyan-white accents. Avoid neon glow, halos, glossy reflections, and cinematic light beams.
- Keep the entity readable as living electricity and memory hunger, not a demon, god, ordinary monster, or generic software interface.

## Smart-Home Comedy Rules

- Device behavior should be funny and readable before it becomes frightening.
- Use small panels for thermostat insults, smart-speaker misunderstandings, battery drain, and appliance pettiness.
- Keep Hyun-woo's jealousy comic when aimed at mild flirtation: dead phone, frozen smartwatch, elevator delay, hostile autocorrect.
- Shift to horror only when the device text names Nari, records her, or tries to open the south wall.
