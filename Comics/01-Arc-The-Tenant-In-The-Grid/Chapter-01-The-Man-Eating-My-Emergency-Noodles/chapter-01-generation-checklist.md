# Chapter 01 Image Generation Checklist

Status: PASS — STORY AND PROMPT PACKAGE READY FOR IMAGE GENERATION

The independent final audit records a verified pass after the six-item correction cycle. Generate pages only in the numbered order below and reject any output that fails a gate in this checklist.

## Approved Chapter 1 Generation Baseline

- Approved source commit for this Chapter 1 production cycle: `ad540d7f11f4f58e40b866aaebd27f5c482a2f4b`.
- This SHA freezes the QA-approved Chapter 1 story, canon, dialogue, page prompts, object states, timeline, and visual rules for this production cycle. It is not a permanent baseline for future chapters.
- This checklist update strengthens production safeguards only; it does not reopen or revise the frozen story/prompt content.
- Before Page 1 generation, record this SHA in the approval record and confirm the production copy of every frozen source file matches it.
- If any frozen Markdown content changes after generation begins, stop the sequence immediately and follow the Markdown Change Stop-Rule below. Never continue with pages generated from mixed source revisions.

## Prompt And Output Sequence

1. `page-001-chatgpt-image-prompt.md` -> `1.png` -> `1.webp`
2. `page-002-chatgpt-image-prompt.md` -> `2.png` -> `2.webp`
3. `page-003-chatgpt-image-prompt.md` -> `3.png` -> `3.webp`
4. `page-004-chatgpt-image-prompt.md` -> `4.png` -> `4.webp`
5. `page-005-chatgpt-image-prompt.md` -> `5.png` -> `5.webp`
6. `page-006-chatgpt-image-prompt.md` -> `6.png` -> `6.webp`
7. `page-007-chatgpt-image-prompt.md` -> `7.png` -> `7.webp`
8. `page-008-chatgpt-image-prompt.md` -> `8.png` -> `8.webp`
9. `page-009-chatgpt-image-prompt.md` -> `9.png` -> `9.webp`
10. `page-010-chatgpt-image-prompt.md` -> `10.png` -> `10.webp`
11. `page-011-chatgpt-image-prompt.md` -> `11.png` -> `11.webp`
12. `page-012-chatgpt-image-prompt.md` -> `12.png` -> `12.webp`
13. `page-013-chatgpt-image-prompt.md` -> `13.png` -> `13.webp`
14. `page-014-chatgpt-image-prompt.md` -> `14.png` -> `14.webp`
15. `page-015-chatgpt-image-prompt.md` -> `15.png` -> `15.webp`
16. `page-016-chatgpt-image-prompt.md` -> `16.png` -> `16.webp`
17. `page-017-chatgpt-image-prompt.md` -> `17.png` -> `17.webp`
18. `page-018-chatgpt-image-prompt.md` -> `18.png` -> `18.webp`

ChatGPT produces PNG only. Manually convert an approved PNG to WebP. Do not generate any image during the Markdown QA stage.

## Strict Sequential Generation Rule

- Generate and approve interior pages strictly in this order: `Page 1 -> Page 2 -> Page 3 -> ... -> Page 18`.
- A later page may be generated only after the immediately previous interior page passes every applicable approval gate and its approved filename is recorded.
- Do not generate Page 8 before Page 7 is approved, batch continuity-dependent pages from an unapproved predecessor, skip an unresolved page, or continue downstream from rejected artwork.
- Only the final approved version of Page N may be attached as the visual reference for Page N+1. A rejected, provisional, or superseded image is never a valid reference.

## Visual Reference Hierarchy

For Page 1, use only:

1. `characters.md`
2. `Comics/style-guide.md`
3. `page-001-chatgpt-image-prompt.md`

Record `Reference page: NONE - SOURCE LOCKS ONLY` for Page 1.

For Page 2 onward, use all four sources in this order:

1. `characters.md`
2. `Comics/style-guide.md`
3. the exact current page prompt
4. the immediately previous approved interior story page

