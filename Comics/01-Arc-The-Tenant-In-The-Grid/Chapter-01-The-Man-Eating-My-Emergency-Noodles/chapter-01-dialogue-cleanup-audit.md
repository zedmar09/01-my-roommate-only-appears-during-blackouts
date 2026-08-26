# Chapter 01 Dialogue, SFX, and Script Cleanup Audit

Status: REWRITE RECOMMENDED — VISUAL CONTINUITY IS MOSTLY STRONG, DIALOGUE NEEDS A NATURAL-SPEECH PASS

Scope: Chapter 1 only. `Covers/story_cover*`, `Covers/front*`, and `Covers/back*` are intentionally excluded.

This audit treats the existing Chapter 1 artwork/compositions as expensive assets that should be preserved where possible. The recommended pass therefore changes dialogue, captions, status text only when needed, and a small number of visual/script continuity instructions. Most pages should need bubble/text edits rather than full art regeneration.

Important limitation: the repository contains the 18 page prompts but not the finished Chapter 1 page PNG/WebP files. This audit can verify `chapter.md` against the page prompts, but it cannot verify the final rendered facial expressions, bubble placement, lettering errors, or art drift in the already-generated images.

## Core Findings

1. **The dialogue is structurally consistent but too written.** Many lines correctly answer the preceding line while still sounding like dialogue written to deliver a joke, lore rule, or character trait rather than something an adult would naturally say.
2. **Nari is over-written as a punchline machine.** Her best voice is tired, practical, dry, and analytical. Game/QA jokes should appear occasionally, not in every scene.
3. **Hyun-woo is too quippy during the first danger sequence.** His strongest voice is concise, guarded, practical, and unexpectedly domestic. Reducing banter makes his protective behavior more attractive and the supernatural threat more credible.
4. **Mrs. Na's warning is harder to understand than necessary.** The distinction between apartment mains power, screens, and blackout behavior can be stated in plain language without spoiling the mystery.
5. **Seungjae sounds like a corporate-dialogue placeholder.** His dinner invitation should sound like a normal adult coworker flirting after a late workday.
6. **Some captions repeat what the art already shows.** Keep captions only when they establish time, causality, or information the image cannot communicate by itself.
7. **SFX spelling is inconsistent.** Several effects (`FLIK`, `KLIK`, `SHK`, `TCHK`, `MFF-CHIME`) are harder to parse than the action they represent.
8. **Three prompt-level continuity defects require correction:** Page 1 uses `CORNER VIEW` instead of the chapter's `CORNER WINDOWS`; Page 8 describes entering from rain under a *closed* umbrella; Page 17 says `cabinet lid` when the object is the *stockpot lid*.

## Voice Locks After Cleanup

### Nari
- Practical first, sarcastic second.
- Shorter sentences when frightened.
- Technical language only when she is actively testing/documenting something.
- Avoid repeated game metaphors and prepared-sounding punchlines.

### Hyun-woo
- Short, literal, dry.
- Protective instructions become clearer when danger rises.
- Humor comes from understatement and domestic behavior, not constant comeback lines.
- He should sound like an engineer who dislikes explaining himself, not a mysterious-romance quote generator.

### Mrs. Na
- Plain, specific rules.
- Evasive about *why*, not evasive about the actual safety instruction.

### Seungjae
- Normal adult flirtation.
- Slightly polished, but not full of production jargon.

## Canonical Dialogue Pass by Page

The lines below are the recommended reader-facing copy. Screen/status lines marked **KEEP** should retain their actor-specific visual signature.

### Page 001

- Caption: `UNIT 2407 WAS SUSPICIOUSLY CHEAP.`
- Caption: `IN SEOUL, RENT THIS LOW ALWAYS CAME WITH A CATCH.`
- Panel 4 caption: `TWO BEDROOMS. CORNER WINDOWS. SMART EVERYTHING.`
- Nari: `SO WHAT'S WRONG WITH IT?`
- Recorded speaker: `WELCOME HOME, YOON NARI.`
- Nari: `THERE IT IS.`

