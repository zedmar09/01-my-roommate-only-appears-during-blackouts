# Manhwa Lettering and SFX Guide

## Dialogue

Use clean mobile-readable speech balloons with enough padding. Keep tails unambiguous. Do not shrink text to preserve a composition; enlarge/reflow the art instead.

Preserve approved source wording, speaker/source, order, punctuation, capitalization, and text type.

## Narration / Time Captions

Use simple high-contrast boxes integrated into the scene. Time captions should be immediately visible without becoming a separate traditional page card.

## Internal Thoughts

Use a distinct thought treatment. Do not turn internal thought into spoken dialogue.

## Device Text

Device text remains physically on the device display.

Helpful signature: clean stable cyan-white.

Hostile signature: broken/doubled stark-white with black pixel corruption.

Never put device messages in ordinary speech balloons.

## Handwriting

Physical notes use handwritten lettering on the paper object. Repeated appearances of the same note must retain the same wrapping, handwriting scale, placement, and paper design.

## SFX Physical-Logic Gate — Absolute

Every scripted SFX must pass this chain before approval:

`PHYSICAL SOURCE → PHYSICAL ACTION → SCRIPTED SOUND → EXACT TIMING → VISUAL PLACEMENT → STATE CHANGE → NEXT-BEAT CONSEQUENCE`

For every sound, be able to answer:
- **SOURCE:** what exact object/body/environment produces it?
- **ACTION:** what physical action causes it?
- **SOUND:** what exact locked SFX is rendered?
- **TIMING:** at what instant in the action does it occur?
- **PLACEMENT:** where is the lettering anchored so the source is visually unambiguous?
- **STATE CHANGE:** what changes because of that action/sound?
- **CONSEQUENCE:** what state must the next beat inherit?

If any field is unexplained, audit the script and movement before approval. Never use an SFX to hide a missing action or teleport.

## SFX Hierarchy

Quiet/local sounds remain small and source-aligned, including examples such as `BEEP`, `CLICK`, `THUD`, `CLINK`, `YANK`, `SNICK`, `SNAP`, `TCHK`, `SHK`, `PFF`.

Medium event sounds may integrate more strongly, including examples such as `FZZT`, `CLATTER`, `KZZT`, `VRR`, `WHIRR`, `THUNK`, `BIP`, `KSSHT`, `SKRRK`, `CLANG`.

High-intensity scripted sounds such as `KIIIIII` may dominate more strongly but must still leave the source, action, faces, hands, dialogue, and continuity clues readable.

Do not invent filler footsteps, ambience, impacts, device noises, or repeated sounds merely to make the art look busy.

## SFX Placement

Place SFX at the physical source: lock, plug, lamp, pen, device, door, radio, chair, knife impact point, candle action, or other scripted source.

SFX can overlap art but must not hide faces, hands, device text, clues, dialogue, or the action that produces the sound.

A sound that continues offscreen must still have an understandable directional source established by story geography.

## Same-Source Continuity

When a sound repeats from the same physical source across beats, preserve the same object/location unless the script visibly moves it. Repeated SFX must not imply duplicated objects or a new source.

When an impact establishes a persistent location — for example a dropped object hitting a fixed floor spot — the next beats must inherit that location until a visible pickup/movement occurs.

## Seam Safety

All reader-facing words must sit fully inside one technical strip. Artwork may continue across a seam; text may not.

Never split a speech balloon, narration box, handwritten message, device message, or critical SFX word across a technical seam or diagonal divider.

## No Production Text

Never print `V01`, `strip-001`, `SFX`, character labels, prompt labels, crop marks, QA notes, or other production metadata in the artwork.

## Re-Audit Rule

After correcting any dialogue, lettering, SFX, action, or object-state problem, re-audit the corrected beat and both neighboring beats/seams to ensure the repair did not introduce a new ownership, timing, placement, or continuity defect.