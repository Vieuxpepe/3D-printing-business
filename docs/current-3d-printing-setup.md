# Current 3D Printing Setup

_Last updated: 2026-05-05_

This document summarizes the current 3D printing setup, workflow, constraints, and practical notes for future planning, troubleshooting, model design, and marketplace strategy.

## 1. Setup Overview

The current setup is built around two Bambu Lab A1 Mini printers used mainly for FDM printing, 3D model testing, marketplace uploads, and small-format functional or tabletop prints.

The setup currently includes:

- **Printer 1:** Bambu Lab A1 Mini with AMS / AMS Lite multi-material capability.
- **Printer 2:** Standard Bambu Lab A1 Mini, older than the AMS-equipped unit.
- **Printer room:** Both printers are located in a room where hot water storage is also present, likely near a hot water tank or water heater.
- **Main use case:** Creating, testing, and publishing printable models for platforms such as MakerWorld and Cults3D.
- **Main creative focus:** Practical models, gaming accessories, tabletop miniatures, DND-style models, fantasy models, and marketplace-friendly printable designs.

The two-printer setup is useful because it allows one machine to handle more experimental or multi-color/material prints while the other can be used for simpler, repeatable, single-material print jobs.

## 2. Printer Inventory

| Printer | Type | Relative age | Current role | Notes |
|---|---|---:|---|---|
| Bambu Lab A1 Mini with AMS | FDM printer | Newer | Main advanced printer | Best suited for multi-color, multi-material, profile testing, and presentation-quality prints. |
| Bambu Lab A1 Mini | FDM printer | Older | Secondary printer | Best suited for single-color testing, repeat prints, backup jobs, and production-style batches. |

## 3. AMS / Multi-Material Setup

The newer A1 Mini has an AMS-style setup, most likely the AMS Lite system used with the Bambu A1 series.

This gives the setup several advantages:

- Easier multi-color prints.
- Better presentation models for product photos.
- Ability to test models with color-separated features.
- More flexible material handling if different filaments are loaded.
- Easier workflow for branded or decorative prints.

Important things to watch with AMS printing:

- **Purge waste:** Multi-color prints can use a lot of filament for flushing.
- **Color bleed:** Some color combinations may need higher flushing volumes.
- **Print time:** Multi-color prints are often much slower than single-color prints.
- **Model design:** Multi-color models should justify the extra print time and filament waste.
- **Marketplace strategy:** For MakerWorld, it is useful to provide both a simple single-color profile and a more premium AMS/multi-color profile when relevant.

## 4. Room and Environment

Both printers are located in a room where hot water storage is present. This matters because the printing environment can affect reliability.

### Potential advantages

- The room may stay warmer than other rooms.
- A slightly warmer room can help reduce drafts and warping for some materials.
- Keeping both printers in one room makes monitoring and maintenance easier.

### Potential risks

- Hot water tanks can create temperature fluctuations.
- The room may have higher humidity depending on ventilation and plumbing conditions.
- Moisture can affect filament quality, especially PLA, PETG, TPU, and other hygroscopic materials.
- If the room is cramped, airflow and access around the printers may be limited.
- If the printers are on unstable furniture, vibration can reduce success rate and surface quality.
- Any water-related room adds a small risk of leaks, so filament, tools, electronics, and spare parts should not be stored directly on the floor.

### Recommended room setup priorities

- Keep both printers on **stable, rigid furniture**.
- Avoid wobbly tables, flexible shelving, or furniture that shakes during fast movements.
- Store filament away from the floor and away from plumbing.
- Use dry boxes, sealed bins, silica gel, or AMS desiccant whenever possible.
- Leave space behind and around the printers for airflow and maintenance.
- Avoid placing printers directly beside the hot water tank.
- Keep power cables organized and away from any possible water source.

## 5. Stability and Furniture

One known observation from the setup is that the printer placed on more stable furniture has a better success rate than the one on wobbly furniture.

That makes sense. The A1 Mini moves quickly, and wobble can affect:

- First-layer consistency.
- Ringing or ghosting on walls.
- Tall, thin prints.
- Miniatures with small contact points.
- Print failures caused by vibration over time.

Current priority:

> Both printers should eventually be placed on rigid, heavy, vibration-resistant surfaces.

Good options include:

- A sturdy workbench.
- A heavy shelving unit with reinforcement.
- A solid table with minimal side-to-side movement.
- A paver stone or heavy slab under the printer, with a thin vibration-damping mat underneath the slab if needed.

## 6. Current Print Style and Typical Settings

The setup is often used for detailed FDM models and small tabletop-style prints.

Known or commonly used settings include:

- **Layer height:** As low as 0.08 mm for detailed models.
- **Walls:** Around 3 walls for strength and surface quality.
- **Infill:** Around 20% for many models.
- **Printer type:** Bambu Lab A1 Mini FDM.
- **Typical model scale:** Small to medium objects, miniatures, tabletop pieces, and practical accessories.

These settings are especially useful for:

- Fantasy miniatures.
- DND-style figures.
- Small statues.
- Display pieces.
- Detailed marketplace models.
- Functional accessories where clean surface finish matters.

## 7. Main Modeling and Marketplace Direction

The current 3D printing work is connected to publishing models online and testing what performs well.

Main platforms:

- MakerWorld.
- Cults3D.

Main model directions explored:

- Dark fantasy miniatures.
- Knights and medieval characters.
- DND-style tabletop models.
- Wild animals.
- Orcs, goblins, elves, dwarves, and other fantasy creatures.
- Practical accessories.
- Gaming accessories.
- Nintendo Switch / controller / stand-style products.
- Miniature transport or storage organizers.

Current strongest category:

> Knight and dark fantasy models appear to be among the best-performing model categories so far.

## 8. Design Philosophy

The current design direction favors models that are:

- Visually appealing.
- Printable on an A1 Mini.
- Not too hard for users to slice and print.
- Support-conscious.
- Marketplace-friendly.
- Simpler than overcomplicated mechanical designs.
- Strong enough to survive normal handling.
- Easy to photograph and present online.

Important lesson from previous designs:

> A model can look impressive but still perform poorly if users see it as too complex, too fragile, too hard to print, or too annoying to assemble.

Better marketplace models should aim for:

- Clear purpose.
- Clean silhouette.
- Easy printability.
- Strong thumbnails.
- Low frustration for users.
- Simple assembly, or no assembly if possible.
- Good default print profiles.

## 9. Miniature Design Rules

For FDM-friendly miniatures, especially on the A1 Mini, the design should avoid thin unsupported details whenever possible.

Useful design rules:

- Add a round base when it improves stability and printability.
- Let swords, capes, staffs, and weapons touch the base when possible.
- Avoid floating weapons or thin parts held by tiny wrists.
- Keep capes connected to the body or base.
- Avoid isolated spikes, hair strands, horns, or fingers that require delicate supports.
- Use thicker silhouettes for weapons and limbs.
- Prefer heroic, readable poses over fragile dynamic poses.
- Make contact points intentional.
- Keep support removal in mind from the start.

For marketplace users, a model that prints reliably is usually better than a model that only looks amazing in renders.

## 10. Practical Product Design Rules

For functional products and accessories, the setup should prioritize models that solve a real problem without becoming too complicated.

Good directions:

- Organizers.
- Holders.
- Simple modular storage.
- Gaming desk accessories.
- Miniature transport cases.
- Tools for tabletop players.
- Accessories that are easier to print than to buy.

Avoid over-investing in products that require:

- Too many screws.
- Very precise tolerances.
- Complicated assembly.
- Excessive print time.
- Too many support structures.
- A use case that is not immediately clear from the thumbnail.

## 11. Known Issues and Troubleshooting Themes

The current setup has already encountered or investigated these themes:

- Brim appearing even when it seemed disabled.
- Supports being generated in strange or unnecessary places.
- Supports that appear to support nothing.
- Print reliability differences between stable and unstable furniture.
- Interest in spaghetti detection or remote print monitoring.
- Camera compatibility questions for monitoring.
- Raspberry Pi / OctoEverywhere-style monitoring possibilities.
- Multi-color purge and bleed considerations.

These are good topics to document further as separate troubleshooting notes later.

## 12. Spaghetti Detection and Monitoring Direction

There has been interest in adding AI or camera-based failure detection to the A1 Mini setup.

Possible monitoring direction:

- Use a camera for visual monitoring.
- Explore OctoEverywhere or similar spaghetti detection options.
- Consider Raspberry Pi-based monitoring if hardware compatibility is solved.
- Confirm camera compatibility before buying extra hardware.
- Decide whether monitoring is mainly for convenience or for protecting long prints.

Because the setup has two printers, monitoring becomes more valuable. Two printers increase the chance that one print may fail while attention is on the other machine.

## 13. Maintenance Priorities

Since one printer may sometimes sit unused for a while, a simple maintenance routine is useful.

### Before restarting after a long break

- Clean the build plate.
- Check that the nozzle is clean.
- Check filament condition.
- Check for dust around rails and moving parts.
- Run a small calibration or test print.
- Confirm the printer is on a stable surface.
- Confirm the room has no unusual humidity or water issue.

### Weekly or regular use

- Wipe the build plate when needed.
- Remove loose filament bits and purge waste.
- Check that the AMS paths are feeding smoothly.
- Check that spools rotate freely.
- Watch for repeated first-layer problems.
- Check if one printer is becoming less reliable than the other.

### Monthly or occasional

- Inspect belts and motion system visually.
- Clean dust from the printer area.
- Review failed prints and look for patterns.
- Check filament storage humidity.
- Reorganize profiles that are working well.
- Archive successful print profiles for models that will be uploaded.

## 14. Suggested Workflow With Two Printers

A strong two-printer workflow could be:

| Task | Best printer |
|---|---|
| Multi-color display prints | Newer A1 Mini with AMS |
| Marketplace hero photos | Newer A1 Mini with AMS |
| Single-color test prints | Older standard A1 Mini |
| Tolerance tests | Older standard A1 Mini |
| Batch printing simple models | Either printer |
| Risky prototype prints | Older standard A1 Mini |
| Final profile validation | Both printers, if possible |

This workflow helps avoid blocking the better printer with rough prototypes while still using the AMS printer for premium final outputs.

## 15. Current Strategic Direction

The current direction should probably focus on models that are:

- Useful or visually strong immediately.
- Not too niche.
- Easy to understand from a thumbnail.
- Printable on the A1 Mini build volume.
- Reliable with minimal support.
- Strong enough for beginner and intermediate users.
- Good candidates for MakerWorld print profiles.

Best current bets:

1. **Fantasy knights and tabletop models** because they already perform well.
2. **Miniature storage and transport solutions** because they solve a real problem.
3. **Simple gaming accessories** if the function is obvious and the design is sleek.
4. **Support-friendly fantasy creatures** with strong silhouettes.
5. **AMS-enhanced decorative versions** of models that also work in single color.

## 16. Open Questions To Clarify Later

These details are not fully locked in yet and should be documented later:

- Exact AMS model and configuration.
- Exact room humidity level.
- Whether filament is stored in sealed containers or open air.
- Which printer is currently on the more stable furniture.
- Whether both printers use the same nozzle size.
- Whether both printers are running the same slicer/profile settings.
- Whether a camera monitoring solution has been purchased.
- Whether the older A1 Mini needs maintenance after sitting unused.

## 17. Immediate Improvement Checklist

Highest-impact improvements for the current setup:

- Move both printers onto stable furniture.
- Keep filament dry, especially in the hot water storage room.
- Add a simple room thermometer/hygrometer.
- Keep electronics and filament off the floor.
- Separate prototype printing from final marketplace-profile printing.
- Create repeatable Bambu Studio profiles for common model types.
- Maintain a small test-print library for miniatures, supports, tolerances, and AMS color bleed.
- Document every model that performs well, including print time, filament used, support settings, and user complaints.

## 18. Summary

The current setup is a compact but capable two-printer Bambu Lab A1 Mini workspace. The newer A1 Mini with AMS is the premium machine for multi-color work, final presentation prints, and advanced profile testing. The older standard A1 Mini is still valuable as a secondary workhorse for prototypes, single-color testing, and repeatable production jobs.

The biggest practical factor to improve right now is probably not the printers themselves, but the environment around them: stable furniture, humidity control, safe storage near the hot water room, and clear separation between prototyping and final print validation.

The strongest business direction remains printable, support-conscious models that are easy to understand, easy to print, and attractive on marketplace thumbnails, especially dark fantasy knights, tabletop models, and practical gaming or miniature accessories.
