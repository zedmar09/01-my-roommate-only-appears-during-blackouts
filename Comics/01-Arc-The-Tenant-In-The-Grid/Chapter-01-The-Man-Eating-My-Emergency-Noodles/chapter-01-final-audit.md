# Chapter 01 Final Audit

Status: **PASS — FINAL PRE-GENERATION GUARD COMPLETE**

This is the current go/no-go audit of the Chapter 1 production package on `main` after the completed Page 1–18 dialogue/continuity rewrite, shared guard cleanup, visible panel-order-marker requirement, scene-adaptive narration-design rule, and the chapter-wide image-only execution lock.

## Audited Production Package

- `chapter.md`
- `page-001-chatgpt-image-prompt.md` through `page-018-chatgpt-image-prompt.md`
- `chapter-01-continuity-audit.md`
- `chapter-01-generation-checklist.md`
- `characters.md`
- `Comics/style-guide.md`
- `Comics/prompt-template.md`
- approved canonical character references

Chapter 1 contains exactly **18 story pages**. There is no Page 019 production prompt.

## Image-Only Execution Rule

The current Page 001–018 Markdown files are already the final production instructions.

For every page generation:

- do not rewrite, summarize, paraphrase, reinterpret, improve, reorganize, or re-block the page prompt before generation
- do not invent alternate actions, poses, prop interactions, transitions, dialogue, captions, SFX, device text, notebook text, or motivations
- execute specific scripted verbs and blocking literally
- do not substitute a generic comic action for a precise scripted action
- do not move characters/objects unless the current page explicitly scripts movement
- if an instruction seems unusual, follow the written instruction rather than “correcting” it
- creative freedom is limited to drawing/composition that realizes the locked instructions without changing meaning
- after reading the prompt/references, generate the page image directly; do not replace the image with a rewritten prompt, production explanation, alternate plan, or pre-generation script

This rule applies to **all Pages 001–018**, even if the individual page Markdown does not repeat the block verbatim.

## Page 2 Doorbell Blocking Lock

Page 2 Panel 1 is explicitly locked as follows:

- Nari is already **inside Unit 2407** among moving boxes.
- Mrs. Na is the visitor **outside in the corridor** and is the source of the `DING-DONG`.
- Nari only hears/reacts to the doorbell sound.
- Nari must not knock, ring, press, tap, buzz, activate, point at, or touch any doorbell, intercom, smart lock, entry panel, buzzer, wall button, or door control in Panel 1.
- The front door remains closed during Panel 1.
- Nari opens the door from inside in Panel 2.
- Mrs. Na does not cross into Unit 2407 until Panel 3.

Any Page 2 image showing Nari operating the doorbell/buzzer in Panel 1 is an automatic **REJECT**.

## Panel Order Marker Rule

Every Chapter 1 interior story panel requires one small circled reader-facing order marker:

- Page 1: `1–6`
- Page 2: `1–9`
- Page 3: `1–7`
- Page 4: `1–7`
- Page 5: `1–7`
- Page 6: `1–9`
- Page 7: `1–6`
- Page 8: `1–6`
- Page 9: `1–5`
- Page 10: `1–6`
- Page 11: `1–4`
- Page 12: `1–6`
- Page 13: `1–5`
- Page 14: `1–8`
- Page 15: `1–8`
- Page 16: `1–8`
- Page 17: `1–8`
- Page 18: `1–6`

Rules:

- exactly one marker per story panel
- consecutive reading order only
- small circled style
- near upper-left or quiet gutter-edge position
- readable but subtle
- never over dialogue, captions, SFX, device/notebook text, faces, hands, props, or clues
- literal prompt labels `PANEL 1`, `PANEL 2`, etc. do not print
- no separate reader-facing page number required
- support banners do not use panel markers

## Narration Caption Design Rule

Narration/time-caption **wording is locked**, but its graphic presentation is intentionally dynamic.

- Caption design responds to the actual panel and story moment.
- Do not force one fixed white box, background, border, color, shape, size, or placement across the chapter.
- Use a restrained high-contrast flat-2D treatment that fits the local scene: light box, dark box, bordered shape, restrained banner, or another simple readable treatment.
- Keep narration visually distinct from dialogue, SFX, device text, notebook text, and the small circled panel-order marker.
- Never sacrifice readability: no low-contrast bare text over busy or very dark artwork.
- Large time captions remain large/noticeable even though their styling is adaptive.
- Pages without narration do not gain invented captions.

For Chapter 1, the narration-bearing page prompts are explicitly aligned to this rule. Narration-free pages remain unchanged while inheriting the same global guard through `Comics/style-guide.md`, `Comics/prompt-template.md`, and the Chapter 1 generation checklist.

## Final Verification Matrix

