# Story Architecture

The story hierarchy is intentionally limited to **arcs and chapters**. There is no volume/publication layer.

```text
03-story/
├── arc-01/
│   ├── arc-bible.md
│   ├── arc-outline.md
│   ├── event-thread-map.md
│   ├── mystery-progression.md
│   └── chapter-001/
│       ├── chapter-outline.md
│       ├── scene-sequence.md
│       ├── parallel-events.md
│       ├── dialogue-script.md
│       ├── page-map.md
│       └── reference-needs.md
└── arc-02/
    └── ...
```

`03-story/` decides **what happens and why**. It does not contain image-generation prompts or rendered pages.

An arc may contain as many chapters as the story needs. Chapter length and page count are story-driven, not fixed quotas.
