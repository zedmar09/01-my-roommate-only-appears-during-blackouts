# Chapter 01 Image Generation Checklist

Status: PASS — PRE-GENERATION GUARD READY

This checklist is the production guard for the final locked Chapter 1 interior sequence: **Pages 001–018**.

## Approved Production Baseline

- Story/prompt content baseline merged to `main`: `99b4ba51b1f321db0cf57b6464ec6c5279fa43d3`.
- Later commits that only refresh QA/audit/checklist documentation do not change the approved story or page-prompt content.
- `chapter.md` is synchronized to `page-001-chatgpt-image-prompt.md` through `page-018-chatgpt-image-prompt.md`.
- Cover/front/back files are outside this interior-page generation sequence.

If any story/dialogue/page-prompt file changes after generation begins, STOP. Re-audit the changed page and every downstream continuity-dependent page before continuing.

## Canonical Character Reference Gate

The following approved PNGs are present on `main` and are the visual identity authority:

- `Character-References/nari-canonical-flat2d.png`
- `Character-References/mrs-na-canonical-flat2d.png`
- `Character-References/seungjae-canonical-flat2d.png`
- `Character-References/hyunwoo-canonical-flat2d.png`

Never use the legacy/original cover, rejected covers, rejected page generations, or unrelated pages as character identity references.

### Required visible-character references

- Page 1: Nari
- Page 2: Nari + Mrs. Na
- Pages 3–7: Nari
- Page 8: Nari + Seungjae
- Page 9: Nari
- Pages 10–15: Nari + Hyun-woo
- Pages 16–18: Nari only; Hyun-woo is physically absent/voice-only and must not be drawn

The current page prompt is authoritative for whether a character is visually present. Do not attach Hyun-woo as a positive visual reference on voice-only Pages 16–18.

## Reference Hierarchy

### Character identity

1. Approved canonical character PNG
2. `characters.md`
3. Previous approved interior page only as secondary continuity evidence

### Scene / action / text

1. Exact current `page-###-chatgpt-image-prompt.md`
2. `chapter.md` for causal cross-check

### Environment / object continuity

1. Exact current page prompt
2. Immediately previous **approved** interior page
3. `Comics/style-guide.md`

A previous page never overrides canonical identity.

## Strict Sequential Generation Rule

Generate and approve only in this order:

`Page 1 -> Page 2 -> Page 3 -> ... -> Page 18`

- Do not batch-generate continuity-dependent future pages from an unapproved predecessor.
- Do not skip an unresolved page.
- Do not use a rejected or provisional page as the next page's continuity reference.
- Only the final approved Page N may be attached as the continuity reference for Page N+1.

## Output Sequence

1. `page-001-chatgpt-image-prompt.md` -> `1.png` -> approved -> `1.webp`
2. `page-002-chatgpt-image-prompt.md` -> `2.png` -> approved -> `2.webp`
3. `page-003-chatgpt-image-prompt.md` -> `3.png` -> approved -> `3.webp`
4. `page-004-chatgpt-image-prompt.md` -> `4.png` -> approved -> `4.webp`
5. `page-005-chatgpt-image-prompt.md` -> `5.png` -> approved -> `5.webp`
6. `page-006-chatgpt-image-prompt.md` -> `6.png` -> approved -> `6.webp`
7. `page-007-chatgpt-image-prompt.md` -> `7.png` -> approved -> `7.webp`
8. `page-008-chatgpt-image-prompt.md` -> `8.png` -> approved -> `8.webp`
9. `page-009-chatgpt-image-prompt.md` -> `9.png` -> approved -> `9.webp`
10. `page-010-chatgpt-image-prompt.md` -> `10.png` -> approved -> `10.webp`
11. `page-011-chatgpt-image-prompt.md` -> `11.png` -> approved -> `11.webp`
12. `page-012-chatgpt-image-prompt.md` -> `12.png` -> approved -> `12.webp`
13. `page-013-chatgpt-image-prompt.md` -> `13.png` -> approved -> `13.webp`
14. `page-014-chatgpt-image-prompt.md` -> `14.png` -> approved -> `14.webp`
15. `page-015-chatgpt-image-prompt.md` -> `15.png` -> approved -> `15.webp`
16. `page-016-chatgpt-image-prompt.md` -> `16.png` -> approved -> `16.webp`
17. `page-017-chatgpt-image-prompt.md` -> `17.png` -> approved -> `17.webp`
18. `page-018-chatgpt-image-prompt.md` -> `18.png` -> approved -> `18.webp`

