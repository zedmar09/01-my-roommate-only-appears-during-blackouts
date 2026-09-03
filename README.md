# My Roommate Only Appears During Blackouts

This repository is the active **black-and-white manga** version of the project.

## Active Story Model

There is no book/volume publication layer. Story organization is intentionally simple:

- **Series** — the complete long-form story and canon
- **Arc** — a major narrative problem, mystery phase, or relationship movement
- **Chapter** — one serialized installment inside an arc
- **Page** — the visual storytelling and generation unit

The active project root is `manga/`.

## Production Stack

1. `manga/00-series/` — series concept, world rules, continuity, chronology, relationships, and arc roadmap
2. `manga/01-style/` — black-and-white manga visual grammar and style references
3. `manga/02-references/` — character, environment, object, and effect canon packages (`.md` + final approved `.webp` authorities)
4. `manga/03-story/` — arcs and their chapters
5. `manga/04-production/` — one self-contained production Markdown per manga page plus final approved page WebPs

## Image Format Workflow

**ChatGPT/image generation always gives PNG first.**

The project workflow is:

1. generate a `.png` candidate
2. visually review that PNG
3. if approved, the user manually converts that exact PNG to `.webp`
4. only the WebP is stored/committed as final visual authority

So:

- PNG = generated review candidate
- WebP = approved final repository authority

Do not ask image generation to output WebP directly.

See `manga/02-references/image-format-workflow.md`.

## One Page = One Production Markdown

Production is page-based, not one giant chapter prompt.

Final repository structure example:

```text
manga/04-production/arc-01/chapter-001/
├── page-001-production.md
├── page-001.webp
├── page-002-production.md
├── page-002.webp
└── ...
```

Before those WebPs exist, ChatGPT/image generation produces `page-001.png`, `page-002.png`, etc. for review. The user manually converts only the accepted PNGs to the matching WebPs.

Each `page-###-production.md` contains everything required to generate that exact page: required attachments and exact repository paths, PNG candidate filename, final WebP filename, page dimensions/aspect ratio, scenario, chronology, event thread, continuity, panel layout/sizes, character blocking, actions, reactions, environments, objects, effects, exact dialogue/narration/SFX, full deterministic generation instructions, rejection conditions, QA, and approval status.

One page must not be split into separate blueprint, prompt, manifest, script, or QA Markdown files.

The final approved `.webp` sits beside its page-production MD and becomes local visual continuity authority for the next page.

## Canon Reset

The previous full-color vertical Manhwa production is retired and recoverable only through Git history. The old Chapter 1 sequence is not canon. The title and premise-level supernatural relationship remain, but the story flow, character entrances, reveals, dialogue, and chapter structure are being rebuilt for manga from the beginning.

## Visual Lock

Black-and-white only: hand-drawn pencil/ink impression, variable line weight, screentones, hatching, solid blacks, expressive manga simplification, and story-driven variable panel composition. No full-color webtoon rendering, glossy finish, cinematic grading, photorealism, CGI, or 3D-render look.
