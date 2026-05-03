# MakerWorld Description Style Audit and Reusable Listing Template

This document defines a consistent writing style for dark fantasy tabletop miniature listings on MakerWorld. It is meant to keep every new model description clear, searchable, practical for 3D printing, and aligned with the gritty RPG miniature style of the catalog.

## Table of Contents

- [1. Style Audit of Current Model Descriptions](#1-style-audit-of-current-model-descriptions)
- [2. What Is Already Working Well](#2-what-is-already-working-well)
- [3. Main Issues to Fix](#3-main-issues-to-fix)
- [4. Recommended Brand Voice](#4-recommended-brand-voice)
- [5. Standard Listing Structure](#5-standard-listing-structure)
- [6. Short Template for Simple Models](#6-short-template-for-simple-models)
- [7. Premium Template for Important Releases](#7-premium-template-for-important-releases)
- [8. Title Formula](#8-title-formula)
- [9. Tag Bank](#9-tag-bank)
- [10. Repeatable Listing Checklist](#10-repeatable-listing-checklist)
- [11. Best Reusable Wording Blocks](#11-best-reusable-wording-blocks)
- [12. Example Filled Description](#12-example-filled-description)
- [13. Recommended Default Description Length](#13-recommended-default-description-length)

---

## 1. Style Audit of Current Model Descriptions

### Overall Impression

The current descriptions already have a strong identity: dark fantasy, tabletop-ready, painter-friendly, and practical for FDM users. The newer descriptions are noticeably stronger because they combine three things at once:

1. **Story hook:** The model feels like a character, monster, boss, guardian, or encounter piece.
2. **Tabletop use case:** The reader immediately understands where the miniature fits in a campaign.
3. **Print practicality:** The description explains scale, supports, support removal, durability, or profile differences.

The best direction going forward is to keep the cinematic tone, but organize it in a repeatable structure so every listing feels premium and trustworthy.

---

## 2. What Is Already Working Well

### Strong Fantasy Framing

Many descriptions present the miniature as more than an object. They describe role, presence, mood, and encounter use. This works especially well for boss monsters, elite knights, guardians, and beasts.

Good recurring phrases and concepts:

- Commanding presence
- Strong silhouette
- Designed for gameplay and display
- Boss encounter
- Dungeon master use
- Painter-friendly details
- Grounded, imposing, aggressive, vigilant, brutal, noble, corrupted

### Practical Print Information

The strongest listings include direct printing expectations, such as:

- Tabletop scale versus display scale
- Support difficulty
- FDM friendliness
- Durability during gameplay
- Areas that need care during support removal
- Notes about removable bases or pin systems

This builds trust. It also reduces negative comments because users know what to expect before printing.

### Clear Use Cases

The best descriptions tell the buyer or user exactly how to use the model:

- DnD boss encounter
- Pathfinder enemy
- Dungeon crawler monster
- Wargaming proxy
- Display painting project
- NPC, villain, guardian, champion, cult leader, corrupted beast, wilderness threat

This is excellent for SEO and for helping people imagine the miniature in their collection.

---

## 3. Main Issues to Fix

### Issue 1: Structure Changes Too Much Between Models

Some listings are very short and functional, while newer ones are more polished and detailed. This creates an uneven catalog feel.

**Fix:** Use the same core section order every time:

1. One-line hook
2. Main description
3. Design notes
4. Included versions or scale
5. Print notes
6. Game uses
7. Optional creator note
8. Cross-link to another model

### Issue 2: Printing Claims Should Be Precise and Careful

Avoid making claims that could be different on another printer, filament, slicer version, or support setting.

Use:

- Designed for FDM printing
- In my testing
- Support removal is quick with the included profile
- Check your slicer preview before printing
- Results may vary depending on printer calibration and filament

Avoid:

- No supports required on all machines
- Perfect on every printer
- Guaranteed support-free
- Will remove in exactly 3 seconds

### Issue 3: Scale Language Should Be Standardized

Current listings use a mix of 28mm, 28 to 32mm, 32mm, 32mm heroic, tabletop scale, display scale, and large display scale.

**Recommended standard:**

- **Tabletop Scale:** Designed for 28 to 32mm RPG use.
- **Display Scale:** Larger version for painting, collectors, and showcase prints.
- **Large Display Scale:** Optional oversized version for maximum presence.

### Issue 4: Tags Are Useful, But Should Be Cleaner

Avoid duplicate capitalization versions like `RPG`, `rpg`, `DND`, `dnd`, `MINI`, and `mini` unless MakerWorld search clearly benefits from it. A cleaner tag set feels more professional and avoids spammy presentation.

Use 20 to 35 strong tags instead of a giant mixed list.

### Issue 5: Long Separator Lines Look Messy

Very long horizontal separators can make the page feel less polished. Use normal Markdown headings instead.

Use:

```md
## Included Versions

## Print Notes

## Game Uses
```

Avoid:

```md
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
```

### Issue 6: The First 2 Lines Matter Most

The first paragraph should quickly answer:

- What is this model?
- What is its fantasy role?
- Why should someone print it?

Keep the opening compact, search-friendly, and exciting.

---

## 4. Recommended Brand Voice

### Tone

Dark fantasy, practical, confident, and slightly cinematic.

The writing should feel like:

- A tabletop creator presenting a useful encounter piece
- A sculptor explaining why the model prints well
- A DM giving someone a reason to put the miniature on the table

### Avoid Sounding Like

- Generic AI marketing
- Overly epic without practical details
- Too vague about supports or scale
- Too technical without fantasy appeal

### Ideal Voice Formula

**Cinematic hook + sculpt details + gameplay purpose + honest printing notes.**

Example tone:

> This brutal beast is built for dark fantasy encounters where the table needs something heavy, aggressive, and easy to read at a glance. Its compact stance, thick anatomy, and textured details make it useful both as a gameplay miniature and as a fast painting project.

---

## 5. Standard Listing Structure

Use this order for most new models.

```md
# [Model Name] - [Short Category]

[One short hook paragraph. Say what the model is, what role it fills, and why it stands out.]

[Main fantasy description. Mention pose, silhouette, armor/anatomy/clothing, weapon, base, movement, and overall presence. Keep it cinematic but clear.]

[Practical design paragraph. Explain whether it is built for FDM, tabletop use, durability, easy support removal, removable base, thicker anatomy, or display painting.]

## Included Versions

- **Tabletop Scale:** Designed for 28 to 32mm RPG use. Best for regular gameplay, dungeon crawlers, skirmish games, and fast painting.
- **Display Scale:** Larger version for painters, collectors, or showcase prints. More detail is visible, but support removal may require more care.
- **Large Display Scale:** Optional. Use only when included. Best for centerpiece painting or shelf display.

## Print Notes

- **Recommended process:** FDM and/or resin, depending on the model.
- **Layer height:** [0.08mm / 0.12mm / other]
- **Walls and infill:** [2 or 3 walls, 15 to 20% infill]
- **Supports:** [None / light supports / supports required / integrated supports]
- **Support removal:** [Easy / medium / careful removal needed around specific details]
- **Tested on:** [Printer name, if tested]
- **Base:** [Integrated base / removable base / no base / round base / pinned base]

## Game Uses

- DnD or Pathfinder encounter
- Dungeon crawler enemy or NPC
- Wargaming or skirmish proxy
- Boss, elite champion, guardian, beast, cultist, spellcaster, or wilderness threat
- Display painting project

## Creator Note

[Optional short note. Use this for community requests, major redesigns, test print notes, or when the model has an interesting origin. Keep it human and honest.]

## Related Models

If you like this style, you may also want to check out: [Related model name].

## Suggested Tags

[20 to 35 tags, chosen from the tag bank below.]
```

---

## 6. Short Template for Simple Models

Use this for smaller models, quick releases, or models that do not need long lore.

```md
# [Model Name] - Tabletop Miniature

[Model Name] is a [creature/class/character type] designed for dark fantasy tabletop encounters. With [main visual traits], it works well as a [boss/NPC/enemy/hero/guardian/beast] for DnD, Pathfinder, dungeon crawlers, and skirmish games.

The sculpt focuses on [silhouette/detail/anatomy/armor/movement], making it readable at tabletop scale while still giving painters enough texture and detail to enjoy.

## Print Notes

- **Scale:** 28 to 32mm tabletop RPG scale
- **Printing:** [FDM friendly / resin recommended / both FDM and resin]
- **Supports:** [support status]
- **Layer height:** [recommended layer height]
- **Base:** [base type]

## Game Uses

- [Use case 1]
- [Use case 2]
- [Use case 3]
- [Use case 4]
```

---

## 7. Premium Template for Important Releases

Use this for big models, boss monsters, elite knights, display versions, and models with multiple profiles.

```md
# [Model Name] - [Dark Fantasy / RPG / Tabletop] Miniature

[Model Name] is a high-detail [creature/character/class] miniature built for dark fantasy tabletop encounters. [One sentence about the main pose, weapon, anatomy, or visual identity.] It is designed to bring strong presence to DnD, Pathfinder, dungeon crawlers, skirmish games, and display painting projects.

[Fantasy description paragraph. Explain what the miniature represents. Keep it atmospheric, but not too long. Mention where it belongs: cursed sewer, ruined temple, imperial battlefield, forest path, ancient shrine, arena, corrupted wilderness, etc.]

The sculpt emphasizes [strong silhouette / grounded stance / brutal mass / flowing motion / readable armor / painter-friendly texture]. [Mention practical design choices: thick parts, durable details, compact posture, removable base, support-friendly pose, tabletop readability, or FDM-friendly proportions.]

## Included Versions

- **Tabletop Scale:** Optimized for 28 to 32mm RPG gameplay. Best for regular table use, quick painting, and campaign encounters.
- **Display Scale:** Larger version for painters and collectors. More details are visible, but support removal may require more care.
- **Large Display Scale:** [Only include if available.] Oversized version for showcase painting and maximum visual impact.

## Print Notes

- **Recommended layer height:** [0.08mm / 0.12mm]
- **Recommended walls:** [2 / 3]
- **Recommended infill:** [15% / 20%]
- **Supports:** [light / medium / required / integrated / no supports]
- **Support removal:** [easy / medium / careful around weapon, hair, horns, cape, claws, snout, underbelly, etc.]
- **Printer compatibility:** Designed with FDM in mind. Resin may capture finer details.
- **Tested on:** [Bambu Lab A1 Mini / other]

## Game Uses

- Boss encounter or elite enemy
- Dungeon crawler or RPG campaign piece
- Wargaming or skirmish proxy
- Display painting or collection piece
- NPC, guardian, monster, champion, spellcaster, beast, or villain

## Notes

[Optional: mention community inspiration, remix history, update notes, support profile improvement, or base system.]

## Related Models

If you like this style, you may also want to check out: [Related model name].
```

---

## 8. Title Formula

Use a title that is clear, searchable, and not too long.

### Recommended Pattern

```text
[Character/Creature Name] - [Fantasy Role] Tabletop Miniature
```

### Examples

- Imperial Vanguard Knight - Tabletop Miniature
- Dire Boar - Removable Base Tabletop Miniature
- Plague Rat Boss - Fantasy RPG Miniature
- Centaur Spear Guardian - Tabletop Miniature
- Elemental Mindflayer - Boss Miniature
- Temple Knight Commander - RPG Miniature

### Title Rules

- Use one separator style consistently: `-` is the cleanest.
- Avoid mixing `:`, `-`, and parentheses unless the title really needs it.
- Include one strong searchable category: `Tabletop Miniature`, `RPG Miniature`, `Fantasy Miniature`, or `Boss Miniature`.
- Put the most important keyword near the front.

---

## 9. Tag Bank

Do not use every tag. Pick the most relevant 20 to 35 tags.

### Core Tabletop Tags

```text
tabletop, miniature, rpg, dnd, pathfinder, fantasy, tabletop rpg, dungeon crawler, wargame, skirmish, 28mm, 32mm, mini, painting, display, resin, fdm
```

### Knight and Warrior Tags

```text
knight, paladin, warrior, fighter, armored, plate armor, sword, shield, greatsword, cape, helmet, crusader, temple knight, guardian, champion, commander, noble, heroic, medieval
```

### Monster and Boss Tags

```text
monster, boss, boss monster, villain, enemy, creature, dark fantasy, grimdark, horror, dungeon, beast, savage, brutal, corrupted, plague, undead, mutant, encounter
```

### Animal and Beast Tags

```text
boar, dire boar, beast, animal, wilderness, tusks, charge, forest, encounter, monster, creature, tabletop beast
```

### Eldritch and Magic Tags

```text
mindflayer, aberration, eldritch, cthulhu, water, elemental, spellcaster, cult, ancient, summoned, horror, psionic, tentacles, magic, boss encounter
```

### Centaur and Mythic Tags

```text
centaur, spear, guardian, nomad, forest guardian, mythic, cavalry, warrior, plains, hunter, fantasy creature, heroic
```

---

## 10. Repeatable Listing Checklist

Before publishing a new model, check this list.

### Description Checklist

- [ ] The first paragraph says what the model is and where it fits.
- [ ] The description includes at least one clear tabletop use case.
- [ ] The print notes mention supports honestly.
- [ ] Scale is written consistently: 28 to 32mm or display scale.
- [ ] If support removal is easy, the claim is framed as tested or profile-based.
- [ ] Any fragile areas are named clearly.
- [ ] The model's strongest visual selling point is mentioned.
- [ ] The description avoids giant separator lines.
- [ ] Related model link is included when relevant.
- [ ] Tags are relevant and not excessively duplicated.

### Practical Print Checklist

- [ ] Layer height recommendation is included.
- [ ] Wall count and infill are included if useful.
- [ ] Base type is mentioned.
- [ ] Multiple versions are clearly explained.
- [ ] Support difficulty is classified as easy, medium, or careful.
- [ ] FDM versus resin expectations are clear.

---

## 11. Best Reusable Wording Blocks

### For FDM-Friendly Models

> The model was designed with FDM printing in mind, using a compact silhouette, durable shapes, and support-conscious details to keep the print practical for regular tabletop use.

### For Removable Bases

> This version includes a removable round base with alignment pins. Depending on printer tolerance and filament, the pin holes may need a small adjustment for the cleanest fit.

### For Support Removal

> The included profile uses light supports that are quick to remove in testing, but always check your slicer preview and take extra care around thin details.

### For Display Versions

> The display version is scaled larger for painters and collectors. It shows more sculpted detail, but support removal may require more patience than the tabletop version.

### For Boss Monsters

> Whether used as a boss encounter, corrupted beast, or climactic campaign threat, this miniature is designed to command attention as soon as it hits the table.

### For Knights and Elite Warriors

> The sculpt focuses on a grounded stance, strong armor shapes, and a readable silhouette that works equally well for gameplay, painting, and display.

---

## 12. Example Filled Description

```md
# Temple Knight Commander - RPG Tabletop Miniature

The Temple Knight Commander is a high-detail fantasy warrior miniature designed for dark fantasy tabletop encounters. Clad in heavy sacred armor and carrying a massive blade, this model works well as a paladin hero, elite guardian, knight captain, or boss-tier champion for DnD, Pathfinder, dungeon crawlers, and skirmish games.

The sculpt focuses on a grounded stance, strong armor shapes, and a readable silhouette. The layered plate armor, flowing cape, and imposing weapon give the miniature a commanding presence on the table while still offering plenty of detail for painters.

## Included Versions

- **Tabletop Scale:** Designed for 28 to 32mm RPG gameplay. Best for regular table use and campaign encounters.
- **Display Scale:** Larger version for painters, collectors, and showcase prints.

## Print Notes

- **Recommended layer height:** 0.08mm to 0.12mm
- **Supports:** Light supports recommended around the weapon, cape, and overhangs
- **Printing:** Designed with FDM in mind. Resin may capture sharper details.
- **Base:** Round tabletop base included
- **Support removal:** Easy to medium depending on scale and slicer settings

## Game Uses

- Paladin hero or knight commander
- Temple guardian or sacred champion
- Elite enemy, mini boss, or faction leader
- Display painting project

If you like this style, you may also want to check out: [Related model name].
```

---

## 13. Recommended Default Description Length

For most models, aim for:

- **Short/simple model:** 120 to 220 words
- **Standard tabletop miniature:** 220 to 380 words
- **Premium/boss/multiple profiles:** 350 to 550 words

The goal is not to write as much as possible. The goal is to make the model feel useful, printable, and worth downloading within the first few seconds of reading.
