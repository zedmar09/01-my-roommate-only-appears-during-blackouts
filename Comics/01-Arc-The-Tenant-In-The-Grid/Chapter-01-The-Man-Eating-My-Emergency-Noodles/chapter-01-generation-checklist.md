# Chapter 01 Image Generation Checklist

Status: CONDITIONAL PASS — STORY AND ALL 18 PAGE PROMPTS APPROVED/IDENTITY-LOCKED; CHARACTER-CONTAINING GENERATION REQUIRES APPROVED FLAT-2D CANONICAL REFERENCES

The independent final audit records a verified story/prompt pass. All 18 Chapter 1 page prompts now contain direct canonical-character-reference locks. Before generating any final asset that contains a recurring character, complete the relevant flat-2D canonical reference preflight below. Front/back appliance-only banners do not require character references.

## Approved Chapter 1 Generation Baseline

- Approved source commit for the frozen Chapter 1 story/prompt/reference-lock content: `900eafcb408fc3e429cb429fb3bd18c06ce507ab`.
- This SHA freezes the QA-approved Chapter 1 story, canon, dialogue, all 18 page prompts, object states, timeline, visual rules, and page-level canonical-character-reference locks for this production cycle. It is not a permanent baseline for future chapters.
- Later documentation-only safeguards do not authorize story, canon, dialogue, page-action, or character-identity changes.
- If any frozen Markdown story/prompt content changes after generation begins, stop the sequence immediately and follow the Markdown Change Stop-Rule below. Never continue with pages generated from mixed source revisions.

## Canonical Flat-2D Character Reference Preflight — Mandatory

The original/legacy cover established the intended historical concepts for Nari and Hyun-woo, but its rendering is NOT production-safe for the current visual target. It is too cinematic, glossy, reflective, neon-heavy, and over-rendered.

HARD RULE: DO NOT attach the legacy/original cover during normal final cover or interior-page generation. Do not use it as an active image reference. Do not use the rejected drifted cover either.

Create and approve these production-safe references before the first final page/asset that visually shows each character:

1. `Character-References/nari-canonical-flat2d.png` from `Character-References/nari-canonical-flat2d-chatgpt-image-prompt.md`
2. `Character-References/hyunwoo-canonical-flat2d.png` from `Character-References/hyunwoo-canonical-flat2d-chatgpt-image-prompt.md`
3. `Character-References/mrs-na-canonical-flat2d.png` from `Character-References/mrs-na-canonical-flat2d-chatgpt-image-prompt.md`
4. `Character-References/seungjae-canonical-flat2d.png` from `Character-References/seungjae-canonical-flat2d-chatgpt-image-prompt.md`

Reference timing:

- Before final story-cover generation: Nari + Hyun-woo references must be approved.
- Before Page 1: Nari reference must be approved.
- Before Page 2: Nari + Mrs. Na references must be approved.
- Before Page 8: Nari + Seungjae references must be approved.
- Before Page 11: Nari + Hyun-woo references must be approved.
- Pages where Hyun-woo is voice-only do not require his image to be attached and must not draw him physically.

After approval, optionally convert each canonical PNG to WebP. The approved flat-2D images become the permanent active production identity references. The legacy cover is retired from the normal generation input chain.

Do not start a final character-containing asset until the required reference for every visible recurring character on that asset has been approved.

## Canonical Character Identity Authority — Mandatory

Character identity and scene instructions are separate authorities.

For every final generated asset that shows a recurring character, attach that character's APPROVED FLAT-2D CANONICAL VISUAL REFERENCE whenever one exists.

The approved flat-2D canonical visual reference is the absolute authority for WHO the character is. It controls:

- face shape and facial proportions
- eye shape and placement
- nose and mouth shape
- apparent adult age and ethnicity
- hair silhouette, length, shape, and color
- beauty marks and other persistent facial identifiers
- stable adult body proportions
- character-specific persistent accessories/design identifiers
- Hyun-woo's established technical lower-face mask shape and fit
- Hyun-woo's established long low-tied hair silhouette
- Hyun-woo's established broad adult build
- Hyun-woo's approved dense circuit-sigil tattoo map and visual density

The current page `.md` controls WHAT happens: scene, action, pose, expression, wardrobe for that moment, props, dialogue, SFX, panel layout, power state, and environment.

