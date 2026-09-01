# Environment Reference Policy

## Absolute Rule

Environment canonicals belong to LOCATIONS, not chapters.

For every environment used in any Manhwa chapter:
- reuse an already approved canonical pack if the location already exists
- create a new location-named canonical pack only when the story introduces a genuinely new environment
- do not duplicate the same place under chapter-numbered folders
- do not let individual strips independently redesign the same place

## Naming Rule

Use permanent location names such as:
- `Unit-2407/`
- `Building-Shared-Areas/`
- `Nth-Pixel-Studio/`
- `Rooftop/`

Never prefix reusable environment references with `Chapter-01`, `Chapter-02`, etc.

## Generation / Repository Format Rule

Environment image prompts may request PNG as their first local generation output. Keep that generation convention when useful.

After visual approval:
1. manually convert the accepted PNG to WebP
2. commit/store only the approved `.webp` authority in GitHub
3. production Markdown must use the exact committed `.webp` path and basename

Do not point a strip at a deleted PNG or at the Markdown prompt itself.

## Minimum Reference Package

Every new environment gets at least:
1. geometry/orientation reference (floor plan, map, or equivalent)
2. canonical establishing view
3. reverse/secondary view sufficient to prevent axis flips

Recurring/important environments additionally require:
- multi-angle/room-angle atlas
- key-zone detail references
- relevant day/night/power/weather states
- recurring furniture/appliance anchors

## Authority

Approved environment WebPs control architecture, doors/windows, room relationships, fixed furniture/appliances, paths, proportions, materials/colors, and physically valid camera axes.

Character pose and temporary prop state come from the strip/previous approved image; they do not authorize changing architecture.

If a previous strip conflicts with an approved environment canonical, reject/correct the drift rather than carrying it forward.

## Attachment Discipline

Attach only the smallest relevant environment set for the current strip. Too many unrelated environment images can confuse production.

Use the chapter strip manifest as the attachment map, and require each current strip prompt to repeat the exact WebP paths it needs.

## New Chapter Checklist

Before production of a new chapter:
- list every environment
- mark each as `reuse existing canonical` or `new canonical needed`
- generate/approve only genuinely new location packs
- manually convert approved generated PNGs to WebP for repository storage
- record exact approved WebP filenames
- add exact environment WebP attachments to that chapter manifest and strip prompts
- then begin sequential strip generation