## Locked Panel Counts

| Page | Panels |
|---:|---:|
| 1 | 6 |
| 2 | 9 |
| 3 | 7 |
| 4 | 7 |
| 5 | 7 |
| 6 | 9 |
| 7 | 6 |
| 8 | 6 |
| 9 | 5 |
| 10 | 6 |
| 11 | 4 |
| 12 | 6 |
| 13 | 5 |
| 14 | 8 |
| 15 | 8 |
| 16 | 8 |
| 17 | 8 |
| 18 | 6 |

Reject any generation with a different panel count.

## Global Pre-Generation Gate — Run Before Every Page

Confirm ALL before generating:

- Correct page prompt from current `main` is being used.
- Exact page number / output filename is correct.
- Required canonical character PNG(s) are attached.
- No legacy/rejected/drifted character or page image is attached.
- For Page 1: no previous interior page is needed.
- For Page 2 onward: attach only the immediately previous **approved** interior page when the prompt calls for continuity.
- Current page prompt's starting subject/object/environment state matches the approved prior page.
- Dialogue, captions, device text, and SFX are copied exactly; no paraphrasing.
- No production panel numbers are meant to appear in finished artwork.
- No unscripted brands, logos, advertisements, promotional Korean text, fake slogans, prices, or dense filler copy.
- No future lore or spoiler content is added.

## Global Style Rejection Gate

Reject any page containing:

- photoreal / semi-photoreal rendering
- glossy webtoon/cinematic rendering
- painterly / airbrushed / 3D-CG treatment
- reflective TV/refrigerator/glass/floor
- bloom, rim light, lens flare, volumetric rays, neon room glow
- wet/shiny/plastic surfaces
- strong gradients or cinematic color grading
- character identity drift

Required look: 100% flat 2D human-drawn modern manga/manhwa, clean ink, matte cel colors, solid blocks, restrained hard-edged shadowing, readable adult faces and environments.

## Character Rejection Gate

### Nari

Reject:

- long black hair / generic heroine hair
- changed face or apparent teenage age
- missing/wrong beauty mark
- wrong canonical dark-plum short asymmetrical shag
- unapproved outfit change
- missing required persistent identifiers where scripted

### Hyun-woo

Reject:

- short hair
- generic cloth mask
- uncovered lower face where prompt requires mask
- slim/recast body instead of canonical broad build
- simplified/new tattoo map
- neon/glowing veins
- physical Hyun-woo on Pages 16–18

### Mrs. Na / Seungjae

Reject any face/hair/age/design that does not match the approved canonical PNG.

## Global Environment Rejection Gate

Reject:

- Unit 2407 geometry changes
- dining table merged with kitchen counter/sink/island
- changed refrigerator body/display/door arrangement
- reflective or redesigned TV
- extra dining chairs where prompt locks exactly two
- random added doors/windows/furniture
- common-area emergency light incorrectly lighting the apartment interior
- unexplained subject teleportation
- object cleanup/movement that has not been scripted

## Critical Object Guard

Track these through all pages:

- brass backup key: entry tray after Page 5 through Page 18
- electrical binder: kitchen counter after Page 6 Panel 9 through Page 18
- guarded fruit knife: under sofa cushion; separate from practical knife
- practical knife: desk tray -> drawn Page 10 -> floor Page 14 -> remains floor Pages 15–16 -> re-sheathed desk Page 17 -> stays desk Page 18
- six noodles: one spicy-seafood + five other flavors; spicy-seafood used during blackout; five unopened remain
- speaker-storage stockpot + two towels + lid: same lower cabinet; separate from noodle cooking pot
- noodle cooking pot + trivet + folded handle cloth: same dining table from Page 10 onward
- candle + ceramic holder: same dining table; extinguished Page 14 and never relit
- Hyun-woo's dining chair: same chair Pages 10–12; pushed back Page 13; stays pushed back through ending
- phone: screen stays dark Page 9; placed on kitchen counter Page 17; remains there Page 18
- A5 notebook: desk until Page 18; physically retrieved and returned to dining table
- TV: visibly unplugged after Page 4; remains unplugged through final hostile activation

## Critical Page-To-Page Guards

### Page 4 -> 5

- No `OUR APARTMENT`.
- No toaster-crumb writing mechanic.
- Page 5 uses the same physical pen to write `NOT THE ONE YOU SHOULD BE AFRAID OF.`

### Page 6

- No reader-facing `RECORD CORRUPTED`.
- Clean warning is `DON'T SAVE THIS DIGITALLY.` / `IT CAN SEE IT.`
- Binder visibly returns to kitchen counter in Panel 9.