The previous approved interior page controls ongoing page-to-page continuity such as apartment geometry, prop state, rendering density, wardrobe continuity, and current production look. It does NOT outrank the flat-2D canonical character reference for identity.

Never allow the text description, current page prompt, previous page, story cover, legacy cover, or generator preference to recast or reinterpret an approved character identity.

Never average multiple conflicting visual references. Use only approved flat-2D canonical references plus the immediately previous approved interior page. Rejected or drifted generations are never identity references.

Hard character-drift rejection examples:

- Nari with long black hair instead of her established short asymmetrical dark-plum shag
- Nari with a different generic heroine face
- Nari losing her beauty mark or adult game-designer identity
- Hyun-woo with short hair instead of established long black hair tied low
- Hyun-woo with a generic cloth mask instead of the established modern technical lower-face mask
- Hyun-woo with sparse/simplified/newly invented tattoos instead of the approved dense circuit-sigil design
- Hyun-woo with a noticeably slimmer recast build instead of his established broad adult proportions
- Mrs. Na with a youthful/generic face, missing tight silver hair twist/jade earrings, or witch/fantasy styling
- Seungjae with a threatening villain face, wrong brown-hair identity, or a design that resembles Hyun-woo

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
- Only the final approved version of Page N may be attached as the visual continuity reference for Page N+1. A rejected, provisional, or superseded image is never a valid reference.

## Visual Reference Hierarchy

This hierarchy is DOMAIN-SPECIFIC; do not collapse it into one global ranking.

### Character identity

1. Approved flat-2D canonical visual reference for each character shown
2. `characters.md` as textual identity guardrail
3. Previous approved interior page only as secondary continuity evidence

### Scene/action/text

1. Exact current `page-###-chatgpt-image-prompt.md`
2. `chapter.md` when needed for causal verification

### Environment/style/prop continuity

1. `Comics/style-guide.md`
2. exact current page prompt
3. immediately previous approved interior page

For Page 1:

- Attach the approved Nari flat-2D canonical reference.
- Use `characters.md`, `Comics/style-guide.md`, and `page-001-chatgpt-image-prompt.md`.
- There is no previous interior page.
- Record `Reference page: NONE - FLAT-2D CANONICAL CHARACTER REFERENCES + SOURCE LOCKS`.

For Page 2 onward:

- Attach the approved flat-2D canonical visual reference(s) for every recurring character visually shown on that page.
- Attach only the immediately previous APPROVED interior page as the page-to-page continuity reference.
- Use `characters.md`, `Comics/style-guide.md`, and the exact current page prompt.

Use the previous approved interior page to stabilize apartment geometry, furniture, appliances, recurring-prop design/state, wardrobe continuity, line weight, matte palette, rendering density, lettering treatment, and powered/blackout exposure. Do not copy its action, camera angle, panel layout, or dialogue unless the current script explicitly continues that element.

The previous page must never override the flat-2D canonical character reference when faces, hair, mask, tattoos, or body proportions disagree.

Never use the legacy/original cover, any rejected/drifted cover, current/future story covers, front support banners, or back support banners as interior identity/composition/style references. The approved flat-2D canonical character references are the only character identity images in the active production chain.

## Page 1 Benchmark Gate

Page 1 establishes the production benchmark for line art, matte rendering, Unit 2407 geometry, appliance design, prop scale, color treatment, and the first interior presentation of the already-approved flat-2D canonical Nari identity.

Page 1 does NOT create a new Nari identity. It must faithfully reproduce the approved flat-2D canonical Nari reference.

Do not approve Page 1 merely because it is attractive. Approve it only when it correctly preserves the same Nari identity and every locked continuity element. If its face, hair, body proportions, style, scale, environment, or text is wrong, reject and regenerate it before creating Page 2.

## Pre-Generation Gate

- Confirm the frozen story/prompt/reference-lock source baseline is `900eafcb408fc3e429cb429fb3bd18c06ce507ab`.
- Confirm all 18 prompt files exist contiguously with no duplicates or missing number.
- Confirm every required flat-2D canonical character reference for the current page has already been generated and approved.
- Confirm the current page itself contains a `CANONICAL CHARACTER REFERENCE LOCK` section.
- Attach approved flat-2D canonical visual reference(s) for every recurring character visually shown on the page.
- For Page 1, attach no previous interior page.
- For Page 2 onward, attach only the immediately previous approved interior page in addition to the flat-2D canonical character reference(s).
- Confirm the legacy/original cover and rejected/drifted cover are NOT attached.
- Confirm no rejected/superseded/drifted image is attached as an identity or continuity reference.
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