Use the previous approved interior page to stabilize face shapes, hair, adult body proportions, clothing treatment, line weight, matte palette, Unit 2407 geometry, furniture, appliances, recurring-object design, rendering density, lettering treatment, and powered/blackout exposure. Do not copy its action, camera angle, panel layout, or dialogue unless the current page script explicitly continues that element.

Never use these files as interior continuity references:

- `Covers/story_cover.png`
- `Covers/story_cover.webp`
- `Covers/front.png`
- `Covers/front.webp`
- `Covers/back.png`
- `Covers/back.webp`

The story cover is symbolic premise art, while the front/back files are promotional appliance banners. Neither is a literal interior scene, and their composition or wardrobe may intentionally differ. Only approved interior pages may serve as page-to-page visual references.

## Page 1 Benchmark Gate

Page 1 establishes the production benchmark for Nari's face, hair shape, adult proportions, beauty mark, yellow scrunchie, clothing treatment, line art, skin rendering, matte color treatment, Unit 2407 geometry, refrigerator, TV, smart speaker, floor/wall/cabinet colors, and overall visual density.

Do not approve Page 1 merely because it is attractive. Approve it only when it correctly establishes every locked continuity element and passes every applicable gate below. If its style, scale, environment, character design, or text is wrong, reject and regenerate it before creating Page 2.

## Pre-Generation Gate

- Confirm the approval record uses source commit `ad540d7f11f4f58e40b866aaebd27f5c482a2f4b` for this production cycle.
- Confirm all 18 prompt files exist contiguously with no duplicates or missing number.
- For Page 1, attach no previous page. For Page 2 onward, attach only the immediately previous approved interior page.
- Confirm no rejected/superseded draft or cover/support image is attached as a continuity reference.
- Confirm the page prompt matches the current prose scene, dialogue, time, power state, wardrobe, object states, and preceding page.
- Confirm each prompt includes all required blocks, panel-order numbers, exact dialogue/text, story clarity, and avoid list.
- Confirm no prompt invents a flashback, future event, future lore, or unlisted dialogue.

## Hard Style Rejection Gate

Reject and regenerate any image containing any of the following:

- glossy webtoon rendering or glossy material treatment
- cinematic lighting or movie color grading
- photorealism or semi-photorealism
- 3D or CG rendering
- painterly, concept-art, oil-paint, or airbrushed rendering
- shiny skin, shiny lips, glossy hair, glossy clothing, plastic shine, or chrome-like shine
- glossy refrigerator/TV, reflective screen/floor, mirror-like window/appliance, refrigerator glare, television glare, glass glare, or white reflection streak
- cinematic or strong atmospheric lighting, bloom, rim light, lens flare, volumetric rays, neon aura, excessive supernatural glow, or atmospheric glow flooding the room
- strong gradients, depth-of-field blur, over-rendered texture, or wet-looking surface

Required appearance: 100% flat 2D human-drawn colored manga/manhwa, clean visible ink, matte cel colors, solid color blocking, controlled hard-edged shading, readable adult faces and environments, clean silhouettes, stable character proportions, and matte technology/appliances.

Do not approve a page containing a prohibited style merely because the character faces are attractive.

## Character Rejection Gate

- Reject teenage/schoolgirl Nari, changed dark-plum asymmetrical hair, missing beauty mark, missing yellow scrunchie, missing headphones where scripted, glamorous heiress styling, chibi, or generic waifu features.
- Reject historical/palace/vampire/xianxia/corporate/school-delinquent Hyun-woo, uncovered lower face, changed technical mask, short hair, neon tattoos, glowing veins, or light beneath skin.
- Reject Mrs. Na without her established arrival handbag/key ring/analog watch, or with handbag appearing only on departure.
- Reject Seungjae as villainous or stranded; his car key must work.

## Environment And Appliance Rejection Gate

- Reject changed Unit 2407 geometry: TV/living left, dining center, kitchen/refrigerator right, hallway behind, windows exterior.
- Reject palette changes to cool-gray walls, eucalyptus lower cabinets, pale-gray counters/table, medium-gray floor, burgundy chairs.
- Reject moved/redesigned refrigerator, changed door count/handles/display position, glossy door, chrome, or random temperature/status between consecutive panels.
- Reject reflective/redesigned TV, changed bezel/stand/console, or accidental character silhouette/reflection.
- Reject speaker redesign, words printed on its body, missing cord, or speech without a bubble tail to hardware.
- Reject cooktop redesign, digital controls, glossy glass, or missing manual knobs.