### Page 8

- Exterior canopy -> same ground-floor lobby -> same elevator bank.
- Seungjae never enters Unit 2407 or an apartment corridor.
- No car-key beat.
- Elevator remains functional; Nari goes upstairs alone, Seungjae exits.

### Page 9

- Phone screen remains completely dark.
- Nari does not press/wake/unlock phone.
- Practical knife stays sheathed and untouched.

### Pages 10–12 — highest spatial-risk sequence

- Hyun-woo is seated at the **dining table**, never beside the sink/counter/cooktop.
- Use canonical Hyun-woo already on Page 10 while concealing identity by angle/shadow.
- Page 11 starts from the exact Page 10 chair/table/pot/candle position.
- Page 12 keeps Hyun-woo seated in the same chair for all six panels.
- Only Nari takes one cautious step on Page 12.

### Pages 13–15 — movement / power sequence

- Page 13 visibly shows: chair push -> rise -> cross -> protective block.
- Page 14 starts from Page 13 protective position.
- Page 14 order: candle warning -> hostile locking -> blue flame -> blow out -> shriek -> knife drop -> wrist catch.
- Page 15 begins with same wrist contact, then release.
- City power returns outside before Unit 2407.
- Hyun-woo remains physical while Unit 2407 itself is dark.
- Do not show his disappearance process; power-on beat then next beat absent.

### Pages 16–18 — procedural / voice-only sequence

- Hyun-woo must not be physically drawn.
- Page 16 route: disappearance spot -> front door -> lock history -> camera -> security -> Mrs. Na voicemail -> closed cabinet chimes.
- Page 17 starts with same closed cabinet; phone is deliberately placed on kitchen counter; same speaker-storage stockpot/towels/lid are revealed.
- Page 17 knife route: exact floor spot -> hand -> desk sheath; Nari returns to food empty-handed.
- Page 18 begins with same open cabinet and Nari seated at same dining chair.
- Page 18 movement: table -> desk -> table for notebook; no teleportation.
- Final TV remains physically unplugged and uses hostile broken-white/black-pixel signature.

## Device Signature Guard

### Clean / Hyun-woo

- Clean cyan-white text or clean voice treatment.
- No crawling black pixels.
- Physical handwritten Page 5 reply is ordinary handwriting.

### Hostile

- Broken/doubled stark-white glyphs + crawling black pixels/corruption.
- Never render hostile messages as clean cyan.

## Reader-Facing Text Guard

Reject if the image adds, removes, changes, or paraphrases text.

Especially reject recurrence of these removed lines/beats:

- `OUR APARTMENT`
- `RECORD CORRUPTED`
- toaster-crumb `TENANT.`
- Page 8 `TOO MANY DEVICES` / car-key exchange
- Page 9 phone activation
- Page 11 fruit-knife joke
- Page 12 `haunting my noodles` banter
- Page 15 cheap-rent / `THROUGH THE DOOR?` banter

## Post-Generation Approval Gate — Run Before Approving Every Page

Do not approve Page N until all applicable checks pass:

1. **Panel count** matches the locked count.
2. **Character identity** matches canonical PNGs.
3. **Wardrobe/physical state** matches prior approved page and current prompt.
4. **Environment geometry** has not reset or drifted.
5. **Object states/positions** match the continuity ledger.
6. **Movement** is physically understandable; no teleportation.
7. **Power/lighting state** matches the story moment.
8. **Device actor signature** is correct.
9. **Reader-facing text** is exact and complete.
10. **SFX** is attached to the correct physical source.
11. **No reader-facing production panel numbers**.
12. **No extra text/brands/logos/advertising/random Korean copy**.
13. **No spoilers/future lore**.
14. **Style** stays flat matte 2D with no prohibited glossy/cinematic treatment.
15. Page is safe to use as the continuity reference for Page N+1.

If ANY check fails: mark the image REJECTED, do not use it downstream, correct/regenerate Page N, then run this gate again.

## Final Chapter Completion Gate

After Page 18 is approved, perform one final 1->18 image audit for:

- Nari identity consistency across all visible pages
- Mrs. Na / Seungjae / Hyun-woo identity consistency
- Unit 2407 geometry and appliance consistency
- recurring object paths
- time/power continuity
- Page 10–15 subject positioning
- clean-vs-hostile device signatures
- exact dialogue/SFX/lettering
- no accidental extra text or production numbers

Only after that image-level pass should Chapter 1 be considered fully rendered and production-complete.