- Reject any face that does not match the approved flat-2D canonical character reference.
- Reject teenage/schoolgirl Nari, long black-haired Nari, changed dark-plum asymmetrical hair, missing beauty mark, missing yellow scrunchie, missing headphones where scripted, glamorous heiress styling, chibi, generic waifu features, or any newly invented heroine face.
- Reject historical/palace/vampire/xianxia/corporate/school-delinquent Hyun-woo, uncovered lower face, changed technical mask, generic cloth mask, short hair, simplified/new tattoo map, noticeably slimmer recast build, neon tattoos, glowing veins, or light beneath skin.
- Reject Mrs. Na if her face/design contradicts her approved canonical reference, including missing tight silver twist, jade earrings, mature age, or practical mauve-coat identity.
- Reject Seungjae if his face/design contradicts his approved canonical reference or begins resembling Hyun-woo.
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

### A. Character Identity

- Compare every visible recurring character directly against the approved flat-2D canonical visual reference, not only against text descriptions.
- Face, adult age, hairstyle, hair color, beauty mark, body proportions, mask, tattoos, accessories, and persistent identifiers must match the flat-2D canonical reference.
- Wardrobe and expression then follow the current page prompt.
- The previous approved page is secondary evidence only; it cannot legitimize character drift.

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

- Page 1: visible first entry and fixed apartment establishment; Nari must match her approved flat-2D canonical visual identity exactly.
- Page 2: Nari + Mrs. Na canonical identities; Mrs. Na arrives/enters, detaches key, defines rule, answers blackout question evasively, leaves; key moves separately.
- Page 3: `ONE WEEK LATER` and mid-page `THAT NIGHT` cards, 19 C thermostat, clean speaker voice during flicker, visible unplug.
- Page 4: unplugged-TV order and separate hostile refrigerator seed.
- Page 5: speaker hiding, paper note, guarded fruit knife, `LATER THAT NIGHT - 1:17 A.M.` card, flicker, `THE NEXT MORNING` card, crumb answer.
- Page 6: nine panels showing two failed photos, hostile corruption, clean warning, missing manual section, Mrs. Na contact, then binder closure/carry/return to counter.
- Page 7: binder begins on counter, only one sheathed practical knife is purchased, fruit knife stays in apartment, realistic retailer, physically possible two-bag entry, safe pantry/desk setup.
- Page 8: Nari + Seungjae canonical identities; comic device sabotage, working car key, completed elevator entry/exit.
- Page 9: 12:43 citywide outage, visible lamp compliance, 81% phone evidence, separate corridor backup.
- Page 10: repeated-test montage, 12:56 card, safe knife draw, connected route, candle holder/trivet/cooking evidence.
- Page 11: Nari + Hyun-woo canonical identities; mask secured before face readability and spacious first reveal.
- Page 12: same canonical Nari/Hyun-woo; last spicy-seafood flavor plus five remaining packets; causal banter.
- Page 13: same canonical Nari/Hyun-woo; no refrigerator reflection; rise/cross/block/warn sequence; hostile name reveal.
- Page 14: same canonical Nari/Hyun-woo; mains-light/candle explanation, blue center, ordered horror reaction, `WARM.` first-touch evidence.
- Page 15: same canonical Nari/Hyun-woo; actor distinction, unit remains dark through dialogue, power snap, next-beat absence.
- Page 16: canonical Nari only; no physical Hyun-woo; lock/latch/log/camera/security/landlord checks before speaker; camera labels only the `OUTAGE INTERVAL`, with no invented return time.
- Page 17: canonical Nari only; Hyun-woo voice-only; borrowed current, safe knife storage, food inspection/hesitation, concise rules.
- Page 18: canonical Nari only; Hyun-woo voice-only; missing-page evasion, danger admission, notebook observation/hypothesis, hostile final TV.

## High-Risk Page Watchlist

Apply an especially strict review to these continuity-heavy pages:

- Canonical preflight: Nari, Hyun-woo, Mrs. Na, and Seungjae flat-2D references must each be approved before the first final asset/page that visually shows them.
- Page 1: canonical Nari face/hair/beauty mark/adult proportions plus Unit 2407 baseline. Page 1 must not invent a new Nari.
- Page 2: canonical Mrs. Na face/age/hair twist/jade earrings/mauve-coat identity plus Nari continuity.
- Page 3: both time cards, `19 C`, speaker plugged then visibly unplugged, clean Hyun-woo signal.
- Page 5: both time cards, key return, speaker/stockpot/towels/lid, guarded fruit knife, 1:17 flicker, physical crumb reply.
- Page 6: two failed photos, hostile corruption, clean warning, binder and missing Section 17, Mrs. Na communication, binder returned to counter.
- Page 8: canonical Seungjae face/hair/office-casual identity, working car key, and harmless jealousy behavior.
- Pages 9-10: 12:43 A.M., 81% phone, device failures, corridor backup outside the apartment, 12:56 A.M., knife/sheath, cooking evidence, candle holder, trivet.
- Pages 11-15: canonical Hyun-woo face/eyes/hair/mask/broad build/tattoo map; physical state, noodle inventory, chair movement, hostile refrigerator, blue candle, ordered shriek/ears/knife/wrist sequence, `WARM.`, clean/broken actor explanation, Unit remaining dark through final dialogue, Hyun-woo absent only after power-on.
- Pages 16-18: canonical Nari identity; no physical/reflected/silhouetted Hyun-woo, locks/security/camera checks, `OUTAGE INTERVAL / FILE ERROR`, borrowed speaker current, knife re-sheathed, food inspection, binder on counter, key in entry tray, notebook retrieved only on Page 18, final hostile TV signature.

## Failure And Change Control

### Do Not Propagate A Bad Page

A page with any unresolved character-identity, environment, appliance, object, power-state, text, SFX, time-card, spoiler, or style error must never become the reference for the next page. If Page 8 fails, do not generate Page 9 from it. Regenerate or correct Page 8 first; only its final approved version may become Page 9's continuity reference.

Character identity drift is a hard failure even if the page is otherwise attractive.

### Regeneration Version Rule

- Rejected or draft versions must remain outside the final reader-facing chapter directory or be removed before final ingestion.
- The final directory must contain only accepted reader-facing names such as `1.png` and `1.webp` through `18.png` and `18.webp`.
- Do not leave ambiguous names such as `7-final.png`, `7-final2.png`, `7-good.webp`, `7-new.png`, or `7-test.png` in the final reader directory.
- Never attach a rejected, draft, superseded, character-drifted, legacy-cover, or rejected-cover image as an identity or continuity reference.

### Markdown Change Stop-Rule

If anyone changes `chapter.md`, `characters.md`, `Comics/style-guide.md`, `Comics/prompt-template.md`, a canonical character-reference prompt/designation, the current or previous page prompt, dialogue, SFX, panel count, chronology, power rules, prop position, wardrobe, device signature, or environment geometry after generation begins:

1. Stop all downstream page generation.
2. Identify every already-generated page affected by the change.
3. Return the changed material and affected pages to QA.
4. Obtain and record a new approved source baseline/reference designation.
5. Regenerate affected pages when necessary.
6. Resume generation sequentially from the earliest affected page.

Never continue silently with mixed Markdown/script versions or mixed character identities.

## Approval Record

Copy and complete this record for each page. A page may be marked `APPROVED` only when every applicable category is `PASS` and the approved file is the final reader-facing version.

```text
PAGE 01
Status: APPROVED / REJECTED
Frozen story/prompt/reference-lock source commit: 900eafcb408fc3e429cb429fb3bd18c06ce507ab
Canonical character reference(s): LIST APPROVED FLAT-2D REFERENCES FOR EVERY RECURRING CHARACTER VISUALLY SHOWN
Reference page: NONE - FLAT-2D CANONICAL CHARACTER REFERENCES + SOURCE LOCKS
Character identity: PASS / FAIL
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

For Page 2 onward, replace `Reference page` with the immediately previous approved interior page while still listing the approved flat-2D canonical character references separately.

The independent final audit passed the story/prompt comparisons. All 18 page prompts contain direct canonical-character-reference locks. Keep this checklist with the prompt set during generation and return the package to `HOLD` if a future Markdown change alters canon, dialogue, panel order, timing, object state, visual rules, page-level reference locks, or canonical flat-2D character-reference authority.