Reason: removes the setup/punchline rhythm while keeping Nari's dry suspicion. `CORNER WINDOWS` also matches the prose and environment lock.

### Page 002

- Mrs. Na: `I BROUGHT THE APARTMENT GUIDE.`
- Nari: `THIS PLACE NEEDS A MANUAL?`
- Mrs. Na: `IT DOES.`
- Nari: `ANYTHING I ACTUALLY NEED TO KNOW?`
- Mrs. Na: `AFTER MIDNIGHT, KEEP AT LEAST ONE LIGHT ON.`
- Mrs. Na: `KEEP THE HALLWAY LAMP ON. IT HAS TO USE THE APARTMENT POWER.`
- Nari: `WHY? WHAT HAPPENS IF IT GOES DARK?`
- Nari: `WHAT IF THE BUILDING LOSES POWER?`
- Mrs. Na: `IF THE POWER GOES OUT, KEEP EVERY SCREEN OFF. CALL ME WHEN IT COMES BACK.`
- Mrs. Na: `GOOD NIGHT, MS. YOON.`
- Nari: `NOT REASSURING.`

Reason: removes `IS THERE A BOSS PHASE?` and makes the safety rule understandable on first read without revealing why it exists.

### Page 003

- Nari: `KITCHEN LIGHT ON.`
- Recorded speaker: `I FOUND RESULTS FOR KITCHEN LIGHTING.`
- Nari: `NO. TURN ON THE LIGHT.`
- Hyun-woo speaker voice: `YOU COULD SAY PLEASE.`
- Nari: `WHO SAID THAT?`

Narration may remain, but avoid presenting `IT WAS WORSE / IT WAS OPTIMIZED` as a two-panel punchline if the final art already communicates the automation montage clearly.

Reason: replaces the `KITCHEN BLIGHT` pun with a believable assistant misunderstanding.

### Page 004

- TV: `YOUR PATCH NOTES ARE TOO LONG.` **KEEP** if the existing image already has it; it is acceptable as the first dry Hyun-woo message.
- Nari: `OKAY. WHO ARE YOU?`
- TV: `NOT THE FRIDGE` **KEEP** — this is a useful early actor-separation clue.
- Nari: `NOT HELPFUL. GET OUT.`
- TV: `OUR APARTMENT` **KEEP** — concise and memorable.
- Fridge: `TENANT PROFILE: PENDING` **KEEP HOSTILE SIGNATURE**.

Reason: the clue structure works; only Nari's response needs to sound less scripted.

### Page 005

- Note: `WHO ARE YOU?` **KEEP**.
- Crumb reply: `TENANT.` **KEEP**.

No dialogue rewrite required. The page works because the humor comes from the physical method of reply rather than a verbal punchline.

### Page 006

- Nari: `SAME RESULT.`
- Tablet hostile text: `RECORD CORRUPTED` **KEEP HOSTILE SIGNATURE**.
- Hyun-woo tablet text: `DON'T SAVE THIS DIGITALLY. IT CAN SEE IT.`
- Nari: `IT?`
- Nari text to Mrs. Na: `I UNPLUGGED THE TV. IT STAYED ON. WHAT IS IN UNIT 2407?`
- Mrs. Na text: `KEEP THE HALLWAY LAMP ON. IF THE POWER GOES OUT, KEEP ALL SCREENS OFF. WE'LL TALK IN PERSON.`
- Handwritten manual note: `KEEP ONE MAINS-POWERED LIGHT ON AFTER MIDNIGHT.`

Reason: `REPRODUCIBLE` reads like a character tag rather than natural muttering. `SAME RESULT` preserves her analytical behavior without turning it into a joke.

### Page 007

- Replace caption with: `IF THERE WERE RULES, SHE COULD TEST THEM.`

Reason: keeps Nari's systems-thinking without sounding like a game-development slogan.

### Page 008

