# Environment References

Create environment references only for locations that need recurring spatial continuity.

Typical package:

```text
<location-id>/
├── canon.md
├── <location-id>-reference-generation-prompt.md
├── <location-id>-master-atlas.webp
├── <location-id>-floor-plan.webp   # optional
└── details/                        # optional
```

Use one strong multi-angle atlas whenever possible to reduce image-generation count. Repeated manga pages may change camera, crop, lighting state, and character blocking without changing canonical geometry.
