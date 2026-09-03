# Object References

Create individual object packages only for recurring or plot-critical props whose design must stay stable.

```text
<object-id>/
├── canon.md
├── <object-id>-reference-generation-prompt.md
└── <object-id>-canonical.webp
```

## Generation Format

ChatGPT/image generation should first create:

`<object-id>-canonical.png`

That PNG is the review candidate only. After visual approval, the user manually converts that exact PNG to:

`<object-id>-canonical.webp`

Only the approved WebP becomes repository visual authority.

Minor related props should be grouped into a single approved black-and-white prop atlas when that reduces generation work without harming continuity.
