# Object References

Create individual object packages only for recurring or plot-critical props whose design must stay stable.

Object folders store semantic authorities:

```text
objects/<object-id>/
├── canon.md
└── <object-id>-reference-generation-prompt.md
```

Approved final object WebPs are centralized in:

`manga/02-references/approved-webp/`

Typical name:

`<object-id>-canonical.webp`

Minor related props may share one approved prop atlas when that reduces generation work without harming continuity.

Generate PNG first, review it, then manually convert the exact approved PNG to the centralized WebP. Consult `generation-attachment-map.md` before generation when existing visual authorities are required.