## Power And Actor Rejection Gate

- Reject any phone screen treated as the protective mains light or as independently blocking manifestation.
- Reject Hyun-woo physically visible while ordinary Unit 2407 power is active.
- Reject Hyun-woo visible during the exact power-on panel or any shown dissolution/particles/portal/network transition.
- Reject supernatural current described or drawn as ordinary building power.
- Reject hostile corruption styled as clean cyan Hyun-woo text.
- Reject Hyun-woo warning styled with broken glyphs/crawling black pixels.
- Reject a disconnected device operating normally without the weak/static supernatural-current instruction.
- Reject candle center other than unnatural blue on Page 14.

## Timeline And Action Rejection Gate

- Reject missing/unreadable time cards or decorative/numbered time cards.
- Reject Page 3 without both unnumbered undecorated gutters: `ONE WEEK LATER` before Panel 1 and `THAT NIGHT` between Panels 3 and 4.
- Reject Page 5 without both unnumbered undecorated gutters: `LATER THAT NIGHT - 1:17 A.M.` between Panels 4 and 5 and `THE NEXT MORNING` between Panels 5 and 6.
- Reject the old seven-minute/12:50 interval; the kitchen discovery is thirteen minutes into the blackout at 12:56 A.M.
- Reject any invented exact power-return or outage-end timestamp; Page 16 camera text must read `OUTAGE INTERVAL / FILE ERROR`.
- Reject meaningful location changes without entry/walk/connecting context.
- Reject reordered TV beats: on -> approach -> unplug -> still active -> reaction -> question.
- Reject one-photo evidence conclusion; two failed photos must appear.
- Reject merged Page 14 actions: extinguish -> shriek -> ears -> knife drop -> wrist catch.
- Reject Page 15 unit lights returning before Hyun-woo finishes speaking.
- Reject Page 16 security checks being skipped before food/speaker decompression.

## Object Rejection Gate

- Reject oversized key, binder, speaker, knife, candle, holder, noodle pot, notebook, refrigerator, or Hyun-woo.
- Reject any unguarded fruit knife under the sofa cushion or unsheathed practical knife in the desk tray.
- Reject the guarded fruit knife appearing at the Page 7 store, any claim that two knives are purchased, or any purchase other than the single sheathed practical knife.
- Reject missing sheath when knife moves, changed handle orientation, or blind grip on blade.
- Reject candle without ceramic holder or extinguished candle missing its smoke/holder.
- Reject hot noodle pot directly on table, missing trivet, or confusing handle cloth with table protection.
- Reject noodle dialogue/inventory that implies all noodles are gone; one spicy-seafood packet is used and five other packets remain.
- Reject key, binder, speaker, stockpot, towels, lid, trays, supplies, knives, noodle items, chair, notebook, TV, or refrigerator teleporting or changing state without scripted movement.

## Page-By-Page Approval Gate

Before generating the next page, review the current page against every applicable category. Any unresolved failure means `REJECTED`; correct or regenerate the current page before continuing.

### A. Character

- Face, adult age, hairstyle, hair color, beauty mark, scrunchie, body proportions, and timeline wardrobe match the source locks and previous approved page.
- When visible, Hyun-woo's mask, tied-back hair, adult proportions, and matte tattoo treatment remain exact.
- Mrs. Na and Seungjae retain their established identifiers.

### B. Environment

- Unit 2407 remains TV/living left, dining table center, kitchen/refrigerator right, hallway behind, and window wall exterior.
- Wall, cabinet, counter, floor, and chair colors remain consistent with the locked matte palette.

### C. Appliances

- Refrigerator body, door layout, recessed handles, and upper-right display remain unchanged.
- TV bezel, centered stand, and charcoal console remain unchanged.
- Speaker remains a screenless corded matte-charcoal cylinder.
- Cooktop remains a manual two-burner gas unit.

### D. Objects