- Seungjae: `DINNER SOMETIME? ON A NIGHT WE ACTUALLY LEAVE ON TIME?`
- Seungjae: `WHY DID EVERYTHING DIE AT ONCE?`
- Seungjae: `CAR KEY STILL WORKS. GOOD.`
- Tablet: `TOO MANY DEVICES.`
- Nari: `YOU DID THAT?`
- Tablet: `ONLY THE UNIMPORTANT ONES.`
- Seungjae: `I'LL TEXT YOU WHEN MY PHONE COMES BACK.`
- Nari: `GET HOME FIRST.`

Visual fix: Panel 1 must not say or show them entering from rain **under a closed umbrella**. Show them crossing the lobby threshold while Seungjae is *closing/folding* the umbrella, or show the umbrella open just outside and closed only once they are inside.

Reason: keeps harmless jealousy but removes `LOW POWER MODE / ARE YOU TWELVE? / OLDER`, which reads like a prepared gag.

### Page 009

- Caption: `SEOUL WENT DARK.`
- Caption: `NOT A FLICKER. EVERYTHING OUTSIDE WENT BLACK AT ONCE.`
- Charge caption: `81% TEN MINUTES AGO.`
- Nari: `OF COURSE IT'S AFTER MIDNIGHT.`
- Nari: `COME ON. THE FLASHLIGHT TOO?`

Reason: clearer and less melodramatic than `THE CITY DIED IN ONE BREATH` while retaining scale.

### Page 010

- Caption: `SHE TRIED THEM AGAIN. NOTHING.`
- Nari: `DON'T MOVE. I HAVE A KNIFE.`
- Optional suspense caption: `SHE HADN'T LIT THAT CANDLE.`

Reason: `I AM ARMED` does not sound like what a frightened resident would naturally say to an unknown intruder.

### Page 011

- Hyun-woo: `THE FRUIT KNIFE OR THE BIGGER ONE?`
- Nari: `THE BIGGER ONE. WHO ARE YOU?`
- Hyun-woo: `HYUN-WOO.`

Reason: keeps the unnerving fact that he knows about both knives while making his introduction less formal.

### Page 012

- Nari: `THAT WAS MY LAST SPICY SEAFOOD.`
- Hyun-woo: `YOU HAVE FIVE LEFT.`
- Nari: `DIFFERENT FLAVORS. NOT THE POINT.`
- Hyun-woo: `I WAS HUNGRY.`
- Nari: `HOW DID YOU GET IN?`
- Hyun-woo: `I DIDN'T. I LIVE HERE.`
- Nari: `NO, YOU DON'T. I SIGNED THE LEASE ALONE.`
- Hyun-woo: `MRS. NA SHOULD HAVE TOLD YOU.`
- Nari: `YOU KNOW MRS. NA?`

Visual wording fix: Page 12 should say the dining chair remains **at the table/unchanged**. It is not pushed back until Hyun-woo rises on Page 13.

Reason: removes `FIVE INFERIOR ONES / YOU ARE HAUNTING MY NOODLES / I AM EATING THEM`, the corniest exchange in the chapter, without losing the domestic comedy.

### Page 013

- Hyun-woo: `NARI. LOOK AT ME.`
- Nari: `THE FRIDGE IS OFF.`
- Hyun-woo: `THAT DOESN'T STOP IT. DON'T LOOK AT THE SCREEN.`
- Fridge: `YOON NARI` **KEEP HOSTILE SIGNATURE**.

Reason: `IT DOES NOT NEED ORDINARY POWER. IT IS HUNGRY.` sounds like lore exposition and a horror tagline at the same time. The replacement is immediate, useful, and frightening.

### Page 014

- Hyun-woo: `BLOW OUT THE CANDLE.`
- Nari: `MRS. NA SAID TO KEEP A LIGHT ON.`
- Fridge: `IDENTITY LOCKING` **KEEP HOSTILE SIGNATURE**.
- Hyun-woo: `SHE MEANT THE APARTMENT LIGHTS.`
- Hyun-woo: `THAT FLAME IS HELPING IT FIND YOU.`
- Hyun-woo: `NOW.`
- Nari thought caption: `WARM.` **KEEP** if the art makes the wrist contact unambiguous.
- Hyun-woo: `STAY IN THE DARK UNTIL THE POWER'S BACK.`

