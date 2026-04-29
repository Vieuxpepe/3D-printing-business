# FDM Supportless Miniature Design Rules

**Repository:** 3D-printing-business  
**Category:** Market research / technical design rules  
**Target platform:** MakerWorld  
**Target printer:** Bambu Lab A1 Mini  
**Primary audience:** FDM users who want reliable tabletop miniatures with minimal cleanup

---

## Executive Summary

For a MakerWorld creator using a Bambu Lab A1 Mini, the strongest direction is not to chase resin-level detail at all costs. The better opportunity is to design miniatures that are:

- Supportless or nearly supportless
- Reliable with the stock 0.4 mm nozzle
- Readable from tabletop distance
- Durable enough for handling
- Easy to print with included 3MF profiles
- Clear enough to paint without requiring resin-quality micro-detail

The core business advantage is simple: a model that prints cleanly on a common FDM setup can outperform a more detailed sculpt that fails, needs heavy supports, or breaks during handling.

The most important design pattern is:

> **Strong silhouette first, printable geometry second, micro-detail last.**

On MakerWorld, listings that emphasize supportless printing, 0.4 mm and 0.2 mm nozzle compatibility, real printed photos, and plug-and-play 3MF profiles are easier for users to trust. The supportless promise needs to be true in the STL, in the slicer preview, and in the uploaded print profile.

---

## Strategic Recommendation

The best direction for your 3D modeling business is:

> **FDM-friendly fantasy tabletop models: supportless 28 mm and 32 mm minis, designed first for 0.4 mm nozzles, with optional 0.2 mm premium profiles.**

Recommended product types:

1. **Supportless fantasy enemy packs**
   - Goblins
   - Bandits
   - Skeletons
   - Orcs
   - Guards
   - Cultists

2. **Supportless NPC utility packs**
   - Merchants
   - Blacksmiths
   - Tavern NPCs
   - Prisoners
   - Nobles
   - Villagers

3. **Supportless knight and medieval soldier packs**
   - This aligns with your current best sellers
   - Strong market fit with your existing direction
   - Easier to make a recognizable brand around

4. **FDM-optimized boss or hero models**
   - Best at 32 mm or 40 mm
   - Use only when the design justifies extra print time
   - Consider splitting large weapons, wings, or capes if supportless geometry would hurt the look

---

## Core Design Rules

### 1. Design for the stock 0.4 mm nozzle first

The A1 Mini ships with a 0.4 mm nozzle. Bambu Lab offers 0.2 mm nozzles, and its own documentation notes that 0.2 mm is useful for tabletop miniatures, but the 0.2 mm nozzle is slower, more clog-prone, and produces weaker fine features than larger nozzles.

**Business rule:**

> If the model only works well with a 0.2 mm nozzle, it should be considered a premium variant, not the default product.

Practical target:

- Main profile: 0.4 mm nozzle
- Premium detail profile: 0.2 mm nozzle
- Main scale: 28 mm or 32 mm
- Optional showcase scale: 40 mm

Sources:

- Bambu Lab A1 Mini technical specs: https://bambulab.com/en/a1-mini/tech-specs
- Bambu Lab 0.2 mm nozzle FAQ: https://wiki.bambulab.com/en/knowledge-sharing/02-mm-nozzle-FAQ

---

### 2. Avoid unsupported horizontal surfaces

A supportless miniature should avoid large flat undersides. Capes, arms, weapons, shields, jaws, beards, tails, and monster bellies should not create long unsupported ceilings.

Good geometry:

- Sloped cape undersides
- Arms angled downward or inward
- Weapons tilted vertically or connected to the base
- Beards merged into the chest
- Tails touching the ground or the base
- Cloaks that flow into rocks, cloth folds, or the base

Bad geometry:

- Horizontal swords floating in the air
- Wide flat cape undersides
- Arms extended straight sideways
- Thin staffs held far away from the body
- Wings extending outward without cuts or support strategy

Design rule:

> Turn ceilings into ramps. Turn floating details into anchored details.

Sources:

- Prusa modeling for 3D printing guide: https://help.prusa3d.com/article/modeling-with-3d-printing-in-mind_164135
- Bambu Lab overhang guide: https://wiki.bambulab.com/en/filament-acc/filament/print-quality/overhang

