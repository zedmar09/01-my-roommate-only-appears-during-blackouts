# Series Manga Style Reference — Generation Prompt

## Status

**TEXT APPROVED — READY FOR FIRST VISUAL GENERATION.**

This is the first image that should be generated for the new manga reference pipeline.

## Output Format Workflow

ChatGPT/image generation should produce this first candidate as:

`series-manga-style-reference.png`

The PNG is an intermediate review artifact only.

After the PNG is visually approved, the user manually converts that exact approved image to the final repository authority:

`manga/01-style/reference-style/series-manga-style-reference.webp`

Do **not** ask the image generator to output WebP directly. The WebP becomes authority only after manual conversion of the approved PNG and repository commit.

See `manga/02-references/image-format-workflow.md`.

## Purpose

Create one original calibration image that locks the **broad black-and-white manga production language** before story characters or environments are generated.

This image controls only visual language:

- hand-drawn ink/sketch feeling
- line-weight behavior
- screentone density
- hatching/cross-hatching
- solid-black placement
- adult face/body rendering
- clothing folds
- background-detail balance
- simplified reaction rendering
- panel-border feeling
- printed-manga texture

It does **not** define Nari, Hyun-woo, any story location, dialogue, or page-specific composition.

## Required Attachment / Text Authorities

Use:

- `manga/01-style/manga-style-lock.md`
- `manga/01-style/page-composition-rules.md`
- `manga/01-style/panel-language.md`
- `manga/01-style/screentone-and-hatching-guide.md`

Do not use retired Manhwa reference images as visual authority.

## Generation Instruction

```text
Create exactly ONE original BLACK-AND-WHITE MANGA VISUAL-LANGUAGE CALIBRATION SHEET in a portrait manga-page family.

OUTPUT FORMAT
Return/generate the first review candidate as PNG. Do not treat the PNG as final repository canon and do not convert it to WebP inside generation. The user will manually convert the exact approved PNG to WebP after visual approval.

This is NOT a story page and must NOT depict any character or location from "My Roommate Only Appears During Blackouts". Use only generic original adult human subjects and generic original interiors/exteriors.

ABSOLUTE MEDIUM
- traditional black-and-white manga drawing
- confident human-drawn pencil/ink impression
- visible natural line variation and slight organic imperfection
- crisp black ink with white paper used actively
- selective solid blacks
- manga screentones for mid-values and atmosphere
- purposeful hatching and cross-hatching
- natural adult anatomy and readable hands
- believable fabric folds and hair strands rendered through line/black/tone rather than glossy gradients
- printed-manga feeling, not polished digital concept art

CALIBRATION CONTENT
Arrange the sheet as a controlled original multi-panel/style-study composition that demonstrates all of the following without becoming a narrative scene:

1. adult head-and-shoulders neutral expression
2. adult 3/4 face with stronger emotion
3. simplified/comedic reaction face using manga abstraction
4. full or 3/4 adult figure showing clothing folds and natural hands
5. close-up of hand interacting with an ordinary object
6. ordinary interior background with furniture/perspective detail
7. quieter low-detail emotional background treatment
8. one darker-value study using screentone + hatching + selective solid blacks while preserving readable forms
9. one small movement/impact example using restrained speed/impact lines
10. examples of clean but not sterile panel borders/gutters

STYLE BALANCE
- characters should look like adults, not school-age/chibi unless the tiny reaction example intentionally simplifies anatomy
- faces attractive but grounded, not glossy fashion illustrations
- backgrounds detailed when spatial context matters, simplified when emotion/reaction is the focus
- do not over-fill every area with tone; preserve clean white areas
- blacks should anchor composition without crushing all shadow detail
- screentones should look like manga value control, not gray digital painting

TEXT
Prefer ZERO readable text. No speech balloons, captions, labels, fake Japanese/Korean lettering, logos, watermarks, signatures, UI, or metadata.

COPYRIGHT / ORIGINALITY LOCK
Do not reproduce, trace, imitate, or closely reconstruct any specific published manga page, character, costume, pose sequence, panel layout, dialogue, logo, or recognizable composition. The goal is only the broad medium language of traditional published black-and-white manga.

ABSOLUTELY REJECT
- any color
- glossy webtoon finish
- cinematic lighting/grade
- bloom, lens flare, volumetric light
- 3D/CG/game-render look
- photorealism or semi-photorealism
- painterly/airbrushed shading
- smooth plastic AI finish
- giant vertical-webtoon blank spaces
- repeated rigid identical panel grid
- copied copyrighted character or recognizable manga panel

FINAL GOAL
A single original portrait-oriented PNG review candidate that can become the reusable style authority after approval and manual conversion to WebP, stabilizing linework, screentone, hatching, black placement, anatomy, background detail, and overall traditional black-and-white manga feeling.
```

## Acceptance Gate

Approve only if the PNG can function as the exact visual source to be manually converted into the reusable WebP style authority without accidentally becoming a story reference.

Reject if:

- any story character/location is implied
- specific existing manga imagery is recognizable
- rendering becomes glossy, cinematic, photoreal, painterly, CGI, or webtoon-like
- screentones/hatching are absent or overused
- adult anatomy/hands are poor
- all panels use the same density/detail level
- the sheet contains invented text/logos/labels

After approval: manually convert the accepted PNG to `series-manga-style-reference.webp`, commit that WebP, then mark the style package `APPROVED` in `manga/02-references/reference-register.md`.
