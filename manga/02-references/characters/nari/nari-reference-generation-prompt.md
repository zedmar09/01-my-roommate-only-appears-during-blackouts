# Yoon Nari — Manga Reference Generation Prompt

## Status

**TEXT APPROVED — WAITING FOR SERIES STYLE WEBP APPROVAL.**

Do not generate Nari until this final approved style authority exists:

`manga/01-style/reference-style/series-manga-style-reference.webp`

## Output Format Workflow

ChatGPT/image generation should first create the review candidate as:

`nari-canonical.png`

The PNG is intermediate only. After visual approval, the user manually converts that exact approved PNG to the final repository authority:

`manga/02-references/characters/nari/nari-canonical.webp`

Do not ask the image generator to output WebP directly.

## Required Attachments / Authorities

- `manga/02-references/characters/nari/canon.md`
- `manga/01-style/manga-style-lock.md`
- approved `manga/01-style/reference-style/series-manga-style-reference.webp`

## Generation Instruction

```text
Create exactly ONE reusable BLACK-AND-WHITE MANGA CHARACTER MODEL SHEET / ATLAS for YOON NARI from "My Roommate Only Appears During Blackouts".

OUTPUT FORMAT
Return/generate the first review candidate as PNG. The user will manually convert the exact approved PNG to WebP after visual review. Do not treat the PNG as final repository canon.

This is a production reference sheet, NOT a manga story page, cover, splash illustration, or colored character art.

IDENTITY — ABSOLUTE
- Korean woman, age 30
- approximately 165 cm tall
- natural slim-average adult build
- mature but approachable adult face
- expressive eyes and natural brows
- slightly tired resting expression when overworked
- grounded, practical, observant, dry-humored visual presence
- attractive in a believable ordinary-adult way, NOT model/glamour styling

HAIR — LOCK
- dark hair rendered through black ink/tone, not color identity
- approximately mid-back length
- restrained natural wave toward ends
- normally loose
- include one small secondary view showing a simple low tie for focused work/home tasks
- SAME length/shape/volume across all views
- no short haircut, high ponytail, elaborate braid, fantasy hairstyle, or legacy signature scrunchie

FACE / ACCESSORIES
- no permanent glasses
- no flashy jewelry
- no color-dependent signature accessory
- do not import retired Manhwa facial/accessory design by default

BODY / ANATOMY
- clearly adult proportions
- natural shoulders, waist, hips, arms, legs
- no exaggerated curves
- no fashion-illustration elongation
- hands and feet must be readable and anatomically coherent

PRIMARY WORK OUTFIT
A practical publishing-company editor outfit:
- simple blouse OR modest knit top
- understated cardigan or simple practical jacket
- straight-cut slacks
- simple practical shoes
- no logos, brands, slogans, lanyard text, cyber/tech styling, glamorous heels, or shiny fabrics

PRIMARY HOME OUTFIT
Show a smaller secondary full-body or clear outfit inset:
- loose T-shirt or comfortable long-sleeve top
- relaxed lounge pants
- ordinary at-home presentation
- no fan-service or sleepwear glamour

REQUIRED MODEL-SHEET CONTENT
A. Full-body turnaround in the SAME primary work outfit, complete head-to-feet: front, 3/4 left, left profile, back, 3/4 right.
B. Larger head/shoulder identity angles: front, 3/4, profile, rear hair construction.
C. Expression set: neutral/composed, editorial focus, dry amusement, tired annoyance, skeptical, mild embarrassment, self-doubt/trying to remember, concerned, alert/guarded, grounded fear.
D. Hand/action detail insets: holding/marking a manuscript or proof, holding phone, gripping/moving a dining-chair back, relaxed hand.
E. One home-outfit full-body/inset and one simple low-tie hair variation. These are the same woman, not alternate identities.

MANGA STYLE
Follow the attached approved series manga style reference:
- black-and-white ink only
- natural human-drawn line variation
- selective screentone/hatching
- clean white background for model-sheet readability
- no glossy highlights
- no cinematic lighting
- no painterly grayscale
- no 3D/CG
- no photorealism

COMPOSITION
- one clean unified production atlas
- plain white/light paper background
- enough whitespace to compare silhouettes
- zero readable text preferred
- no speech balloons, SFX, captions, labels, watermarks, signatures, fake UI, or story background

AUTOMATIC REJECT IF
- she looks younger than a believable 30-year-old adult
- face/hair/body changes between angles
- hair becomes short or changes length
- glasses appear as permanent design
- legacy colored-Manhwa accessory styling appears
- workwear reads as tech/game/cyber office costume
- home outfit is sexualized/glamorous
- hands/feet are cropped or malformed in full-body views
- any color/glossy/cinematic/photoreal/3D/painterly rendering appears

FINAL GOAL
A stable reusable black-and-white manga PNG review candidate for Nari. After approval and manual conversion to WebP, it becomes the identity authority supporting ordinary publishing-office scenes, home life, subtle comedy, skeptical investigation, and later supernatural tension without making her look like a technical specialist or action heroine.
```

## Approval Gate

After PNG generation, mark `VISUAL REVIEW` first. Only move to `APPROVED` after verifying identity consistency, adult age, hair geometry, body proportions, work/home outfits, hand quality, and match to the series manga style reference; then manually convert that exact approved PNG to `nari-canonical.webp` and commit the WebP.