---

### 3. Use double anchoring for fragile features

Fragile details print and survive better when connected to more than one point.

Examples:

| Feature | Weak version | Better FDM version |
|---|---|---|
| Sword | Thin sword held outward | Sword tip touches base or shield |
| Staff | Isolated staff in one hand | Staff touches base and hand |
| Cape | Floating cape edge | Cape touches base or leg |
| Bow | Thin curved bow away from body | Bow connected to cloak or quiver |
| Horns | Long thin horns | Shorter, thicker horns angled upward |
| Tail | Tail floating behind body | Tail touches ground, rock, or base |

Design rule:

> If a detail is thin, give it a second contact point.

This matters especially for weapons, ankles, staffs, fingers, capes, horns, and tails.

---

### 4. Prefer closed poses over open poses

Open poses look dramatic in renders, but they are harder to print on FDM. Supportless miniatures usually perform better with compact poses.

Better supportless pose traits:

- Arms closer to torso
- Weapons vertical, diagonal, or touching the base
- Legs not too far apart
- Cape flowing downward into the base
- Shield close to the body
- Head and hair shaped with downward-printable forms

Risky pose traits:

- Wide T-pose arms
- Spear held horizontally
- Sword pointing straight sideways
- Bow fully extended away from body
- Flying creatures with thin legs or wing tips unsupported

Design rule:

> Make the silhouette dramatic, but keep the geometry compact.

This is especially important for MakerWorld users who expect a model to print successfully with minimal tuning.

---

### 5. Exaggerate medium details, not micro-details

FDM does not reward ultra-fine resin sculpting at miniature scale. The details that matter most are the ones visible after slicing.

Details that work well:

- Large armor plates
- Thick belts and pouches
- Big cloak folds
- Strong helmet shapes
- Large hair clumps
- Bold shoulder armor
- Thick weapon silhouettes
- Clear face planes instead of tiny facial features

Details that often disappear or print poorly:

- Tiny chainmail
- Micro-runes
- Thin individual fingers
- Fine jewelry
- Thin teeth
- Tiny fur strands
- Very small facial wrinkles

Design rule:

> Sculpt details that are readable from 30 to 60 cm away on a table.

---

### 6. Avoid thin structural elements

A detail can be technically printable and still be too fragile. For 0.4 mm nozzle FDM miniatures, structural features should generally be thicker than a single extrusion line.

Practical thickness targets:

| Element | Recommended minimum for 0.4 mm nozzle |
|---|---:|
| Weapon shafts | 1.0 to 1.2 mm |
| Swords | 1.0 mm or thicker at the thinnest point |
| Ankles | 1.2 mm or thicker if possible |
| Horns | 1.0 mm or thicker at the base |
| Fingers | Better merged into mitten-like readable shapes |
| Cape edges | Avoid paper-thin edges, use tapered but printable thickness |
| Staffs and spears | 1.2 mm or connect to body/base |

These are practical design targets, not universal laws. The exact result depends on filament, slicer, orientation, cooling, and scale.

Source:

- Bambu Lab line width documentation: https://wiki.bambulab.com/en/software/bambu-studio/parameter/line-width

---

### 7. Use bases as structural tools

The base is not just a display platform. It can solve several FDM problems.

A good supportless miniature base should:

- Stabilize the model
- Improve bed adhesion
- Anchor weapons, staffs, tails, capes, and robes
- Hide supportless design tricks
- Give the model a stronger tabletop presence

Recommended base approach:

- 25 mm base for many 28 mm humanoids
- 28 to 32 mm base for larger humanoids or dynamic poses
- 40 mm or larger for monsters and bosses
- Use shallow texture, not extreme rocky overhangs
- Avoid very thin base rims
- Consider magnet holes only if they do not weaken the base

Design rule:

> Make the base part of the engineering, not just decoration.

---

### 8. Split models only when it creates a better user experience

Supportless does not always mean one-piece. Sometimes a carefully split model is better than a one-piece model that needs ugly supports or loses detail.

Split when:

- A wing creates ugly underside geometry
- A cape would need heavy support
- A large weapon ruins supportless posing
- A monster tail creates a long unsupported bridge
- The best orientation for the body is bad for the weapon

