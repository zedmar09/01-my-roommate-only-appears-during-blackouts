# My Roommate Only Appears During Blackouts

This repository is the active **black-and-white manga** version of the project.

## Active Story Model

There is no book/volume publication layer. Story organization is intentionally simple:

- **Series** — the complete long-form story and canon
- **Arc** — a major narrative problem, mystery phase, or relationship movement
- **Chapter** — one serialized installment inside an arc
- **Page** — the visual storytelling unit used for manga generation

The active project root is `manga/`.

## Production Stack

1. `manga/00-series/` — series concept, world rules, continuity, chronology, relationships, and arc roadmap
2. `manga/01-style/` — black-and-white manga visual grammar and style references
3. `manga/02-references/` — approved character, environment, object, and effect canon packages (`.md` + `.webp`)
4. `manga/03-story/` — arcs and their chapters
5. `manga/04-production/` — one self-contained master production Markdown per chapter plus approved final manga page WebPs

## Single-File Chapter Production

Every production chapter uses exactly one generation-authority Markdown file:

```text
manga/04-production/arc-01/chapter-001/
├── chapter-001-production.md
└── pages/
    ├── page-001.webp
    ├── page-002.webp
    └── ...
```

`chapter-001-production.md` contains the complete chapter-generation package: requirements, approved reference paths, complete generation-ready script, page map, panel instructions, per-page attach sets, complete image-generation prompts, continuity rules, QA gates, and approval status.

No separate page prompt/blueprint/manifest/QA Markdown files are used. The `pages/` folder contains approved page images only.

## Canon Reset

The previous full-color vertical Manhwa production is retired and recoverable only through Git history. The old Chapter 1 sequence is not canon. The title and premise-level supernatural relationship remain, but the story flow, character entrances, reveals, dialogue, and chapter structure are being rebuilt for manga from the beginning.

## Visual Lock

Black-and-white only: hand-drawn pencil/ink impression, variable line weight, screentones, hatching, solid blacks, expressive manga simplification, and story-driven variable panel composition. No full-color webtoon rendering, glossy finish, cinematic grading, photorealism, CGI, or 3D-render look.
