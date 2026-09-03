# Reader-Visible Language Lock

## Absolute Rule

All reader-visible text in the active manga is **English only** unless the user explicitly approves a page-specific exception before generation.

The image generator must never translate, localize, substitute, or invent another language.

Forbidden by default:

- Japanese text
- Korean text
- Chinese text
- any other non-English script
- pseudo-Japanese / pseudo-Korean / pseudo-Chinese glyphs
- fake multilingual text
- gibberish that resembles readable writing

## Final Story Pages

Final pages may contain only the exact English reader-visible text explicitly approved in the page-production Markdown.

This includes:

- dialogue
- thought balloons
- narration/captions
- SFX
- signs
- labels
- device/UI text
- notes
- letters/messages
- book/manuscript titles
- any other readable lettering

If text is not explicitly required by the page-production MD, **do not generate it**.

Do not paraphrase, translate, rewrite, romanize, or localize approved wording.

## Background Text Default

Background objects should normally contain **no readable text**.

Use blank, abstract, cropped, obscured, or non-legible marks for documents, books, binders, screens, sticky notes, signs and packaging unless readable text is story-required.

If a story-required background label is approved, it must be exact English text listed in the page-production MD.

## Layout References

Layout references are composition authorities, not lettering finals.

Default layout-reference rule:

- speech balloons are **EMPTY**
- captions are omitted unless composition absolutely requires a caption box shape
- SFX text is omitted
- background text is omitted
- signs/labels/UI/documents contain no readable text

The layout reference locks balloon/caption **shape and placement only**. Final English wording is added during final page generation according to `page-###-production.md`.

## SFX

SFX are English / Latin-letter forms only and must match the exact approved script, for example:

- `THUMP`
- `SKRRR`
- `CLICK`
- `TAP`
- `BEEP`
- `BZZT`

Do not convert SFX into Japanese kana/kanji, Korean hangul, Chinese characters, or invented glyphs.

## Numbers

Arabic numerals are allowed when story-required, such as an analog clock face or a specified time display.

Do not add dates, numbers, timestamps, prices, page numbers, addresses or codes unless the production MD explicitly requires them.

## Automatic Rejection

Reject/regenerate any image if:

- any non-English reader-visible text appears
- any approved English line is translated into another language
- any dialogue/SFX differs from the approved English wording
- fake readable background text appears
- unapproved labels, signs, notes, titles or UI text appear
- a layout reference contains generated dialogue instead of empty balloons

## Authority

This file is a global production rule and applies to all active story-page and layout-reference generation unless the user explicitly approves a page-specific exception.