Do not split when:

- The model prints cleanly as one piece
- Assembly would frustrate users
- The split line is very visible
- The part is too small to glue comfortably

Good split locations:

- Shoulder joints
- Wrist or weapon hand
- Cape attachment seam
- Wing root
- Tail root
- Large shield connection
- Scenic base connection

Source:

- Bambu Studio cut tool documentation: https://wiki.bambulab.com/en/software/bambu-studio/cut-tool

---

## Scale Recommendations

### 28 mm

Best for:

- Enemy packs
- Town guards
- NPC packs
- Goblins, skeletons, bandits, soldiers
- Fast MakerWorld releases

Pros:

- Familiar tabletop scale
- Faster prints
- Good for packs
- Lower filament use

Cons:

- Harder to show face detail
- Fragile weapons need exaggeration
- Micro-detail is often lost

Verdict:

> Best default scale for volume products and packs.

---

### 32 mm

Best for:

- Player characters
- Knights
- Premium NPCs
- Stronger tabletop presence
- Easier painting

Pros:

- Better readability
- More forgiving for details
- Good balance between size and print time

Cons:

- Takes longer than 28 mm
- Slightly less universal for some tabletop collections

Verdict:

> Best premium scale for heroes, knights, and named characters.

---

### 40 mm

Best for:

- Bosses
- Showcase versions
- Large monsters
- Painting-friendly variants

Pros:

- Details read better
- Easier to paint
- Stronger listing thumbnails

Cons:

- Longer print times
- Layer lines become more visible on smooth helmets, domes, and large curved surfaces
- Not ideal for every DnD table

Verdict:

> Use selectively for models where the extra size increases perceived value.

---

## Recommended Slicer Profiles for A1 Mini

These are practical starting points, not perfect universal presets.

### Stock 0.4 mm profile

Use for most public MakerWorld releases.

Recommended settings:

| Setting | Starting point |
|---|---:|
| Nozzle | 0.4 mm |
| Layer height | 0.08 mm for detail, 0.12 mm for faster packs |
| Walls | 2 to 3 |
| Infill | 15% to 25%, or 100% for tiny simple minis if it improves reliability |
| Supports | Off for supportless listings |
| Wall generator | Arachne as starting point |
| Outer wall speed | 30 to 45 mm/s |
| Small feature speed | 20 to 30 mm/s |
| Seam | Avoid random seam on visible face |
| Brim | Use brim ears or small brim when tall and narrow |

Best use:

- 28 mm enemy packs
- NPCs
- Guards
- Skeletons
- Bandits
- Functional tabletop pieces

---

### Optional 0.2 mm profile

Use for premium versions or detail-focused users.

Recommended settings:

| Setting | Starting point |
|---|---:|
| Nozzle | 0.2 mm |
| Layer height | 0.06 mm default, 0.04 mm only for showcase testing |
| Walls | 3 if details are fragile |
| Speed | Slower than 0.4 mm profile |
| Supports | Off if listed as supportless |
| Filament | Dry PLA or PLA matte |
| Calibration | Strongly recommended before publishing profile |

Important caution:

0.2 mm nozzles produce better visual detail, but they are more sensitive to clogs, moisture, filament quality, and calibration. They should not be the only profile for a product unless the model truly requires it.

Sources:

- Bambu 0.2 mm nozzle FAQ: https://wiki.bambulab.com/en/knowledge-sharing/02-mm-nozzle-FAQ
- Bambu Lab nozzle clog guide: https://wiki.bambulab.com/en/a1-mini/troubleshooting/nozzle-clog

---

## Common Failure Points and Fixes

| Problem | Likely cause | Design fix | Slicer / print fix |
|---|---|---|---|
| Sword breaks | Too thin, too isolated | Thicken blade, connect to base or shield | Print slower, improve cooling |
| Staff strings badly | Long isolated vertical detail | Attach staff to robe, base, or hand in more places | Dry filament, avoid crossing walls |
| Cape underside looks rough | Too much overhang | Make cape slope downward, connect to base | Slow down overhangs, increase cooling |
| Ankles snap | Too thin, pose too open | Thicken boots, use rocks/grass as supports | More walls, slower print |
| Face loses detail | Details too small for FDM | Use larger planes, deeper brows, stronger nose/chin shape | Use 0.2 mm profile for premium version |
| Base lifts | Small contact area or tall model | Wider base, better center of mass | Clean plate, brim ears, small brim |
| Surface damaged by supports | Model depends on support removal | Redesign supportless, split model | Avoid supports on visible surfaces |
| Visible stair stepping | Smooth curved surface too large | Add texture, facets, ridges, helmet details | Lower layer height |
| Stringing between limbs | Too many travel moves across open pose | Compact pose, reduce isolated gaps | Dry filament, calibrate retraction, avoid crossing walls |

