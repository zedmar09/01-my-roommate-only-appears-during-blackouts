# Chapter 01 Image Generation Checklist

Status: **PASS — PRE-GENERATION GUARD READY**

This checklist is the production guard for the final locked Chapter 1 interior sequence: **Pages 001–018**.

## Image-Only Execution Rule — Applies To Pages 001–018

Every Chapter 1 page prompt is already a FINAL production instruction. During image generation:

- Do **not** rewrite, summarize, paraphrase, reinterpret, improve, reorganize, or re-block the page production prompt before generating.
- Do **not** substitute a more generic comic action for the specific scripted action.
- Do **not** invent alternate poses, movements, prop interactions, transitions, dialogue, captions, SFX, device text, notebook text, character motivations, or environment changes.
- Do **not** change panel sequence, panel count, subject position, object position, movement route, lighting/power state, or scene geography unless the current page prompt explicitly requires that change.
- Treat wording such as `hears`, `looks`, `opens`, `walks`, `places`, `picks up`, `remains`, `does not move`, `voice-only`, and `physically absent` literally.
- If a production instruction seems unusual, execute the written instruction rather than “correcting” it into a conventional pose or action.
- The only creative freedom is the drawing/composition necessary to realize the locked script without changing its meaning.
- After reading the page prompt and references, **generate the comic image directly**. Do not output a rewritten production prompt, revised script, explanation, alternate plan, or pre-generation summary in place of the image.

This rule governs **every Page 001–018 generation**, including pages whose individual Markdown does not repeat this block verbatim.

## Script Immutability Rule — ABSOLUTE — Applies To Pages 001–018

The script already written in each `page-###-chatgpt-image-prompt.md` is FINAL production canon. Production has ZERO authority to rewrite it.

For every Page 001–018:

- Reproduce every scripted reader-facing line **verbatim**.
- Do not rewrite, paraphrase, shorten, expand, improve, simplify, correct, translate, censor, summarize, merge, split, reorder, duplicate, omit, or invent text.
- Preserve exact spelling, capitalization, punctuation, ellipses, dashes, numbers, timestamps, wording, and line order.
- Preserve the exact **panel assignment** of every line.
- Preserve the exact **speaker/source attribution** of every line.
- Preserve the exact **text type**: dialogue stays dialogue; narration stays narration; thought stays thought; SFX stays SFX; device/screen text stays on the specified device/screen; printed object text stays on that object; handwriting stays handwriting; messages stay messages; notebook text stays notebook text.
- Never move a line from one character to another, from dialogue to narration, from a device to a speech bubble, from narration into dialogue, or between panels.
- Never add filler dialogue, explanatory narration, extra SFX, extra labels, unscripted reactions, or “helpful” text.
- If the generator cannot render the exact scripted text correctly, the image is **REJECTED**. Approximate or “close enough” text is not acceptable.
- A production image is not allowed to become continuity reference if ANY scripted text, source, panel, or text type is changed.

This rule applies even when an individual page already contains `TEXT AND LETTERING RULES`, `Locked Reader-Facing Text`, or `IMAGE-ONLY EXECUTION LOCK`. Those sections reinforce this global rule; they do not weaken it.

## Dialogue / Callout Attribution Rule — ABSOLUTE — Applies To Pages 001–018

Dialogue ownership is part of the script, not optional graphic styling.

For every dialogue panel in Chapter 1:

- Every spoken line must visually belong only to the exact scripted speaker.
- Every speech-bubble tail/callout must point unmistakably to the correct speaking character or exact scripted audio source.
- Never point a tail between two characters or toward an ambiguous shared space.
- Never cross two speakers' bubble tails in a way that makes ownership unclear.
- Never merge dialogue from different speakers into one bubble.
- Never attach one speaker's line to another speaker's bubble.
- When two or more characters speak in one panel, keep each bubble on/near that speaker's side where possible and preserve the exact scripted reading order.
- Consecutive lines from the SAME speaker may use connected bubbles only if the source remains unmistakable and exact wording/order remains unchanged.
- Narration, thought captions, SFX, device text, object text, handwriting, messages, and notebook text must not receive a character speech-bubble tail unless the page explicitly defines an audible source.
- Screenless-speaker dialogue must point to the actual speaker hardware when the page says the voice comes through that device.
- Voice-only/off-panel audio must use the exact source treatment defined by that page; do not visually assign it to a physically present character.
- Wrong speaker, wrong tail, ambiguous tail, crossed/mixed ownership, or reordered dialogue = **automatic REJECT**.

## Current Production Rule Change

Chapter 1 interior pages require **visible reader-facing panel-order markers**.

