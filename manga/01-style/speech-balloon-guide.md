# Speech Balloon Guide

## Global Language Rule

Follow:

`manga/01-style/reader-visible-language-lock.md`

All reader-visible speech/thought/caption text in final manga pages is **English only** unless the user explicitly approves a page-specific exception before generation.

Never translate approved English dialogue into Japanese, Korean, Chinese, or another language.

## Balloon Composition

- balloons are part of composition, not text pasted over finished art
- reserve space during panel design
- keep reading order unambiguous
- use ordinary round/oval balloons for normal speech
- use restrained thought/internal-caption treatment only when needed
- use jagged or distorted balloons for shouting or supernatural voice only when story rules support it
- tails must clearly identify speakers
- do not overcrowd faces or key hand actions
- dialogue density should influence panel count before generation

## Layout-Reference Rule

During `page-###-layout-reference` generation:

- dialogue balloons must be **EMPTY**
- thought balloons must be **EMPTY**
- caption boxes should be empty if their placement must be locked
- do not generate placeholder words
- do not generate translated dialogue

The layout reference locks balloon shape, size, tail direction and placement only. Exact English wording comes from the final `page-###-production.md`.

## Final-Page Rule

Final page balloons may contain only the exact approved English wording listed in the page-production MD.

Reject if:

- dialogue is paraphrased
- dialogue is translated
- non-English characters appear
- fake/gibberish text appears
- extra dialogue is invented

No production labels, page instructions, panel IDs, prompt text, or QA notes may appear in reader-facing art.