---

## MakerWorld Listing Rules

The technical model is only half the product. MakerWorld users need to trust that the model really prints well.

A strong listing should include:

- Clear title with searchable keywords
- Real printed photos, not only renders
- Front, side, back, and close-up photos
- Photo of the most risky detail, such as sword, staff, cape, or face
- Scale information, for example 28 mm, 32 mm, or 40 mm
- Nozzle compatibility, for example 0.4 mm and optional 0.2 mm
- Layer height recommendation
- Support status clearly stated
- 3MF profile included
- Notes about brim if needed
- A short troubleshooting note for thin weapons or tall poses

Recommended title pattern:

```text
Supportless [Creature/Class/NPC Type] Pack - 28mm FDM Friendly DnD Miniatures
```

Examples:

```text
Supportless Medieval Guard Pack - 28mm FDM Friendly DnD Minis
Supportless Goblin Ambush Pack - 28mm FDM Optimized Miniatures
Supportless Knight Patrol Pack - 32mm FDM Friendly Fantasy Minis
Supportless Tavern NPC Pack - 28mm DnD Townsfolk Miniatures
```

Useful keywords:

- supportless
- support free
- FDM friendly
- FDM optimized
- DnD miniature
- TTRPG miniature
- fantasy miniature
- 28mm
- 32mm
- Bambu A1 Mini
- tabletop
- RPG
- wargaming
- no supports

---

## Quality Assurance Checklist

Before publishing a miniature on MakerWorld, check the following:

### Geometry checklist

- [ ] No large horizontal unsupported surfaces
- [ ] Thin weapons are thickened or anchored
- [ ] Staffs, spears, and bows are not isolated fragile lines
- [ ] Ankles and wrists are thick enough
- [ ] Cape or robe edges do not float too far from the body
- [ ] Base is stable and supports the center of mass
- [ ] Facial details are readable at tabletop distance
- [ ] No micro-detail is required for the model to look good
- [ ] Model works in 0.4 mm preview
- [ ] Optional 0.2 mm version adds value, not just complexity

### Slicer checklist

- [ ] Supportless profile has supports turned off
- [ ] 3MF profile uses correct nozzle size
- [ ] Seam is not placed on the most visible face if avoidable
- [ ] Brim or brim ears added if the model is tall or narrow
- [ ] Overhang preview checked
- [ ] Thin walls preview checked
- [ ] Print time is reasonable for the product type
- [ ] File was tested on the A1 Mini or similar FDM setup

### Listing checklist

- [ ] Real printed photos included
- [ ] Scale is stated
- [ ] Nozzle compatibility is stated
- [ ] Layer height recommendation is stated
- [ ] Supportless claim is accurate
- [ ] Known fragile areas are disclosed if relevant
- [ ] Keywords are included naturally in title and description
- [ ] If a pack, all minis are shown together and individually

---

## ROI Scoring Matrix

Use this before spending too much time on a model.

| Question | Points |
|---|---:|
| Is the silhouette readable in a thumbnail? | 2 |
| Can it print with a stock 0.4 mm nozzle? | 3 |
| Can it print supportless or almost supportless? | 3 |
| Are thin parts durable enough for handling? | 2 |
| Does the model fit into a reusable product family? | 2 |
| Can it be photographed well without heavy post-processing? | 1 |
| Does it solve a common DM/player need? | 2 |
| Is competition weak enough that your version can look better? | 2 |

Score interpretation:

| Score | Meaning |
|---|---|
| 14 to 17 | Strong candidate, prioritize it |
| 10 to 13 | Worth testing, but simplify or improve printability first |
| 7 to 9 | Risky, likely too fragile, too generic, or too much work |
| 0 to 6 | Avoid unless it is for practice or personal passion |