- Render exactly ONE small circled number inside every story panel.
- Number panels consecutively from `1` through the page's locked panel count.
- The numbers follow the exact reading order defined by the page prompt.
- Keep them small, readable, and subtle near the upper-left of the panel or a quiet gutter-edge position.
- Never place them over dialogue, narration, SFX, device text, notebook text, faces, hands, recurring props, or clues.
- Reject missing, duplicated, skipped, out-of-order, oversized, or ambiguous numbers.
- Literal prompt labels such as `PANEL 1`, `PANEL 2`, etc. are still production instructions and must never be printed literally.
- Cover/front/back support assets do not use these markers.

Chapter 1 also uses **scene-adaptive narration/time-caption design**.

- Narration/time-caption wording is exact and locked by the page prompt.
- The visual treatment is NOT locked to one white box, background, border, color, shape, size, or placement.
- Caption presentation should blend with the actual scene while staying clearly readable and distinct from dialogue, SFX, device/notebook text, and panel-order markers.
- Appropriate treatments may include a clean light box, dark box, bordered shape, restrained banner, or another simple high-contrast flat-2D treatment suited to the panel.
- Do not force every caption on a page or chapter to look identical.
- Do not use unreadable bare narration over a busy or dark background.
- When a page requires a LARGE / noticeable time caption, the dynamic treatment must preserve that visual hierarchy.
- Do not invent narration on pages that have none.

## Approved Production Sources

Use the current files on `main`:

- `chapter.md`
- `page-001-chatgpt-image-prompt.md` through `page-018-chatgpt-image-prompt.md`
- `characters.md`
- `Comics/style-guide.md`
- `Comics/prompt-template.md`

If any story/dialogue/page-prompt file changes after generation begins, stop and re-audit that page plus every downstream continuity-dependent page.

## Canonical Character Reference Gate

Approved character PNGs:

- `Character-References/nari-canonical-flat2d.png`
- `Character-References/mrs-na-canonical-flat2d.png`
- `Character-References/seungjae-canonical-flat2d.png`
- `Character-References/hyunwoo-canonical-flat2d.png`

Required visible-character references:

| Page | Required canonical reference(s) |
|---:|---|
| 1 | Nari |
| 2 | Nari + Mrs. Na |
| 3 | Nari |
| 4 | Nari |
| 5 | Nari |
| 6 | Nari |
| 7 | Nari |
| 8 | Nari + Seungjae |
| 9 | Nari |
| 10 | Nari + Hyun-woo |
| 11 | Nari + Hyun-woo |
| 12 | Nari + Hyun-woo |
| 13 | Nari + Hyun-woo |
| 14 | Nari + Hyun-woo |
| 15 | Nari + Hyun-woo |
| 16 | Nari only — Hyun-woo physically absent |
| 17 | Nari only — Hyun-woo voice-only |
| 18 | Nari only — Hyun-woo voice-only |

Never use rejected/drifted generations, the legacy cover, or unrelated pages as character identity references.

## Reference Hierarchy

### Character identity
1. Approved canonical character PNG
2. `characters.md`
3. Previous approved page only as secondary continuity evidence

### Current page action/text
1. Current `page-###-chatgpt-image-prompt.md`
2. `chapter.md` for causal cross-check

### Environment/object continuity
1. Current page prompt
2. Immediately previous **approved** page
3. `Comics/style-guide.md`

A previous page must never override canonical character identity.

## Strict Sequential Generation Rule

Generate and approve only in this order:

`Page 1 → Page 2 → Page 3 → ... → Page 18`

- Do not batch-generate continuity-dependent future pages from an unapproved predecessor.
- Do not skip an unresolved page.
- Do not use a rejected/provisional page downstream.
- Only approved Page N may become the continuity reference for Page N+1.

## Locked Panel Counts And Required Markers

| Page | Panels / required circled markers |
|---:|---:|
| 1 | 1–6 |
| 2 | 1–9 |
| 3 | 1–7 |
| 4 | 1–8 |
| 5 | 1–8 |
| 6 | 1–9 |
| 7 | 1–6 |
| 8 | 1–6 |
| 9 | 1–5 |
| 10 | 1–6 |
| 11 | 1–4 |
| 12 | 1–6 |
| 13 | 1–5 |
| 14 | 1–8 |
| 15 | 1–8 |
| 16 | 1–8 |
| 17 | 1–8 |
| 18 | 1–6 |

Reject any generation with a different panel count or a marker sequence that does not exactly match this table.

## Global Pre-Generation Gate

Before generating every page confirm:

