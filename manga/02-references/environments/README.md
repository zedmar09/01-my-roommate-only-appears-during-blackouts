# Environment References

Create environment references only for locations that need recurring spatial continuity.

Environment folders store semantic authorities:

```text
environments/<location-id>/
├── canon.md
├── <location-id>-reference-generation-prompt.md
└── details/   # optional text/detail authorities
```

Approved final environment WebPs are centralized in:

`manga/02-references/approved-webp/`

Typical names:

- `<location-id>-master-atlas.webp`
- `<location-id>-floor-plan.webp` — optional only when a separate floor-plan authority is needed

Use one strong multi-angle atlas whenever possible to reduce image-generation count. Repeated manga pages may change camera, crop, lighting state, and character blocking without changing canonical geometry.

Generate PNG first, review it, then manually convert the exact approved PNG to the centralized WebP.

Before generating an environment, consult `manga/02-references/generation-attachment-map.md` for the exact approved WebPs to attach.
