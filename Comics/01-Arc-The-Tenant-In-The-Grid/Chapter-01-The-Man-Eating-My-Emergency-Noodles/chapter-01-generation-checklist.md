# Chapter 01 Image Generation Checklist

Status: **PASS — PRE-GENERATION GUARD READY**

This checklist is the production guard for the final locked Chapter 1 interior sequence: **Pages 001–018**.

## Current Production Rule Change

Chapter 1 interior pages now require **visible reader-facing panel-order markers**.

- Render exactly ONE small circled number inside every story panel.
- Number panels consecutively from `1` through the page's locked panel count.
- The numbers follow the exact reading order defined by the page prompt.
- Keep them small, readable, and subtle near the upper-left of the panel or a quiet gutter-edge position.
- Never place them over dialogue, narration, SFX, device text, notebook text, faces, hands, recurring props, or clues.
- Reject missing, duplicated, skipped, out-of-order, oversized, or ambiguous numbers.
- Literal prompt labels such as `PANEL 1`, `PANEL 2`, etc. are still production instructions and must never be printed literally.
- Cover/front/back support assets do not use these markers.

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
| 4 | 1–7 |
| 5 | 1–7 |
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
- correct page/output filename
- required canonical character PNG(s) attached
- only approved prior page used for scene continuity when needed
- exact panel count locked
- exact `1…N` small circled markers required
- starting subject/object/environment state matches prior approved page
- exact dialogue/captions/device text/notebook text/SFX copied without paraphrase
- large in-panel time caption used where scripted
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

Critical object paths:

- brass backup key → entry tray
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

- changes, omits, paraphrases, or invents story text
- omits a panel-order number
- duplicates a panel-order number
- skips a number
- renders numbers out of reading order
- renders numbers too large or over important content
- prints literal production labels such as `PANEL 1`
- adds a page number or unrelated counting marks

Removed story beats must not return, including `OUR APARTMENT`, reader-facing `RECORD CORRUPTED`, toaster-crumb writing, Page 8 car-key beat, Page 9 phone activation, Page 11 fruit-knife joke, Page 12 haunting-noodles banter, and Page 15 cheap-rent/door banter.

## Post-Generation Approval Gate

Do not approve Page N until all applicable checks pass:

1. Exact locked panel count.
2. Exactly one small circled reading-order marker per panel, consecutively `1…N`.
3. Marker placement is subtle and does not obscure story content.
4. Character identity matches canonical PNGs.
5. Wardrobe/physical state matches current/prior approved page.
6. Environment geometry remains consistent.
7. Object states/positions match continuity ledger.
8. Movement is physically understandable; no teleportation.
9. Power/lighting state matches story moment.
10. Device actor signature is correct.
11. Reader-facing story text is exact and complete.
12. SFX is attached to the correct physical source.
13. No extra text/brands/logos/ads/random Korean promotional copy.
14. No spoilers/future lore.
15. Flat matte 2D style is preserved.
16. Page is safe to use as the continuity reference for Page N+1.

If any check fails: REJECT the image, do not use it downstream, correct/regenerate it, then run the gate again.

## Final Chapter Completion Gate

After Page 18 is approved, perform one final Page 1→18 image audit for:

- canonical character consistency
- Unit 2407 geometry/appliance consistency
- recurring object paths
- power/time continuity
- Page 10–15 subject positions
- clean-vs-hostile signatures
- exact story text/SFX
- exact panel counts
- correct small circled `1…N` markers on every page
- no missing/duplicate/out-of-order markers
- no accidental extra text

Only after this visual pass is Chapter 1 fully rendered and production-complete.
