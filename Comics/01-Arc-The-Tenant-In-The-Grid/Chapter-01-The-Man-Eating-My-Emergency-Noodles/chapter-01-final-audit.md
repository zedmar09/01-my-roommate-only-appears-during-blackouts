# Chapter 01 Final Audit

Status: PASS — FINAL PRE-GENERATION AUDIT COMPLETE

This is a fresh final check of the merged Chapter 1 production package on `main`. It supersedes the earlier final-audit PASS that predated the completed Page 1–18 dialogue and continuity rewrite.

## Audited Production Package

- `chapter.md`
- `page-001-chatgpt-image-prompt.md` through `page-018-chatgpt-image-prompt.md`
- `chapter-01-continuity-audit.md`
- `chapter-01-generation-checklist.md`
- canonical character references used by Chapter 1
- `characters.md`
- `Comics/style-guide.md`

Chapter 1 contains exactly **18 story pages**. No `page-019-chatgpt-image-prompt.md` exists.

## Production Content Baseline

Approved story/page-prompt content was merged to `main` at:

`99b4ba51b1f321db0cf57b6464ec6c5279fa43d3`

Subsequent commits refresh QA documentation only; they do not alter the locked story or page-prompt content.

## Independent Verification Matrix

| Area | Result | Verified state |
|---|---|---|
| Page sequence | PASS | Exactly `001` through `018`, contiguous; no Page 019. |
| Master/story sync | PASS | `chapter.md` is synchronized to the locked Page 1–18 story/dialogue. |
| Dialogue | PASS | Reader-facing dialogue is connected, adult, understandable, and matches the approved page-by-page locks. |
| SFX / narration | PASS | SFX sources and large time captions are explicitly defined where required. |
| Panel counts | PASS | `6, 9, 7, 7, 7, 9, 6, 6, 5, 6, 4, 6, 5, 8, 8, 8, 8, 6`. |
| Character references | PASS | Approved canonical PNGs for Nari, Mrs. Na, Seungjae, and Hyun-woo are present on `main`. |
| Character identity locks | PASS | Every page that visually shows a recurring character specifies the required canonical reference(s). |
| Page 8 geography | PASS | Exterior canopy -> same ground-floor lobby -> elevator bank; Nari goes upstairs alone; Seungjae exits; no car-key beat. |
| Page 9 screen rule | PASS | Nari deliberately leaves phone screen dark and tests only flashlight/radio. |
| Page 10–12 spatial lock | PASS | Canonical Hyun-woo is seated at the dining table, not the sink/counter; same chair/table/pot/candle geometry carries through reveal and interrogation. |
| Page 13–15 movement | PASS | Chair push -> rise -> cross -> protective block; candle/knife/wrist sequence is ordered; city returns before Unit 2407; disappearance process is not shown. |
| Page 16 evidence chain | PASS | Door/latch -> entry history -> camera loss -> security -> Mrs. Na voicemail -> same closed cabinet chimes. |
| Page 17 object route | PASS | Same speaker/storage stockpot/towels/lid; phone set on counter; practical knife floor -> desk sheath; food checked before eating. |
| Page 18 ending | PASS | Hyun-woo voice-only; `I CAN'T PROMISE I'M NOT.`; notebook physically retrieved; cautious apartment-power hypothesis; hostile unplugged TV ends on `NEW TENANT CONFIRMED`. |
| Object continuity | PASS | Key, binder, two knives, six-noodle inventory, speaker-storage stockpot vs noodle pot, candle, chair, phone, notebook, TV and refrigerator all have traceable states. |
| Actor signatures | PASS | Hyun-woo/helpful presentation remains clean; hostile presentation remains broken-white/black-pixel corruption. |
| Power rules | PASS | Apartment power, city return, hallway-light rule, no-screen outage behavior, candle exception, physical Hyun-woo, borrowed speaker power, and disappearance trigger agree. |
| Visual style | PASS | Flat 2D human-drawn matte manga/manhwa style is explicitly locked; glossy/cinematic/photoreal/3D/painterly/reflective treatments are rejected. |
| Reader-facing production numbers | PASS | Current prompts explicitly prohibit rendering production panel numbers. |
| Brand/text contamination | PASS | Page prompts guard against extra brands, logos, advertising, fake slogans, random promotional Korean text, and unscripted copy. |
| Spoiler boundary | PASS | Chapter 1 does not reveal hostile-system origin, Hyun-woo origin/accident, future restoration, memory-cost, culprit, sacrifice, or climax. |

## Removed / Obsolete Material Confirmed Absent From Current Production Script

The current production package does not use these superseded reader-facing beats:

- `OUR APARTMENT`
- `RECORD CORRUPTED`
- toaster crumbs forming `TENANT.`
- Page 8 `TOO MANY DEVICES` / car-key exchange
- Page 9 phone activation during outage
- Page 11 fruit-knife joke
- Page 12 `haunting my noodles` exchange
- Page 15 cheap-rent / `THROUGH THE DOOR?` banter

Where old wording is mentioned in an `AVOID`/rejection rule, it is intentionally present only as a guard against regeneration drift.

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

## Final Generation Guard

The story/prompt package is ready for generation **only under strict sequential approval**:

1. Generate one page at a time, Page 1 through Page 18.
2. Use the current page prompt from `main`.
3. Attach only the canonical recurring-character PNGs required by that page.
4. For Page 2 onward, use only the immediately previous **approved** interior page as continuity reference when required.
5. Never use rejected/provisional/drifted artwork downstream.
6. After generation, verify exact panel count, canonical character identity, environment geometry, object positions/states, power state, exact reader-facing text, SFX source, device signature, and flat-matte style.
7. If any guard fails, reject/regenerate that page before continuing.
8. After Page 18, perform one final visual 1->18 continuity audit before declaring the rendered chapter complete.

## Final Result

**PASS — Chapter 1's 18-page Markdown story/prompt package is cleared for strict sequential image generation.**

This PASS applies to the production instructions and continuity package. It does **not** pre-approve future generated images. Every rendered page must still pass the post-generation guard before it may become the continuity reference for the next page.