# Chapter 01 Final Audit

Status: **PASS — FINAL PRE-GENERATION GUARD COMPLETE**

This is the final go/no-go audit of the Chapter 1 production package currently on `main` after the completed Page 1–18 dialogue/continuity rewrite **and** the shared generation-guard cleanup.

## Audited Production Package

- `chapter.md`
- `page-001-chatgpt-image-prompt.md` through `page-018-chatgpt-image-prompt.md`
- `chapter-01-continuity-audit.md`
- `chapter-01-generation-checklist.md`
- `characters.md`
- `Comics/style-guide.md`
- `Comics/prompt-template.md`
- approved canonical character references used by Chapter 1

Chapter 1 contains exactly **18 story pages**. There is no Page 019 production prompt.

## Production Baseline

The approved Chapter 1 story and all 18 page prompts were merged into `main` by merge commit:

`99b4ba51b1f321db0cf57b6464ec6c5279fa43d3`

The final guard then found two stale shared-source instructions outside the locked page scripts:

1. `Comics/style-guide.md` still described separate time-card gutters and contained obsolete text examples.
2. `Comics/prompt-template.md` still instructed generators to render circled panel numbers and separate time-card gutters.

Those shared-source conflicts were corrected on `main` in:

- style-guide guard fix: `a81d07e58fa21e64c9b474d9dcf74c3f5f13d03b`
- prompt-template guard fix: `669aa80ada13580631a67246b8e445b1e4f0af19`

The fixes **did not change any approved Chapter 1 reader-facing script or page story beat**. They removed global instructions that could have caused image-generation drift.

## Final Verification Matrix

| Area | Result | Verified state |
|---|---|---|
| Page sequence | PASS | Exactly Pages `001`–`018`; no Page 019. |
| Master/story sync | PASS | `chapter.md` is synchronized to the final locked Page 1–18 story/dialogue. |
| Dialogue | PASS | Approved page-by-page dialogue is connected, natural adult speech, and free of the rejected corny/disconnected exchanges. |
| Narration / time transitions | PASS | Meaningful time jumps use **large noticeable in-panel narration captions**. Shared guides no longer require separate blank time-card gutters. |
| Production numbers | PASS | `PANEL 1`, `PANEL 2`, etc. are prompt-only labels. Finished artwork must contain **no reader-facing panel/circled/page numbers**. |
| Panel counts | PASS | Locked counts: `6, 9, 7, 7, 7, 9, 6, 6, 5, 6, 4, 6, 5, 8, 8, 8, 8, 6`. |
| Canonical identities | PASS | Nari, Mrs. Na, Seungjae, and Hyun-woo use the approved canonical references where visually present. |
| Visual style | PASS | Flat 2D human-drawn matte manga/manhwa; glossy/cinematic/photoreal/3D/painterly/reflective treatments rejected. |
| Unit 2407 geometry | PASS | Living/TV left, dining center, kitchen/refrigerator right, hallway behind; appliance bodies and room geometry stay fixed. |
| Object continuity | PASS | Brass key, binder, two knives, noodle inventory, two separate pots, towels/lid/speaker, candle, chair, phone, notebook, TV, and refrigerator have traceable states. |
| Power logic | PASS | Ordinary Unit 2407 power is distinct from supernatural current; city power can return before unit power; Hyun-woo disappears only when Unit 2407 itself powers back on. |
| Screen rule | PASS | Page 9 keeps Nari's phone screen dark during the outage. |
| Candle rule | PASS | Candle does not replace the protective mains light; on Page 14 it helps the hostile presence locate Nari and is extinguished. |
| Device signatures | PASS | Hyun-woo/helpful communication is clean; hostile communication is broken-white with black-pixel corruption. |
| Page 8 geography | PASS | Exterior canopy → same ground-floor lobby → elevator bank; Nari goes upstairs alone; Seungjae leaves; no car-key beat. |
| Pages 10–12 spatial chain | PASS | Hyun-woo is canonical and seated at the dining table, not sink/counter; same chair/table/pot/candle relationship continues; Page 12 keeps him seated while Nari alone steps. |
| Pages 13–15 movement | PASS | Chair push → rise → cross → protective block; candle/shriek/knife/wrist order is explicit; disappearance process is never visually shown. |
| Page 16 evidence chain | PASS | Door/latch → entry history → camera loss → security → Mrs. Na voicemail → same closed cabinet chimes. |
| Page 17 route | PASS | Same cabinet/storage stockpot/towels/speaker; phone placed on counter; practical knife floor → desk sheath; food checked before eating. |
| Page 18 ending | PASS | Hyun-woo voice-only; `I CAN'T PROMISE I'M NOT.`; notebook physically retrieved; `LOSS OF APARTMENT POWER MAY BE THE TRIGGER.`; hostile unplugged TV ends on `NEW TENANT CONFIRMED`. |
| Brand/text contamination | PASS | No unscripted brands, logos, advertisements, prices, fake slogans, random promotional Korean text, or filler copy. |
| Spoiler boundary | PASS | Chapter 1 does not reveal the hostile system's full origin, Hyun-woo's full origin/accident, restoration cost, culprit, sacrifice, or climax. |

## Obsolete Production Material Guard

Do not regenerate or reintroduce these removed beats:

- `OUR APARTMENT`
- reader-facing `RECORD CORRUPTED`
- toaster-crumb writing / `TENANT.`
- Page 8 `TOO MANY DEVICES` or car-key exchange
- Page 9 phone-screen activation during outage
- Page 11 fruit-knife joke
- Page 12 `haunting my noodles` banter
- Page 15 cheap-rent / `THROUGH THE DOOR?` banter
- `LOSS OF BUILDING POWER REQUIRED.` as Nari's final hypothesis
- separate tiny/full-width time-card gutters for Chapter 1
- rendered panel-order/circled production numbers

Old wording may appear only inside explicit `AVOID`/audit-history text, never as reader-facing production content.

## Final Generation Guard

Chapter 1 is cleared for image generation **only with strict sequential approval**:

1. Generate Page 1 first.
2. Run the post-generation audit before approving it.
3. Only an **approved** Page N may become the continuity reference for Page N+1.
4. Never use rejected/provisional/drifted artwork downstream.
5. For every rendered page verify: exact panel count, canonical identity, wardrobe/subject state, environment geometry, object positions, physical movement, power state, exact text, SFX source, device signature, time-caption treatment, and flat-matte style.
6. Reject any page with extra text, production numbers, object teleportation, environment reset, character drift, wrong device actor signature, or wrong lighting/power logic.
7. After Page 18 is approved, perform one final visual Page 1→18 continuity audit before marking the chapter production-complete.

## Final Result

**PASS — Chapter 1's 18-page Markdown production package and shared generation guardrails are now aligned and cleared for strict sequential image generation.**

This PASS applies to the instructions currently on `main`. It does **not** pre-approve generated artwork. Every rendered page must pass the post-generation guard before the next page is generated.