| Area | Result | Verified state |
|---|---|---|
| Page sequence | PASS | Exactly Pages 001–018; no Page 019. |
| Image-only execution | PASS | Pages 001–018 are executed from the locked prompt without pre-generation rewrite/reinterpretation. |
| Page 2 doorbell | PASS | Nari inside; outside visitor rings; Nari never operates doorbell/intercom/control in Panel 1. |
| Master/story sync | PASS | `chapter.md` remains synchronized to the locked Page 1–18 story/dialogue. |
| Dialogue | PASS | Production-presentation changes do not alter approved dialogue, narration wording, device text, notebook text, or SFX. |
| Panel counts | PASS | Locked counts remain `6, 9, 7, 7, 7, 9, 6, 6, 5, 6, 4, 6, 5, 8, 8, 8, 8, 6`. |
| Panel order markers | PASS | Every page prompt requires one small circled marker per panel in exact consecutive reading order. |
| Narration design | PASS | Narration/time-caption wording is exact; presentation is scene-adaptive, high-contrast, and not locked to a universal white box/background/shape. |
| Time transitions | PASS | Meaningful time jumps remain large noticeable in-panel narration captions; no separate tiny time-card gutters. |
| Canonical identities | PASS | Nari, Mrs. Na, Seungjae, and Hyun-woo use approved canonical references where visually present. |
| Visual style | PASS | Flat 2D human-drawn matte manga/manhwa; glossy/cinematic/photoreal/3D/painterly/reflective treatments rejected. |
| Unit 2407 geometry | PASS | Living/TV left, dining center, kitchen/refrigerator right, hallway behind; fixed appliance bodies and room geometry. |
| Object continuity | PASS | Key, binder, two knives, noodles, two separate pots, towels/lid/speaker, candle, chair, phone, notebook, TV, and refrigerator have traceable states. |
| Page 8 geography | PASS | Exterior canopy → same ground-floor lobby → elevator bank; Nari goes upstairs alone; Seungjae leaves. |
| Page 9 screen rule | PASS | Phone remains dark during outage. |
| Pages 10–12 | PASS | Hyun-woo stays at the dining table; Page 12 keeps him seated while only Nari steps. |
| Pages 13–15 | PASS | Chair push → rise → cross → block; candle/knife/wrist order; city returns before unit; disappearance process not shown. |
| Page 16 | PASS | Door/latch → entry history → camera → security → voicemail → cabinet chimes. |
| Page 17 | PASS | Same cabinet/storage stockpot/towels/speaker; phone counter; knife floor → desk sheath; food checked before eating. |
| Page 18 | PASS | Hyun-woo voice-only; notebook physically retrieved; apartment-power hypothesis; hostile unplugged TV ending. |
| Device signatures | PASS | Helpful remains clean; hostile remains broken-white/black-pixel corruption. |
| Brand/text contamination | PASS | No unscripted brands, ads, prices, fake slogans, promotional Korean filler, signatures, or watermarks. |
| Spoiler boundary | PASS | Chapter 1 does not reveal future origin/restoration/memory-cost/climax material. |

## Obsolete Production Material Guard

Do not reintroduce:

- `OUR APARTMENT`
- reader-facing `RECORD CORRUPTED`
- toaster-crumb writing / `TENANT.`
- Page 8 `TOO MANY DEVICES` / car-key exchange
- Page 9 phone-screen activation
- Page 11 fruit-knife joke
- Page 12 haunting-noodles banter
- Page 15 cheap-rent / `THROUGH THE DOOR?` banter
- `LOSS OF BUILDING POWER REQUIRED.` as the final notebook hypothesis
- separate tiny/full-width time-card gutters for Chapter 1
- the obsolete instruction to remove all panel numbers
- any obsolete instruction forcing all narration into identical solid-white caption boxes
- pre-generation rewriting/rephrasing of a locked page prompt
- generic substitute actions that contradict a scripted action/source

The current requirements are:

- **execute every locked page prompt literally and generate the image directly**
- **small circled order markers are mandatory on every interior story panel**
- **narration design is dynamic and scene-adaptive while exact wording stays locked**

## Final Generation Guard

Chapter 1 is cleared for generation only with strict sequential approval:

1. Read the current page prompt and references; do not rewrite/reinterpret the production instructions.
2. Generate the page image directly from the locked prompt.
3. Verify exact panel count and exact consecutive circled panel markers.
4. Verify marker placement does not cover story content.
5. Verify canonical character identity.
6. Verify environment geometry and object states.
7. Verify exact scripted verbs/actions/sources were followed literally; reject invented substitute interactions.
8. Verify exact dialogue/narration/device/notebook text and SFX.
9. Where narration/time captions are present, verify scene-appropriate dynamic treatment, high contrast, readability, and required time-caption prominence.
10. Reject narration that is unreadable or mechanically forced into one universal caption style regardless of scene.
11. Verify correct lighting/power state and clean-vs-hostile device signature.
12. Reject any page with missing, duplicate, skipped, out-of-order, oversized, or obstructive panel markers.
13. Only an **approved** Page N may become the continuity reference for Page N+1.
14. Never use rejected/provisional/drifted artwork downstream.
15. After Page 18, perform one final Page 1→18 visual continuity audit.

## Final Result

**PASS — Chapter 1's 18-page production package and shared guardrails are aligned with the image-only execution rule, Page 2 doorbell blocking, visible panel-order-marker requirement, and scene-adaptive narration-design rule, and are cleared for strict sequential image generation.**

This PASS applies to instructions currently on `main`. It does not pre-approve generated artwork; every rendered page still requires post-generation review.