- Check every scripted recurring prop: brass key, electrical binder, notebook, speaker, stockpot, towels, lid, note, knives, guards/sheaths, flashlight, radio, candle, holder, matches, noodle packets, noodle pot, trivet, cloth, chopsticks, and chairs.
- Verify each prop's scale, position, state, orientation, and whether a scripted hand/action actually moved it.

### E. Power State

- Verify powered versus blackout state, hallway lamp, phone/devices, candle, Hyun-woo physical versus voice-only state, city/common-area backup versus Unit 2407 power, and the power-return sequence.

### F. Dialogue And Text

- Every line exactly matches the current page prompt, belongs to the correct speaker/device, and follows the intended reading order.
- Reject missing, duplicated, invented, misspelled, unreadable, meaning-changing, gibberish, or random fake interface text.
- Device text must use the correct clean Hyun-woo or broken hostile-system signature and must not cover a face, hand, clue, or important object.

### G. SFX

- Only scripted SFX may appear. Each must belong to the correct physical source and must not obscure a face, hand, clue, or dialogue.
- Reject random decorative SFX.

### H. Time Cards

- Every scripted card must use exact wording in an unnumbered, undecorated gutter.
- Reject any card containing a panel number, character, object, scenery, decorative image, gradient, SFX, or dialogue.

### I. Spoiler Gate

Reject any generated visual that introduces the future Black Surge reveal, Hyun-woo's origin, accident explanation, human culprit, body-restoration explanation, memory-transfer solution, future-chapter imagery, or unmasked Hyun-woo unless the current page explicitly scripts it.

## Text Rendering Hard Gate

Image-generation text is never "close enough." Reject and regenerate any page with important text that is misspelled, omitted, duplicated, unreadable, assigned to the wrong speaker/device, shown in the wrong supernatural signature, rendered as gibberish, or placed over a face or clue.

Protect these critical text anchors exactly as written in their current page prompts:

- `WELCOME HOME, YOON NARI.`
- `SAY PLEASE.`
- `OUR APARTMENT`
- `TENANT PROFILE: PENDING`
- `TENANT.`
- `STOP. IT CAN SEE WHAT YOU SAVE.`
- `YOON NARI`
- `IDENTITY LOCKING`
- `WARM.`
- Page 18 notebook observation/hypothesis: `UNIT 2407 BUG REPORT`, `OBSERVATION 001:`, `ROOMMATE PHYSICAL DURING BLACKOUT.`, `HYPOTHESIS:`, and `LOSS OF BUILDING POWER REQUIRED.`
- `NEW TENANT CONFIRMED`

Do not approve a visually attractive page with incorrect critical text.

## Page-Level Story Gate

- Page 1: visible first entry and fixed apartment establishment.
- Page 2: Mrs. Na arrives/enters, detaches key, defines rule, answers blackout question evasively, leaves; key moves separately.
- Page 3: `ONE WEEK LATER` and mid-page `THAT NIGHT` cards, 19 C thermostat, clean speaker voice during flicker, visible unplug.
- Page 4: unplugged-TV order and separate hostile refrigerator seed.
- Page 5: speaker hiding, paper note, guarded fruit knife, `LATER THAT NIGHT - 1:17 A.M.` card, flicker, `THE NEXT MORNING` card, crumb answer.
- Page 6: nine panels showing two failed photos, hostile corruption, clean warning, missing manual section, Mrs. Na contact, then binder closure/carry/return to counter.
- Page 7: binder begins on counter, only one sheathed practical knife is purchased, fruit knife stays in apartment, realistic retailer, physically possible two-bag entry, safe pantry/desk setup.
- Page 8: comic device sabotage, working car key, completed elevator entry/exit.
- Page 9: 12:43 citywide outage, visible lamp compliance, 81% phone evidence, separate corridor backup.
- Page 10: repeated-test montage, 12:56 card, safe knife draw, connected route, candle holder/trivet/cooking evidence.
- Page 11: mask secured before face readability and spacious first reveal.
- Page 12: last spicy-seafood flavor plus five remaining packets; causal banter.
- Page 13: no refrigerator reflection; rise/cross/block/warn sequence; hostile name reveal.
- Page 14: mains-light/candle explanation, blue center, ordered horror reaction, `WARM.` first-touch evidence.
- Page 15: actor distinction, unit remains dark through dialogue, power snap, next-beat absence.
- Page 16: lock/latch/log/camera/security/landlord checks before speaker; camera labels only the `OUTAGE INTERVAL`, with no invented return time.
- Page 17: borrowed current, safe knife storage, food inspection/hesitation, concise rules.
- Page 18: missing-page evasion, danger admission, notebook observation/hypothesis, hostile final TV.

