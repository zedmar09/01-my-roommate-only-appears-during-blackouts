# Chapter 01 Final Audit

Status: **PASS — FINAL PRE-GENERATION GUARD COMPLETE**

This is the current go/no-go audit of the Chapter 1 production package on `main` after the completed Page 1–18 dialogue/continuity rewrite, shared guard cleanup, and the new visible panel-order-marker requirement.

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

## Panel Order Marker Change

The production rule has intentionally changed from the earlier no-number policy.

Every Chapter 1 interior story panel now requires one small circled reader-facing order marker:

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

## Final Verification Matrix

| Area | Result | Verified state |
|---|---|---|
| Page sequence | PASS | Exactly Pages 001–018; no Page 019. |
| Master/story sync | PASS | `chapter.md` remains synchronized to the locked Page 1–18 story/dialogue. |
| Dialogue | PASS | The panel-marker change does not alter approved dialogue, narration, device text, notebook text, or SFX. |
| Panel counts | PASS | Locked counts remain `6, 9, 7, 7, 7, 9, 6, 6, 5, 6, 4, 6, 5, 8, 8, 8, 8, 6`. |
| Panel order markers | PASS | Every page prompt now requires one small circled marker per panel in exact consecutive reading order. |
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

The current requirement is the opposite of the old panel-number rule: **small circled order markers are mandatory on every interior story panel.**

## Final Generation Guard

Chapter 1 is cleared for generation only with strict sequential approval:

1. Generate Page 1 first.
2. Audit it before approval.
3. Verify exact panel count and exact consecutive circled panel markers.
4. Verify marker placement does not cover story content.
5. Verify canonical character identity.
6. Verify environment geometry and object states.
7. Verify exact dialogue/narration/device/notebook text and SFX.
8. Verify correct lighting/power state and clean-vs-hostile device signature.
9. Reject any page with missing, duplicate, skipped, out-of-order, oversized, or obstructive markers.
10. Only an **approved** Page N may become the continuity reference for Page N+1.
11. Never use rejected/provisional/drifted artwork downstream.
12. After Page 18, perform one final Page 1→18 visual continuity audit.

## Final Result

**PASS — Chapter 1's 18-page production package and shared guardrails are aligned with the visible panel-order-marker requirement and cleared for strict sequential image generation.**

This PASS applies to instructions currently on `main`. It does not pre-approve generated artwork; every rendered page still requires post-generation review.
