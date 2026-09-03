# Character References

Create one folder per recurring character only after the approved story requires that character.

Each character package normally contains:

```text
<character-id>/
├── canon.md
├── <character-id>-reference-generation-prompt.md
├── <character-id>-canonical.webp
└── variants/   # optional
```

## Generation Format

ChatGPT/image generation should first create:

`<character-id>-canonical.png`

That PNG is the visual-review candidate only. After approval, the user manually converts the exact accepted PNG to:

`<character-id>-canonical.webp`

Only the WebP is committed/stored as the final canonical visual authority.

The canonical WebP should be a compact black-and-white manga model sheet/atlas rather than many redundant generations. Character identity must remain stable across pages while pose, expression, temporary clothing, injuries, and scene-specific state come from the chapter/page script.
