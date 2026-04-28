# Project Context

This file gives a fast overview of the entire 3D printing business planning project.

Use this file when opening the repository for the first time.

## Project identity

**Project name:** 3D Printing Business Hub  
**Brand:** Vieux Pepe / Vieux Pépé  
**Repository purpose:** private planning system for product ideas, market observations, product catalog entries, agendas, feedback, and launch preparation.

This is not a code project. It is a business planning and product development repository written in Markdown.

## Main goal

Help the user build a stronger 3D printing model business by organizing ideas, choosing better products, tracking feedback, preparing listings, and avoiding overcomplicated projects that take too much time for unclear payoff.

## Current business direction

The current strategy is to focus on products that are:

- practical or visually appealing
- easy to understand from thumbnails
- reliable to print
- not overly dependent on tight tolerances
- realistic to finish without burnout
- strong enough to become product families
- useful for MakerWorld, Cults3D, or both

## Current priority order

1. Miniature transport and storage organizer
2. Knight and fantasy miniature series
3. Wild animal models
4. Practical gaming accessories
5. Improved versions of previous models based on feedback

## Current strongest product direction

The miniature transport and storage organizer is currently the strongest practical product direction.

Why:

- solves a clear problem for tabletop players and miniature painters
- can be simple and useful
- can become a product family
- avoids overcomplicated sculpting or mechanisms
- connects to lessons from previous customer complaints about screw mechanisms

Main product record:

```text
product-catalog/miniature-transport-organizer.md
```

## Important lessons learned

### Complexity does not guarantee value

A previous complex articulated modular dragon stand took a lot of time and felt too complicated compared to its practical value.

Lesson:

- score complex ideas before committing serious time
- make the function obvious from the thumbnail
- avoid building full modular systems before testing a small version

### Tolerances matter for public models

A previous model sold somewhat well, but customers complained that the screw mechanism did not work even though it worked on the user's printer.

Lesson:

- design for imperfect printers, not only the user's own printer
- avoid screws in early public releases unless tested carefully
- include tolerance tests if needed
- keep functional designs forgiving

### Proven categories matter

Knight and fantasy models are among the user's best sellers.

Lesson:

- continue the knight/fantasy direction, but keep models printable
- use stable bases
- avoid thin floating parts
- make silhouettes strong and thumbnail-friendly

## Repo structure summary

```text
DASHBOARD.md
PROJECT_CONTEXT.md
AI_CONTEXT.md
NOTIFICATION_CONTACT.md
README.md

ideas/
market-research/
planning/
product-catalog/
products/
feedback/
templates/
```

## What each area is for

### `DASHBOARD.md`

Main command center. Open this first for the current focus, best next action, and key links.

### `PROJECT_CONTEXT.md`

Short project overview for fast onboarding.

### `AI_CONTEXT.md`

Detailed operating instructions for future AI assistants.

### `NOTIFICATION_CONTACT.md`

Private notification instructions. Use only when the user explicitly asks for reminders or emails.

### `ideas/`

Raw ideas, future opportunities, and paused/rejected ideas.

### `market-research/`

Market observations, product analysis, competitor observations, and opportunity mapping.

### `planning/`

Visual dashboard, day-by-day agenda, launch pipeline, priorities, and weekly planning.

### `product-catalog/`

The official long-term product memory. Every serious product should get one Markdown file here.

### `products/`

Active working notes and product family notes.

### `feedback/`

Customer complaints, requests, and lessons learned.

### `templates/`

Reusable templates for product entries, scorecards, launches, descriptions, and agendas.

## Core workflow

1. Capture rough ideas in `ideas/product-ideas.md`.
2. Store market observations in `market-research/`.
3. Score promising ideas with `templates/product-scorecard.md`.
4. Track active projects in `products/active-projects.md`.
5. Create one product record per serious product in `product-catalog/`.
6. Prepare release steps using `planning/launch-pipeline.md`.
7. Store customer feedback in `feedback/customer-feedback.md` and in the matching product catalog file.
8. Use `DASHBOARD.md` to decide what matters right now.

## Product catalog rule

Every serious product should have a dedicated file in:

```text
product-catalog/
```

Each file should include:

- short description
- full concept
- target users
- problem solved
- design notes
- print settings
- MakerWorld listing
- 50 MakerWorld tags
- Cults3D notes if useful
- feedback
- version history
- next actions

Template:

```text
templates/product-catalog-entry-template.md
```

## Market research rule

Market insights should be stored in:

```text
market-research/
```

Separate actual observations from assumptions.

Useful files:

- `market-research/market-observations.md`
- `market-research/product-analysis-log.md`
- `market-research/opportunity-map.md`
- `market-research/competitor-observations.md`

## Planning rule

For current planning, use:

```text
DASHBOARD.md
planning/visual-dashboard.md
planning/visual-agenda.md
```

The visual dashboard gives the big picture. The visual agenda gives day-by-day tasks.

## Current schedule context

As of 2026-04-28:

- The user needs to clean the apartment in the next 2 days.
- Guests are coming Friday for 3 to 4 days.
- No 3D printing work should be expected during the guest block.
- The recommended restart date for 3D planning is around 2026-05-05.

## Best next action

The best next 3D printing business action is:

> Decide whether the miniature transport organizer version 1 should be a simple tray or a compact case.

Do not push a big modeling session until cleaning and the guest block are done.

## Tone guidance

Be practical, clear, and encouraging.

The user likes useful structure, direct recommendations, and a bit of enthusiasm. Avoid making things feel too corporate or heavy.

Focus on helping the user build momentum without overloading them.