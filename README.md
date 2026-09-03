# My Roommate Only Appears During Blackouts

This repository is the active **black-and-white manga** version of the project.

## Active Story Model

There is no book/volume publication layer. Story organization is intentionally simple:

- **Series** — complete long-form story and canon
- **Arc** — major narrative problem/mystery/relationship movement
- **Chapter** — serialized installment inside an arc
- **Page** — visual storytelling and generation unit

The active project root is `manga/`.

## Production Stack

1. `manga/00-series/` — series concept, world rules, continuity, chronology, relationships, arc roadmap
2. `manga/01-style/` — black-and-white manga visual grammar and style text authorities
3. `manga/02-references/` — semantic character/environment/object/effect authorities plus centralized approved reusable WebPs
4. `manga/03-story/` — arcs and chapters
5. `manga/04-production/` — one self-contained production Markdown per manga page plus final approved page WebPs

## Centralized Reusable WebPs

All approved reusable style/character/environment/object/effect WebPs live in:

`manga/02-references/approved-webp/`

Current approved Chapter 001 references:

- `series-manga-style-reference-a.webp`
- `series-manga-style-reference-b.webp`
- `nari-canonical.webp`

Exact generation attachment sets are recorded in:

`manga/02-references/generation-attachment-map.md`

## Image Format Workflow

1. ChatGPT/image generation creates a `.png` review candidate.
2. The PNG is visually reviewed.
3. If approved, the user manually converts that exact PNG to `.webp`.
4. Reusable approved WebPs are centralized under `manga/02-references/approved-webp/`.
5. Approved final manga page WebPs remain beside their page-production MDs for sequential continuity.

Do not ask image generation to output WebP directly.

See `manga/02-references/image-format-workflow.md`.

## One Page = One Production Markdown

Production is page-based, not one giant chapter prompt.

```text
manga/04-production/arc-01/chapter-001/
├── page-001-production.md
├── page-001.webp
├── page-002-production.md
├── page-002.webp
└── ...
```

Each `page-###-production.md` contains exact attachments, page dimensions, scenario, chronology, event thread, continuity, panel layout, character blocking, actions, reactions, environments, objects/effects, exact dialogue/narration/SFX, deterministic generation instructions, rejection conditions, QA, and approval status.

One page must not be split into separate blueprint, prompt, manifest, script, or QA Markdown files.

## Canon Reset

The previous full-color vertical Manhwa production is retired and recoverable through Git history. The old Chapter 1 sequence is not canon. The title and premise-level supernatural relationship remain, but story flow, character entrances, reveals, dialogue, and chapter structure are rebuilt for manga.

## Visual Lock

Black-and-white only: finished hand-drawn manga ink impression, variable line weight, screentones, hatching, solid blacks, expressive manga simplification, and story-driven variable panel composition. No full-color webtoon rendering, glossy finish, cinematic grading, photorealism, CGI, or 3D-render look.