- current page prompt from `main`
- page prompt will be executed literally without rewrite/reinterpretation
- generation response will be the image, not a rewritten prompt or production summary
- exact script text/source/panel/type will be preserved verbatim
- dialogue bubble/callout ownership will match the exact scripted speaker/source
- correct page/output filename
- required canonical character PNG(s) attached
- only approved prior page used for scene continuity when needed
- exact panel count locked
- exact `1…N` small circled markers required
- starting subject/object/environment state matches prior approved page
- exact dialogue/captions/device text/notebook text/SFX copied without paraphrase
- large in-panel time caption used where scripted
- narration/time-caption visual treatment is scene-adaptive and readable, not forced into one fixed white/background/shape style
- no narration is invented on narration-free pages
- no separate time-card gutter unless explicitly requested
- no extra brands, logos, ads, prices, fake slogans, random promotional Korean text, signatures, or watermarks
- no future-lore spoilers

## Global Style Rejection Gate

Reject:

- photoreal/semi-photoreal rendering
- glossy/cinematic rendering
- painterly/airbrushed/3D-CG treatment
- reflective TV/refrigerator/glass/floor
- bloom, rim light, lens flare, volumetric rays, neon room glow
- wet/shiny/plastic surfaces
- strong gradients/cinematic color grading
- character identity drift
- rigid one-style-fits-all narration presentation that ignores the local scene
- unreadable narration caused by insufficient contrast
- generic substitute actions that contradict the exact scripted verb or blocking
- wrong-speaker dialogue bubbles or ambiguous/crossed callout tails

Required style: flat 2D human-drawn modern manga/manhwa, clean ink, matte cel colors, solid blocks, restrained hard-edged shadows.

## Environment And Object Rejection Gate

Reject:

- Unit 2407 geometry changes
- dining table merged with kitchen counter/sink/island
- refrigerator/TV/appliance redesign
- extra furniture/doors/windows
- unexplained character teleportation
- unexplained object movement/cleanup
- common-area emergency light incorrectly becoming apartment power
- a character operating an object when the script says they only hear/see/react to it

Critical object paths:

- brass backup key → entry tray Page 2 → held defensively through Page 4 Panels 5–8 → physically returned to entry tray Page 5 Panel 2 → tray through ending
- Page 5 handwritten paper/pen evidence beside toaster → same physical paper design and position in Page 6 photo tests
- electrical binder → kitchen counter after Page 6
- guarded fruit knife → under sofa cushion
- practical knife → desk sheath → drawn Page 10 → floor Page 14–16 → re-sheathed at desk Page 17–18
- exactly six noodles initially: one spicy seafood + five other flavors; five unopened remain after spicy seafood is used
- speaker-storage stockpot/towels/lid separate from noodle cooking pot
- noodle cooking pot/trivet/folded cloth stay at dining table
- candle stays in ceramic holder; extinguished Page 14 and never relit
- Hyun-woo chair same Pages 10–12; pushed back Page 13 through ending
- phone screen stays dark Page 9; phone placed on kitchen counter Page 17 and stays there Page 18
- A5 notebook stays desk until Page 18 retrieval
- TV stays visibly unplugged after Page 4 through final hostile activation

## Critical Page Guards

### Page 2 Doorbell / Dialogue Attribution
- Panel 1: Nari is already **inside Unit 2407** among moving boxes.
- Mrs. Na is the visitor **outside** and is the source of the doorbell ring.
- Nari only hears/reacts to `DING-DONG`.
- Nari must not knock, ring, press, tap, buzz, activate, point at, or touch the doorbell, intercom, smart lock, entry panel, wall button, or door control in Panel 1.
- The front door stays closed until Nari opens it in Panel 2.
- Mrs. Na does not appear inside Unit 2407 before Panel 3 threshold crossing.
- Panel 4: `THIS PLACE NEEDS A MANUAL?` belongs only to Nari; `IT DOES.` belongs only to Mrs. Na. Their bubble tails must point only to their respective speakers and must not cross.
- Panel 5 reading order is locked: Nari `ANYTHING I ACTUALLY NEED TO KNOW?` → Mrs. Na `YES. ONE THING.` → Mrs. Na `AFTER MIDNIGHT, DON'T LET THE HALLWAY GO DARK.`
- Page 2 Panels 4–8 must never leave the reader guessing whether Nari or Mrs. Na is speaking.