Reason: explains the candle/mains distinction in ordinary language and removes formal phrasing during an urgent moment.

### Page 015

This page needs the strongest dialogue rewrite because the existing banter repeatedly interrupts the horror aftermath.

- Nari: `THAT I UNDERSTAND.`
- Hyun-woo: `GOOD.`
- Nari: `WHAT WAS THAT?`
- Hyun-woo: `WHY THIS UNIT IS SO CHEAP.`
- Nari: `I NEED THE REAL ANSWER.`
- Hyun-woo: `YOU WON'T LIKE IT.`
- Nari: `TRY ME.`
- Hyun-woo: `THE CLEAN MESSAGES ARE MINE.`
- Hyun-woo: `THE BROKEN ONES AREN'T. SOMETHING ELSE IS IN THE SYSTEM. IT USES SCREENS TO LEARN WHO YOU ARE.`
- Hyun-woo: `POWER'S COMING BACK.`
- Nari: `WHAT HAPPENS TO YOU?`
- Hyun-woo: `I WON'T BE HERE WHEN IT DOES.`
- Nari: `WHERE DO YOU GO?`
- Hyun-woo: `I DON'T KNOW.`

Reason: removes `I AM IMPROVING`, the cheap-rent punchline construction, `I ALREADY DISLIKE THE SHORT ANSWER`, and the `THROUGH THE DOOR? / TERRIBLE ANSWER` routine. The revised exchange makes Hyun-woo more vulnerable and makes his disappearance land harder.

### Page 016

- Nari: `HYUN-WOO?`
- Lock text: `LAST ENTRY: NARI / NO OTHER ACCESS`
- Camera text: `OUTAGE INTERVAL / FILE ERROR`
- Security voice: `ELEVATORS WERE DOWN THE WHOLE TIME. ONLY THE EMERGENCY LIGHTS WERE ON. NO ONE REPORTED ANYONE ON YOUR FLOOR.`
- Nari, after cabinet chime: `NO.`

Reason: keeps Nari's rational intruder check and makes the security response sound like a person rather than a system status readout.

### Page 017

- Hyun-woo speaker voice: `EAT BEFORE THE NOODLES GET COLD.`
- Nari: `YOU'RE UNPLUGGED.`
- Hyun-woo speaker voice: `BORROWED CURRENT. I CAN'T HOLD IT LONG.`
- Nari: `IS THAT SAFE?`
- Hyun-woo speaker voice: `NOT REALLY. EAT.`
- **Delete** the caption `HUNGER MADE THE FINAL DECISION.` The panel already shows her choosing to eat after checking the food.
- Nari: `GIVE ME ONE USEFUL RULE.`
- Hyun-woo speaker voice: `WRITE THINGS DOWN. PAPER ONLY. DON'T OPEN THE SOUTH-WALL PANEL.`
- Hyun-woo speaker voice: `AFTER MIDNIGHT, KEEP THE HALL LIGHT ON. IF THE POWER GOES OUT, KEEP EVERY SCREEN DARK.`

Visual wording fix: Panel 4 must say **stockpot lid remains propped open; cabinet door remains open**. There is no `cabinet lid`.

Reason: removes `THAT SOUNDS EXPENSIVE` and converts the final rule dump into plain, usable instructions.

### Page 018

- Nari: `THE MISSING SECTION WAS ABOUT THAT PANEL, WASN'T IT?`
- Nari: `ARE YOU DANGEROUS?`
- Hyun-woo speaker voice: `YES. I'M TRYING NOT TO BE.`
- Notebook:
  - `UNIT 2407 - BUG REPORT`
  - `OBSERVATION 001:`
  - `HYUN-WOO BECAME PHYSICAL DURING THE BLACKOUT.`
  - `HYPOTHESIS:`
  - `LOSS OF UNIT POWER MAY BE THE TRIGGER.`
