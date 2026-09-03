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

## Generation Format

ChatGPT/image generation should first create PNG review candidates:

```text
<location-id>-master-atlas.png
<location-id>-floor-plan.png        # only when separately generated
```

The PNG files are intermediate review artifacts only. After approval, the user manually converts the exact accepted PNG(s) to the final WebP paths shown above. Only those approved WebPs are stored as repository visual authority.

Use one strong multi-angle atlas whenever possible to reduce image-generation count. Repeated manga pages may change camera, crop, lighting state, and character blocking without changing canonical geometry.
