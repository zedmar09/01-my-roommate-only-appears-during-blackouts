# Image Generation / Repository Format Workflow

## Rule

All image-generation prompts in this manga project use a **PNG-first review workflow**.

### ChatGPT / Image Generator Output

The image generator should create the first candidate as **PNG**.

Example:

```text
series-manga-style-reference.png
nari-canonical.png
nari-apartment-master-atlas.png
page-001.png
```

The generated PNG is an **intermediate review artifact only**. It is never the repository's canonical visual authority.

### Visual Review

Review the PNG candidate for story accuracy, identity/geometry continuity, anatomy, style, text, composition, and all package/page acceptance rules.

Rejected PNGs remain non-canon and must not replace an approved authority.

### Manual Conversion After Approval

When a PNG candidate is approved, the user manually converts that exact approved image to WebP.

Example:

```text
series-manga-style-reference.png
        ↓ user manually converts approved candidate
series-manga-style-reference.webp
```

### Repository Authority

Only the manually converted **approved `.webp`** is stored/committed as the reusable or page visual authority.

Therefore:

- `.png` = first generation / review candidate
- `.webp` = approved final repository authority

Do not ask ChatGPT/image generation to produce WebP as the first output. Do not treat an unconverted PNG as an approved repository authority.

## Naming Rule

Use the same basename across the two stages whenever possible:

```text
nari-canonical.png       # generated candidate
nari-canonical.webp      # final approved repository authority

page-001.png             # generated candidate
page-001.webp            # final approved repository authority
```

## Reference Register Status

- `TEXT APPROVED` — semantic canon/prompt approved; no visual candidate yet
- `VISUAL REVIEW` — generated PNG candidate exists and is under review
- `APPROVED` — the exact approved PNG has been manually converted to WebP, the WebP exists in the repository, and the register points to it
- `RETIRED` — no longer valid for new production

This workflow applies to style references, character atlases, environment atlases/floor plans, object/effect references, and final manga pages.