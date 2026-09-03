# Nari Workplace — Manga Reference Generation Prompt

## Status

**TEXT APPROVED — WAITING FOR SERIES STYLE WEBP APPROVAL.**

Do not generate this environment until the final approved style authority exists:

`manga/01-style/reference-style/series-manga-style-reference.webp`

## Output Format Workflow

ChatGPT/image generation should first create the review candidate as:

`nari-workplace-master-atlas.png`

The PNG is intermediate only. After visual approval, the user manually converts that exact approved PNG to the final repository authority:

`manga/02-references/environments/nari-workplace/nari-workplace-master-atlas.webp`

Do not ask the image generator to output WebP directly.

## Required Attachments / Authorities

- `manga/02-references/environments/nari-workplace/canon.md`
- `manga/01-style/manga-style-lock.md`
- approved `manga/01-style/reference-style/series-manga-style-reference.webp`

## Generation Instruction

```text
Create exactly ONE reusable BLACK-AND-WHITE MANGA ENVIRONMENT MASTER ATLAS for NARI'S WORKPLACE from "My Roommate Only Appears During Blackouts".

OUTPUT FORMAT
Return/generate the first review candidate as PNG. The user will manually convert the exact approved PNG to WebP after visual review. Do not treat the PNG as final repository canon.

This is a spatial production reference, NOT a story page.

WORKPLACE IDENTITY — ABSOLUTE
- contemporary mid-sized publishing company in Seoul
- ordinary professional editorial office
- practical and believable
- NOT software company, game studio, engineering lab, cyberpunk startup, newsroom, luxury headquarters, or detective office

EDITORIAL VISUAL LANGUAGE
The office should naturally contain:
- manuscripts / printed proofs
- correction pages / notebooks / ordinary stationery
- books and reference shelves
- ordinary computers/monitors as tools, not the dominant identity
- coworker desks
- modest printer/copier or publishing-office equipment where useful
- no readable real book titles, author names, publisher logos, or copyrighted covers

RECURRING ZONES — REQUIRED
1. wide establishing view of the editorial open work area
2. Nari's recurring desk and immediate neighboring desks
3. reverse angle showing stable desk/shelf/window relationships
4. books/reference/proof-material area
5. small editorial review/meeting room or modest meeting area
6. daytime version of Nari desk zone with ordinary coworker activity
7. late-night version of the SAME Nari desk zone with fewer people and quiet office atmosphere
8. one useful corridor/transition view only if needed to connect recurring zones

NARI DESK — CONTINUITY LOCK
- give Nari one specific desk location/orientation
- preserve it in all views
- practical manuscript/proof workspace
- do not add personal plot clues
- keep monitors/laptop generic and secondary to editorial materials

DAY / NIGHT CONTINUITY
Daytime and late-night atlas views must be the SAME architecture/furniture arrangement. Only occupancy and ordinary lighting/readability change.

The late-night view must make it believable that Nari can remain at work after most coworkers leave during a deadline, which supports Chapter 001's proof that she is away from home.

MANGA STYLE
Follow the attached approved series manga style reference:
- black-and-white ink
- human-drawn perspective/line character
- screentone/hatching for depth
- selective solid blacks
- no glossy office reflections
- no cinematic grading/bloom
- no photorealism, CGI/3D, or painterly rendering

ATMOSPHERE
- adult professional
- moderately busy, not sterile
- believable paper/book texture
- modest contemporary furniture
- no tech-company gimmicks
- no excessive screens

TEXT
Prefer ZERO readable text. No logos, company names, book titles, manuscript text, signs, watermarks, fake UI, or metadata.

AUTOMATIC REJECT IF
- office reads as software/game/engineering workplace
- manuscripts/books/proofs are absent and screens dominate
- Nari desk location changes between views
- meeting area geometry changes
- late-night view redesigns the office
- environment becomes luxury/futuristic/cyberpunk
- color/glossy/cinematic/photoreal/3D/painterly rendering appears

FINAL GOAL
A stable reusable black-and-white manga PNG review candidate for Nari's publishing office. After approval and manual conversion to WebP, it becomes the environment authority supporting ordinary editorial life, coworker scenes, manuscript/proof work, daytime activity, and Chapter 001 late-night timeline proof.
```

## Approval Gate

Mark the PNG `VISUAL REVIEW` first. Approve only when geometry is stable, the publishing identity is immediately readable without text, and the image matches the approved series manga style reference. After approval, manually convert the exact accepted PNG to `nari-workplace-master-atlas.webp`, commit that WebP, then mark the package `APPROVED`.