---

## Recommended First Product Experiments

### 1. Supportless Medieval Guard Pack

Why it is strong:

- Fits your knight/medieval direction
- Useful for many DnD campaigns
- Easier than dramatic heroes
- Can be made as a pack of 4 to 6
- Good test of 0.4 mm supportless rules

Model ideas:

- Sword and shield guard
- Spear guard with spear touching base
- Crossbow guard with compact pose
- Captain with thicker sword and cloak anchored to base
- Torch guard with torch close to body

---

### 2. Supportless Tavern NPC Pack

Why it is strong:

- Underserved compared with monsters and heroes
- Very useful for DMs
- Less competition than dragons and player characters
- Easier supportless geometry

Model ideas:

- Merchant
- Innkeeper
- Blacksmith
- Noble
- Prisoner
- Beggar
- Rat catcher

---

### 3. Supportless Goblin Ambush Pack

Why it is strong:

- Goblins are always useful
- Small prints are fast
- Packs feel high value
- Great for testing exaggerated silhouettes

Model ideas:

- Goblin with dagger
- Goblin archer with bow connected to body
- Goblin shield bearer
- Goblin shaman with staff touching base
- Goblin loot carrier

---

### 4. Supportless Knight Patrol Pack

Why it is strong:

- Closest to your current best sellers
- Strong fantasy/medieval search appeal
- Good brand-building category

Model ideas:

- Sword knight
- Shield knight
- Mace knight
- Banner knight with banner connected to base
- Cloaked knight captain

---

## Final Direction

For your business, the best lane is:

> **Supportless grimdark medieval fantasy miniatures and practical tabletop models optimized for FDM printers.**

This lets you combine:

- Your existing knight-selling strength
- MakerWorld demand for DnD and TTRPG miniatures
- A practical advantage over resin-style sculpts
- Better user satisfaction through reliable printing
- Stronger boosts and downloads through real printability

The most important rule is not to make the most detailed miniature. It is to make the miniature that people can actually print, paint, use, and recommend.

---

## Sources and Reference Links

- Bambu Lab A1 Mini technical specs: https://bambulab.com/en/a1-mini/tech-specs
- Bambu Lab A1 Mini FAQ: https://wiki.bambulab.com/en/a1-mini/manual/faq
- Bambu Lab 0.2 mm nozzle FAQ: https://wiki.bambulab.com/en/knowledge-sharing/02-mm-nozzle-FAQ
- Bambu Lab nozzle clog guide: https://wiki.bambulab.com/en/a1-mini/troubleshooting/nozzle-clog
- Bambu Lab line width guide: https://wiki.bambulab.com/en/software/bambu-studio/parameter/line-width
- Bambu Lab layer height guide: https://wiki.bambulab.com/en/software/bambu-studio/layer-height
- Bambu Lab overhang guide: https://wiki.bambulab.com/en/filament-acc/filament/print-quality/overhang
- Bambu Lab bridging guide: https://wiki.bambulab.com/en/filament-acc/filament/print-quality/bridging
- Bambu Studio cut tool: https://wiki.bambulab.com/en/software/bambu-studio/cut-tool
- Bambu Studio brim ears: https://wiki.bambulab.com/en/software/bambu-studio/brim-ears
- Prusa modeling with 3D printing in mind: https://help.prusa3d.com/article/modeling-with-3d-printing-in-mind_164135
- MakerWorld supportless Dark Elf Ranger example: https://makerworld.com/en/models/1496514-supportless-dark-elf-ranger-dnd-ttrpg-mini
- MakerWorld Dwarf Rifleman supportless example: https://makerworld.com/en/models/153264-dwarf-rifleman-28mm-supportless-fdm-friendly
- MakerWorld Samurai 4 Pack supportless example: https://makerworld.com/en/models/1701094-samurai-4-pack-supportless-28mm-minis
- MakerWorld Legendary Dwarf Pack example: https://makerworld.com/en/models/1584117-legendary-dwarf-pack-10-support-free-dwarves
- Printables Crusader Knight supportless example: https://www.printables.com/model/132163-crusader-knight-28mm-supportless-fdm-friendly
