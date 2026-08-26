# Comics

This folder is for the reader-facing graphic version of `My Roommate Only Appears During Blackouts`.

Use it for interior comic pages after a chapter has been adapted from prose into page-and-panel ChatGPT image prompts. Reusable story-level cover/support assets live in `../Covers/`.

All reader-facing interior pages are colored flat 2D human-drawn modern supernatural romance manga/manhwa illustrations. ChatGPT should generate PNG first, then approved PNG files are manually converted to WebP.

## Intended Structure

Use an arc/season folder before every chapter folder. Do not add bare chapter-number folders directly under `Comics`.

```text
Comics/
  style-guide.md
  prompt-template.md
  01-Arc-Or-Season-Name-In-Camel-Case/
    README.md
    Chapter-01-Title-Of-The-Chapter-In-Camel-Case/
      chapter.md
      page-001-chatgpt-image-prompt.md
      1.png
      1.webp
      page-002-chatgpt-image-prompt.md
      2.png
      2.webp
    Chapter-02-Title-Of-The-Chapter-In-Camel-Case/
      chapter.md
      page-001-chatgpt-image-prompt.md
      1.png
      1.webp
  02-Arc-Or-Season-Name-In-Camel-Case/
    README.md
    Chapter-01-Title-Of-The-Chapter-In-Camel-Case/
      chapter.md
      page-001-chatgpt-image-prompt.md
      1.webp
    Chapter-02-Title-Of-The-Chapter-In-Camel-Case/
      chapter.md
      page-001-chatgpt-image-prompt.md
      1.webp
```

## Naming Rules

- Arc/season folder format: `01-Arc-Or-Season-Name-In-Camel-Case`, `02-Arc-Or-Season-Name-In-Camel-Case`, etc.
- Each arc/season folder contains a `README.md` with the readable arc title and chapter list.
- Use either `Arc` or `Season` in the folder name. Do not type `Arc/Season`, because `/` creates another directory.
- Chapter folder format: `Chapter-01-Title-Of-The-Chapter-In-Camel-Case`, `Chapter-02-Title-Of-The-Chapter-In-Camel-Case`, etc.
- Chapter prose file: `chapter.md` inside the matching chapter folder.
- Page prompt files remain `page-001-chatgpt-image-prompt.md`, `page-002-chatgpt-image-prompt.md`, etc.
- ChatGPT page outputs are saved first as `1.png`, `2.png`, `3.png`, etc. inside the matching chapter folder.
- Approved PNG page outputs are manually converted to `1.webp`, `2.webp`, `3.webp`, etc. inside the matching chapter folder.
- Reusable story-level `story_cover`, `front`, and `back` prompts/assets live in `../Covers/`, not inside each chapter folder.
- If an arc or season title is not final yet, use a clear temporary folder name such as `01-Season-01` and rename it before final app ingestion.

## Current Folders

- `Comics/01-Arc-The-Tenant-In-The-Grid/`
- `Comics/01-Arc-The-Tenant-In-The-Grid/README.md`
- `Comics/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/`
- `Comics/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/chapter.md`
- `Comics/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/chapter-01-continuity-audit.md`
- `Comics/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/chapter-01-final-audit.md`
- `Comics/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/chapter-01-generation-checklist.md`
- `Comics/01-Arc-The-Tenant-In-The-Grid/Chapter-01-The-Man-Eating-My-Emergency-Noodles/page-001-chatgpt-image-prompt.md` through `page-014-chatgpt-image-prompt.md`

Shared cover/promotional banner prompts:

- `../Covers/story_cover-chatgpt-image-prompt.md`
- `../Covers/front-chatgpt-image-prompt.md`
- `../Covers/back-chatgpt-image-prompt.md`

Chapter 1 final reader PNG/WebP assets are not present in this working copy yet.

Chapter 2 is planned/referenced, but its folder and files are not present in this working copy yet. Verify or create the chapter folder before making generation prompts for it.

## Production Rules

- Check `../characters.md` before generating or editing any page. From a nested chapter folder, reference it as `../../../characters.md`.
- Check `style-guide.md` before generating or editing any page. From a nested chapter folder, reference it as `../../style-guide.md`.
- Use `prompt-template.md` when creating new page prompts or shared compact KISAH promotional banner Markdown files.
- Put every chapter under the correct numbered arc/season folder, not directly under `Comics/` and not in a bare chapter-number folder.
- Use the prose chapter title in the chapter folder name, and store the prose manuscript there as `chapter.md`.
- Keep `chapter.md`, page prompts, generated PNG/WebP story pages, and future chapter notes together in the same chapter folder.
- Keep the prose manuscript as `chapter.md` inside its matching chapter folder; do not leave prose chapter files at the story root.
- Use `../Covers/front.webp` and `../Covers/back.webp` as the reusable exact 1024 x 768 KISAH promotional banners after manual conversion.
- Use colored flat 2D human-drawn modern supernatural romance manga/manhwa style for reader-facing pages.
- Do not mix black-and-white interiors, grayscale webtoon, glossy rendering, cinematic lighting, painterly concept art, photorealism, 3D rendering, and manga manuscript styles inside the same interior chapter sequence.
- Apply the shared Unit 2407 environment/appliance master lock and lighting/exposure lock to every new page prompt. Appliance bodies and positions stay fixed; only scripted display content may change. Powered scenes use one medium-bright neutral baseline, and blackout scenes remain readable in flat deep-charcoal and muted blue-gray blocks.
- Put every meaningful time jump in a dedicated full-width quiet matte gutter strip before the new scene. The strip contains only centered uppercase time text, receives no panel-order number, and contains no character, object, scenery, dialogue, SFX, inset, gradient, or decoration. Direct-continuation pages explicitly state `NO TIME CARD`.
- Keep the actual panel script, dialogue, captions, device text, glitch text, and SFX inside each `page-###-chatgpt-image-prompt.md` file.
- Keep each prompt self-contained with `CHARACTER CONSISTENCY`, `SETTING AND PROP CONTINUITY`, `SPOILER BOUNDARY`, `PANEL ORDER NUMBERS`, `TEXT AND LETTERING RULES`, `STORY CLARITY`, and `AVOID` blocks.
- Keep Nari's dark-plum asymmetrical shag, yellow scrunchie, headphones, beauty mark, stickered tablet, and practical game-designer silhouette consistent.
- Keep Hyun-woo's black lower-face technical mask, tied-back long hair, glowing circuit-sigil tattoos, dark sleeveless outfit, and protective body language consistent.
- Keep smart-device text readable and minimal: short phrases only, no paragraphs of tiny generated text.
- Keep color accents consistent across interior pages: candlelight is warm matte amber, phone/device glow is cool cyan-white, Hyun-woo's tattoos glow pale blue-white, Nari's hair stays dark plum, and her scrunchie stays yellow.
- If a new recurring character appears, add them to `../characters.md` before generating final pages.
- Generated pages in this folder should be considered the version that readers see in the app.
- Save generated story pages as PNG first, then manually convert approved pages to final WebP files inside the chapter folder (`1.png`, `1.webp`, `2.png`, `2.webp`, etc.).
