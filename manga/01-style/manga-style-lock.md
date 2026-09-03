# Manga Style Lock

## Absolute Direction

Final story pages must look like **finished black-and-white 2D hand-drawn manga intended for print**.

This is **not** a rough sketch target. Final pages should have clean, confident manga inking, readable screentone, graphic black-and-white values, conventional panel construction, and expressive 2D manga drawing.

The page must immediately read as a finished manga page — not a cinematic illustration, movie still, painted concept frame, glossy webtoon panel, or 3D render with a manga filter.

## Reader-Visible Language Lock — ABSOLUTE

Follow:

`manga/01-style/reader-visible-language-lock.md`

All reader-visible text is **English only** unless the user explicitly approves a page-specific exception before generation.

Final story pages may contain only the exact English dialogue, narration, thoughts and SFX specified in the current page-production MD.

Never translate approved English text into Japanese, Korean, Chinese, or another language. Never generate fake multilingual glyphs or readable background text that was not explicitly scripted.

For layout-reference generation, speech balloons are empty by default and background text is omitted. The layout reference locks lettering placement, not wording.

## Finished 2D Manga Quality Target

Required:

- clean inked contours with natural pen/brush line-weight variation
- crisp 2D line art; human-drawn character without visible construction lines
- readable facial acting and manga simplification
- finished hair, clothing, hands, props and background linework
- screentone used as a real manga value tool rather than smooth grayscale paint
- hatching/cross-hatching where useful for texture or depth
- flat solid-black ink shapes where graphically appropriate
- white paper/negative space used intentionally
- clean speech balloons integrated into page composition
- conventional right-to-left manga panel flow
- detailed backgrounds when location matters; simplified backgrounds when dialogue/emotion benefits
- natural adult anatomy and readable hands

The desired visual language is the broad quality of a professionally finished black-and-white manga page: **clean 2D ink, screentone, graphic blacks, clear panel rhythm and hand-drawn line character**.

Do not copy any specific copyrighted character, panel, composition, logo or dialogue from a reference manga. Match only broad medium/production qualities.

## Solid Black / Screentone Discipline

Solid black is a normal manga tool and does **not** need to be artificially minimized.

Allowed uses include:

- dark hair or clothing areas
- deep occlusion
- graphic background shapes
- silhouettes when story-approved
- bold panel accents
- night/exterior areas
- strong black-white composition

However, solid black must behave like **flat ink design**, not cinematic lighting.

Do not create:

- soft photographic shadow gradients
- fake HDR contrast
- glossy rendered black surfaces
- giant black vignettes added only for drama
- theatrical shadow wedges across faces on ordinary scenes

Screentone and hatching should remain visibly 2D and print-manga-like. Prefer discrete tone/value decisions over smooth digital light falloff.

## Night Scene Rule

Night scenes may use darker window/exterior areas, black ink masses, screentone and hatching.

The scene should still read as manga drawing, not a low-key film frame.

Indoor spaces remain graphically readable. Darkness comes from ink/tone design, not simulated lens exposure or cinematic light physics.

## Absolute Anti-Cinematic Rule

Reject any result that looks like:

- a movie still
- cinematic storyboard frame
- poster/key art
- painterly concept art
- glossy digital illustration
- photoreal/semi-photoreal grayscale
- 3D/CG render converted to manga

Do not use:

- bloom
- lens flare
- volumetric lighting
- depth-of-field blur
- photographic bokeh
- filmic grading
- realistic studio/rim lighting
- airbrushed gradients
- smooth digital shadow rendering
- simulated camera/lens effects

## Final-Page Reject Conditions

Reject if the page is:

- rough or visibly unfinished
- construction-sketch-like
- scribbly instead of cleanly inked
- color or flat-color webtoon rendering
- glossy
- painterly grayscale
- photorealistic
- CGI/3D-looking
- vector-plastic or mechanically uniform
- dominated by cinematic lighting rather than manga ink/tone
- formatted like a vertical webtoon rather than a conventional manga page

Also reject if:

- any non-English reader-visible text appears
- approved English wording is translated or paraphrased
- fake readable background text appears
- unapproved labels/signs/UI text appear

## Story-Page Style Reference Policy

`series-manga-style-reference-a.webp` and `series-manga-style-reference-b.webp` remain approved reference-development assets, but they are **not automatic story-page attachments**.

For actual story-page generation, follow the exact page-production attachment list. If Style A/B have caused the generator to ignore the Markdown or drift into the wrong finish, omit them.

The final rendering authority for story pages is this text style lock plus the page-specific production Markdown.

## Core Test

Ask during review:

1. **Does this look like a finished 2D black-and-white manga page drawn and inked as manga, or does it look like a cinematic/generated illustration?**
2. **Is every reader-visible word exactly approved English, with no foreign-language or invented text?**

If either test fails, reject it.
