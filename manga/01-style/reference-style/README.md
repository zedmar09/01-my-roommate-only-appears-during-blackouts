# Style Reference Images

Store only approved **black-and-white manga style-reference images** here.

Final repository authority format: `.webp`.

## Image Format Workflow

ChatGPT/image generation should first create a PNG review candidate:

`series-manga-style-reference.png`

That PNG is not repository canon. After visual approval, the user manually converts that exact accepted PNG to:

`series-manga-style-reference.webp`

Only the converted WebP becomes the approved series style authority.

See `manga/02-references/image-format-workflow.md`.

## Active Series Style Package

Text generation authority:

`series-manga-style-reference-generation-prompt.md`

First generated candidate:

`series-manga-style-reference.png`

Final approved visual authority after manual conversion:

`series-manga-style-reference.webp`

Approve the style WebP **before** generating Nari or Chapter 001 environment reference images.

## Authority Scope

A style reference controls broad visual language only:

- hand-drawn ink/sketch character rendering
- line-weight variation
- screentone density
- hatching/cross-hatching behavior
- solid-black usage
- background-detail balance
- simplified reaction drawing
- panel-border character
- printed-manga feeling

It does **not** override story canon, character identity, environment geometry, prop identity, dialogue, or page-specific composition.

When a page uses a style-reference image, the exact approved WebP repository path must be listed inside that page's single `page-###-production.md` under its required attachments/references section.

Do not recreate a separate page reference-manifest Markdown file.

## Originality Rule

The series style reference must use generic original subjects and original composition. Never reproduce a specific published manga's characters, dialogue, logo, page, panel sequence, costume, or recognizable exact composition.