### Pages 4–5 Refrigerator / Return Route
- Page 4 Panel 7 is the brief hostile refrigerator activation: `FZZT` and `TENANT PROFILE: PENDING`. The reader sees the hostile message; Nari turns toward it but cannot clearly process/read it before it vanishes.
- Page 4 Panel 8 is a separate aftermath beat. The refrigerator display is completely dark and the message must NOT remain visible. Exact narration: `BY THE TIME NARI TURNED TOWARD IT, THE MESSAGE WAS ALREADY GONE.`
- Page 4 ends with Nari physically at or immediately beside the now-dark refrigerator, still holding the brass backup key.
- Page 5 Panel 1 begins at that exact refrigerator-side position and shows Nari turning away and starting to walk toward the entry area. She is still in transit at the end of Panel 1. No `CLINK` yet.
- Page 5 Panel 2 must visibly continue the SAME uninterrupted walking direction until Nari reaches the entry shelf. Only at the end does she physically return the brass key to the tray with `CLINK`.
- Page 5 Panel 3 occurs only after the key return: Nari turns and physically moves back toward the kitchen, then hides the unplugged speaker with `CLUNK`.
- Reject any version that starts Page 5 already at the tray, collapses the two-panel fridge-to-tray walk into one static key shot, changes walking direction between Panels 1–2, teleports Nari, or keeps the fridge hostile text visible on Page 5.

### Pages 5–6 Handwritten Evidence
- Page 5 Panel 4 and Panel 8 must show the same physical paper and the same original `WHO ARE` / `YOU?` two-line handwriting layout.
- Page 5 Panel 8 becomes the visual authority for the note object: paper size, aspect ratio, color, corners, edge angle, counter placement, pen relationship, toaster relationship, and flat matte paper treatment.
- Page 6 Panels 1–2 must continue that exact same paper object. A new generic note design, sticky note, index card, lined sheet, receipt, notebook page, torn scrap, enlarged prop note, or cleaner re-typeset evidence card is an automatic reject.
- In Page 6, the real physical note remains visible and unchanged; only the phone's captured photo/result omits the paper/writing.
- Page 6 must not collapse the real note's `WHO ARE` / `YOU?` layout into one line, reflow the reply, move the note, redesign the note, or make the real note disappear.
- Fresh Page 6 generation requires the approved Page 5 image as a continuity reference. Without approved Page 5, Page 6 is not ready for production generation.

### Page 8 Lobby Route / Multi-Device Failure
- Panel 1: Seungjae asks `WANT TO GET DINNER SOMETIME? WHEN WE'RE NOT WORKING LATE?`; Nari must answer `YEAH. I'D LIKE THAT.` before any device failure begins.
- Panel 2 is an **ENTERING-INWARD** lobby shot. The glass entrance closes behind them. Seungjae must not look like he is leaving. His first failure is the phone, with exact line `WAIT. MY PHONE JUST DIED.`
- Panel 3 remains deeper inside the SAME lobby while both continue toward the elevator. Seungjae checks separate personal devices: smartwatch and earbuds. The watch also dies and the earbuds fail/disconnect.
- Panel 3 dialogue order is locked: `MY WATCH TOO?` → `WHY IS EVERYTHING DYING AT ONCE?`
- The old line `OKAY. THAT'S WEIRD.` must NOT return.
- Seungjae must visibly look confused/increasingly concerned because several independent devices fail almost at once. A version where only the phone fails is an **automatic REJECT**.
- The building itself remains normally powered: no lobby blackout, elevator failure, door lockout, or safety-system interference.
- Panels 2–5 keep Seungjae continuously inside the lobby and moving/waiting with Nari. No U-turn or exit attempt before Panel 6.
- Panel 6 is the FIRST and ONLY time Seungjae turns back toward the ground-floor entrance. Nari enters the elevator alone; Seungjae does not go upstairs.

### Pages 10–12
- Hyun-woo is at the dining table, never the sink/counter.
- Canonical Hyun-woo is already used on Page 10 while identity is hidden by angle/shadow.
- Page 11 starts from exact Page 10 chair/table/pot/candle position.
- Page 12 keeps Hyun-woo seated all six panels; only Nari takes one cautious step.

### Pages 13–15
- Page 13: chair push → rise → cross → protective block.
- Page 14: candle warning → hostile locking → blue flame → blowout → shriek → knife drop → wrist catch.
- Page 15 starts from same wrist contact, then release.
- City power returns before Unit 2407.
- Hyun-woo remains physical while Unit 2407 itself is dark.
- Never show his disappearance process.