## High-Risk Page Watchlist

Apply an especially strict review to these continuity-heavy pages:

- Page 3: both time cards, `19 C`, speaker plugged then visibly unplugged, clean Hyun-woo signal.
- Page 5: both time cards, key return, speaker/stockpot/towels/lid, guarded fruit knife, 1:17 flicker, physical crumb reply.
- Page 6: two failed photos, hostile corruption, clean warning, binder and missing Section 17, Mrs. Na communication, binder returned to counter.
- Pages 9-10: 12:43 A.M., 81% phone, device failures, corridor backup outside the apartment, 12:56 A.M., knife/sheath, cooking evidence, candle holder, trivet.
- Pages 11-15: Hyun-woo's physical state, mask/tattoos, noodle inventory, chair movement, hostile refrigerator, blue candle, ordered shriek/ears/knife/wrist sequence, `WARM.`, clean/broken actor explanation, Unit remaining dark through final dialogue, Hyun-woo absent only after power-on.
- Pages 16-18: no physical Hyun-woo, locks/security/camera checks, `OUTAGE INTERVAL / FILE ERROR`, borrowed speaker current, knife re-sheathed, food inspection, binder on counter, key in entry tray, notebook retrieved only on Page 18, final hostile TV signature.

## Failure And Change Control

### Do Not Propagate A Bad Page

A page with any unresolved character, environment, appliance, object, power-state, text, SFX, time-card, spoiler, or style error must never become the reference for the next page. If Page 8 fails, do not generate Page 9 from it. Regenerate or correct Page 8 first; only its final approved version may become Page 9's reference.

### Regeneration Version Rule

- Rejected or draft versions must remain outside the final reader-facing chapter directory or be removed before final ingestion.
- The final directory must contain only accepted reader-facing names such as `1.png` and `1.webp` through `18.png` and `18.webp`.
- Do not leave ambiguous names such as `7-final.png`, `7-final2.png`, `7-good.webp`, `7-new.png`, or `7-test.png` in the final reader directory.
- Never attach a rejected, draft, or superseded version as a continuity reference.

### Markdown Change Stop-Rule

If anyone changes `chapter.md`, `characters.md`, `Comics/style-guide.md`, `Comics/prompt-template.md`, the current or previous page prompt, dialogue, SFX, panel count, chronology, power rules, prop position, wardrobe, device signature, or environment geometry after generation begins:

1. Stop all downstream page generation.
2. Identify every already-generated page affected by the change.
3. Return the changed material and affected pages to QA.
4. Obtain and record a new approved source baseline.
5. Regenerate affected pages when necessary.
6. Resume generation sequentially from the earliest affected page.

Never continue silently with mixed Markdown/script versions.

## Approval Record

Copy and complete this record for each page. Use `NONE - SOURCE LOCKS ONLY` as Page 1's reference; for Page 2 onward, name the immediately previous approved interior page. A page may be marked `APPROVED` only when every applicable category is `PASS` and the approved file is the final reader-facing version.

```text
PAGE 01
Status: APPROVED / REJECTED
Source commit: ad540d7f11f4f58e40b866aaebd27f5c482a2f4b
Reference page: NONE - SOURCE LOCKS ONLY
Character continuity: PASS / FAIL
Environment: PASS / FAIL
Appliances: PASS / FAIL
Objects: PASS / FAIL
Power state: PASS / FAIL
Dialogue/Text: PASS / FAIL
SFX: PASS / FAIL
Time cards: PASS / FAIL / N/A
Style: PASS / FAIL
Spoiler gate: PASS / FAIL
Notes:
Approved file:
```

The independent final audit passed every comparison. Keep this checklist with the prompt set during generation and return the package to `HOLD` if a future Markdown change alters canon, dialogue, panel order, timing, object state, or visual rules.