- TV: `NEW TENANT CONFIRMED` **KEEP HOSTILE SIGNATURE**.

Reason: `YES. BUT NOT BY CHOICE.` is a familiar romance/mystery line. `I'M TRYING NOT TO BE` is more human, active, and character-specific. The notebook now separates an observed event from an explicitly uncertain hypothesis in plain language.

## SFX Normalization

Use recognizable sounds and let typography/style make them eerie instead of inventing difficult spellings.

| Current | Recommended | Note |
|---|---|---|
| `WHRR` | `WHIRR` | Curtains/motor. |
| `VRRR` | `VRR` | Robot vacuum. |
| `FLIK` | `FZZT` | Electrical flicker. |
| `SHK` | `SNICK` | Knife guard/sheath action. |
| `KLIK` | `CLICK` | Lamp/switch. |
| `TCHK` | `SNAP` | Mask fastening/strap seating. |
| `KRRR` | `KZZZT` | Corrupted refrigerator activation. |
| `SKRRK` | `SCRAPE` | Chair against floor. |
| `KIIIIII` | `SKREEEEE` | Digital shriek. |
| `VZZT` | `FZZT` | Unit power snap/flicker. |
| `MFF-CHIME` | `DING...` | Render small/muffled from inside cabinet instead of spelling `muffled`. |
| `YANK` | remove if possible | It describes the action more than the sound; the visible unplugging is enough. |

Keep `BEEP`, `CLICK`, `THUD`, `DING-DONG`, `CLINK`, `CLUNK`, `SNAP` (camera), `KZZT`, `ZZT`, `KSSHT`, `SLURP`, `CRINKLE`, `PFF`, `CLANG`, and `CREAK` where their sound source is visually clear.

## Image-Consistency Impact

### Text-only / bubble-only edits
Pages 1-7, 9-16, and 18 can retain their existing panel composition if the generated art otherwise matches the prompt. Dialogue/SFX/caption replacements should be possible as targeted lettering edits.

### Check the existing art before preserving it
- **Page 8:** if the art literally depicts a closed umbrella shielding them from rain, correct the umbrella state. If it already shows them just inside while closing it, only update text.
- **Page 12:** confirm Hyun-woo's chair is still at the table until Page 13.
- **Page 17:** confirm the open object is visually the stockpot lid plus cabinet door, not an invented cabinet lid.

## What Should Not Change

Do not alter these established story/visual locks during the dialogue pass:

- 18-page chapter order and panel counts unless a later lettering edit proves physically impossible.
- Nari, Hyun-woo, Mrs. Na, and Seungjae canonical appearances.
- Mains-power vs supernatural-current rules.
- Clean cyan Hyun-woo signal vs broken-white/black-pixel hostile signal.
- 12:43 A.M. outage and 12:56 A.M. kitchen discovery.
- Six-packet noodle inventory before the blackout; one spicy-seafood packet used, five others remain.
- Two knives with distinct histories: guarded fruit knife under sofa, sheathed practical knife at desk.
- Binder/key/speaker/stockpot/candle/trivet/chair continuity.
- Hyun-woo absent on the first visible beat after Unit 2407 power returns.
- Final hostile `NEW TENANT CONFIRMED` beat.

## Recommended Production Order

1. Treat this file as the temporary dialogue-copy authority.
2. Apply the same replacement lines to `chapter.md` and each corresponding page prompt so prose and generation scripts cannot drift.
3. Edit existing page lettering instead of regenerating art wherever composition is already correct.
4. Re-check Pages 8, 12, and 17 visually for the three non-dialogue continuity defects above.
5. Run a final pass comparing every finished page against the revised prompt, especially speaker tails, actor-specific screen styling, bubble reading order, and SFX source placement.

## Final Assessment

Chapter 1's **story logic is good** and its **object/power continuity is unusually well specified**. The weak point is voice: too many lines are optimized to sound clever, which makes the characters feel less adult and the horror less believable. The revised pass keeps the same plot, romance setup, mystery clues, and generated compositions while making the dialogue shorter, clearer, more natural, and easier to read.