### Pages 16–18
- Hyun-woo is never physically drawn.
- **Page 16 power/lighting is restored before the page begins. Panels 1–8 must use the normal medium-bright neutral powered Unit 2407 baseline.**
- Page 16 must NOT use blackout darkness, deep charcoal/blue-black current-time lighting, candlelight, emergency lighting as the apartment light source, screen glow as primary room illumination, or any look suggesting a second outage.
- Nari's same clothing from Pages 9–15 is wardrobe continuity only; it does NOT justify blackout lighting on Page 16.
- Any earlier-outage darkness/emergency lighting may appear only inside the scripted camera/archive display as historical evidence. It must never restyle the surrounding present-time apartment.
- Page 16 Panel 5 remains a present-time normally lit apartment phone-call panel; do not replace it with a dark outage corridor/elevator scene.
- A Page 16 generation in which the current apartment looks dark or unpowered is an **automatic REJECT**.
- Page 16: disappearance spot → door/latch → entry history → camera → security → Mrs. Na voicemail → closed cabinet chimes.
- Page 17: same cabinet/stockpot/towels/speaker; phone counter; knife floor → desk sheath; food checked before eating.
- Page 18: same open cabinet; table → desk → table notebook route; hostile unplugged TV ending.

## Device Signature Guard

Hyun-woo/helpful:
- clean cyan-white or clean voice treatment
- no crawling black pixels

Hostile:
- broken/doubled stark-white glyphs
- crawling black pixels/corruption

Never swap them.

## Reader-Facing Text And Marker Guard

Reject if the image:

- changes, omits, paraphrases, rewrites, reorders, moves, duplicates, or invents story text
- changes a line's speaker/source
- changes a line's panel assignment
- changes a line's text type
- gives a dialogue line to the wrong character
- uses an ambiguous or wrong speech-bubble tail/callout
- merges dialogue from different speakers into one bubble
- omits a panel-order number
- duplicates a panel-order number
- skips a number
- renders numbers out of reading order
- renders numbers too large or over important content
- prints literal production labels such as `PANEL 1`
- adds a page number or unrelated counting marks
- forces all narration/time captions into a fixed white-box treatment regardless of scene
- makes narration/time captions difficult to read against the local artwork

Removed story beats must not return, including `OUR APARTMENT`, reader-facing `RECORD CORRUPTED`, toaster-crumb writing, Page 8 car-key beat, Page 8 old `OKAY. THAT'S WEIRD.` reaction, Page 9 phone activation, Page 11 fruit-knife joke, Page 12 haunting-noodles banter, and Page 15 cheap-rent/door banter.

## Post-Generation Approval Gate

Do not approve Page N until all applicable checks pass:

1. The generator executed the locked page prompt rather than rewriting/reinterpreting it.
2. Every scripted text line is verbatim and remains in its exact panel, source/speaker, and text type.
3. Every dialogue bubble/callout points unambiguously to the correct scripted speaker/source; no mixed/crossed ownership.
4. Exact locked panel count.
5. Exactly one small circled reading-order marker per panel, consecutively `1…N`.
6. Marker placement is subtle and does not obscure story content.
7. Character identity matches canonical PNGs.
8. Wardrobe/physical state matches current/prior approved page.
9. Environment geometry remains consistent.
10. Object states/positions match continuity ledger.
11. Movement is physically understandable; no teleportation.
12. Scripted verbs/actions are literal: characters do not operate/touch objects unless instructed.
13. Power/lighting state matches story moment; specifically, Page 16 current-time Panels 1–8 are visibly powered and normally lit after Page 15 restores Unit 2407 power.
14. Device actor signature is correct.
15. Reader-facing story text is exact and complete.
16. Narration/time-caption design, where present, fits the local scene, stays high-contrast/readable, and is not unnecessarily forced into one universal box style.
17. SFX is attached to the correct physical source.
18. No extra text/brands/logos/ads/random Korean promotional copy.
19. No spoilers/future lore.
20. Flat matte 2D style is preserved.
21. Page is safe to use as the continuity reference for Page N+1.

If any check fails: REJECT the image, do not use it downstream, correct/regenerate it, then run the gate again.

## Final Chapter Completion Gate

After Page 18 is approved, perform one final Page 1→18 image audit for:

- canonical character consistency
- Unit 2407 geometry/appliance consistency
- recurring object paths
- power/time continuity
- Page 16 current-time powered-lighting continuity after Page 15 restoration
- Page 10–15 subject positions
- clean-vs-hostile signatures
- exact verbatim story text/SFX
- exact speaker/source/panel/text-type attribution
- correct dialogue bubble/callout ownership
- literal execution of scripted actions without invented substitute interactions
- narration/time-caption readability and scene-appropriate design wherever narration appears
- exact panel counts
- correct small circled `1…N` markers on every page
- no missing/duplicate/out-of-order markers
- no accidental extra text

Only after this visual pass is Chapter 1 fully rendered and production-complete.
