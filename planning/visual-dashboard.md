# Visual Dashboard

This file is the more visual version of the agenda.

It uses Mermaid diagrams, which GitHub can render directly inside Markdown files.

## Weekly planning image

A visual weekly planner image is stored here:

```text
assets/planning/week-planning-2026-04-28.svg
```

Preview:

![Week Planning](../assets/planning/week-planning-2026-04-28.svg)

## Current week timeline

```mermaid
timeline
    title Week Plan: Cleaning, Guests, Gentle Restart
    2026-04-28 : Clean apartment part 1
               : Main living areas
               : Kitchen surfaces
               : Trash and laundry
    2026-04-29 : Clean apartment part 2
               : Bathroom
               : Floors
               : Guest-ready surfaces
    2026-04-30 : Buffer day
               : Finish leftover cleaning
               : Prepare for guests
               : Optional tiny 3D decision
    2026-05-01 : Guests arrive
               : No 3D business work
    2026-05-02 : Guest block
               : No work
               : Rest without guilt
    2026-05-03 : Guest block
               : No work
               : Capture ideas only if needed
    2026-05-04 : Guest buffer / recovery
               : Light reset only
    2026-05-05 : Gentle restart
               : Choose organizer format
               : Pick first base size target
```

## Main focus flow

```mermaid
flowchart TD
    A[End-of-semester recovery] --> B[Clean apartment first]
    B --> C[Guests for 3 to 4 days]
    C --> D[No 3D work during guest block]
    D --> E[Gentle restart]
    E --> F[Miniature organizer V1 decision]
    F --> G{Tray or compact case?}
    G --> H[Simple tray prototype]
    G --> I[Compact case prototype]
    H --> J[Small tolerance test]
    I --> J
    J --> K[First prototype]
```

## Weekly priority map

```mermaid
flowchart LR
    A[This week] --> B[Apartment]
    A --> C[Guests]
    A --> D[3D Printing]

    B --> B1[Clean main areas]
    B --> B2[Bathroom]
    B --> B3[Floors]
    B --> B4[Guest-ready reset]

    C --> C1[Protect no-work block]
    C --> C2[Rest without guilt]

    D --> D1[Only tiny planning if energy allows]
    D --> D2[No big modeling]
    D --> D3[Restart May 5]
```

## Product direction map

```mermaid
flowchart TD
    A[3D Printing Business Direction] --> B[Miniature Transport Organizer]
    A --> C[Knight Series]
    A --> D[Wild Animals]
    A --> E[Practical Gaming Accessories]
    A --> F[Paused: Dragon Stand]

    B --> B1[Highest current priority]
    B --> B2[Practical problem]
    B --> B3[Can become product family]
    B --> B4[Avoid screws and tight tolerances]

    C --> C1[Proven seller category]
    C --> C2[Use stable round bases]
    C --> C3[Low-support silhouettes]

    D --> D1[Future validation]
    D --> D2[Could broaden audience]

    E --> E1[Only pursue with unique angle]

    F --> F1[Too complex for current payoff]
    F --> F2[Keep lessons learned]
```

## Simple decision tree for the next 3D project

```mermaid
flowchart TD
    A[Do I have energy after cleaning and guests?] -->|No| B[Rest and capture ideas only]
    A -->|A little| C[Make one small decision]
    A -->|Yes| D[Sketch 2 quick layouts]

    C --> E[Choose tray vs compact case]
    D --> E
    E --> F[Choose 25 mm / 32 mm / mixed base target]
    F --> G[Design tiny tolerance test]
    G --> H[Prototype V1]
```

## Current status board

| Area | Status | Next step |
|---|---|---|
| Apartment | Active priority | Clean in two parts before guests |
| Guests | Scheduled block | No 3D work Friday to Monday |
| Miniature organizer | Best next product | Decide tray vs compact case after guest block |
| Knight series | Keep warm | Brainstorm later, not urgent this week |
| Wild animals | Later | Validate after current project direction is clearer |
| Dragon stand | Paused | Do not return unless simplified heavily |

## How to use this dashboard

Use this file when you want a quick visual overview.

Use `planning/visual-agenda.md` when you want the detailed day-by-day checklist.

Recommended workflow:

1. Check the weekly planning image.
2. Check the timeline.
3. Check the main focus flow.
4. Look at the current status board.
5. Do only the next realistic step.
