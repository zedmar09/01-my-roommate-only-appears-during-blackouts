# Image Generation / Repository Format Workflow

## Rule

All image-generation prompts use a **PNG-first review workflow**.

### ChatGPT / Image Generator Output

The image generator creates the first candidate as PNG, for example:

```text
nari-apartment-master-atlas.png
nari-workplace-master-atlas.png
page-001.png
```

The PNG is an intermediate review artifact only.

### Visual Review

Review the PNG candidate for story accuracy, identity/geometry continuity, anatomy, style, text, composition, and prompt-specific acceptance rules.

Rejected PNGs remain non-canon.

### Manual Conversion After Approval

When a PNG candidate is approved, the user manually converts that exact approved image to WebP.

### Centralized Repository Authority

All approved reference WebPs are stored in one folder:

`manga/02-references/approved-webp/`

Examples:

```text
nari-canonical.png
        ↓ approve + manual convert
manga/02-references/approved-webp/nari-canonical.webp

nari-apartment-master-atlas.png
        ↓ approve + manual convert
manga/02-references/approved-webp/nari-apartment-master-atlas.webp
```

Therefore:

- `.png` = first generation / review candidate
- centralized `.webp` = approved final visual authority

Do not ask ChatGPT/image generation to produce WebP as the first output.

## Current Approved Chapter 001 Visual Authorities

- `manga/02-references/approved-webp/series-manga-style-reference-a.webp`
- `manga/02-references/approved-webp/series-manga-style-reference-b.webp`
- `manga/02-references/approved-webp/nari-canonical.webp`

## Generation Attachment Rule

Before generating any subject, check:

`manga/02-references/generation-attachment-map.md`

Every generation prompt must explicitly list the exact WebPs to attach. Do not attach every available WebP automatically.

## Reference Register Status

- `TEXT APPROVED` — semantic canon/prompt approved; no accepted visual yet
- `VISUAL REVIEW` — generated PNG candidate exists and is under review
- `APPROVED` — the exact approved PNG has been manually converted to WebP, the WebP exists in `approved-webp/`, and the register points to it
- `RETIRED` — no longer valid for new production

## Manga Page Exception

Final approved manga page WebPs may remain beside their `page-###-production.md` because they are sequential page outputs rather than reusable cross-project reference authorities. Reusable style/character/environment/object/effect WebPs belong in `approved-webp/`.
