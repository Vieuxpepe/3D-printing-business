# 3D Printing Business Hub

A simple Markdown-based planning hub for the **Vieux Pepe / Vieux Pépé** 3D printing business.

This repository is designed to organize product ideas, active model projects, product catalog entries, market observations, customer feedback, release preparation, and weekly planning without becoming a complicated software project.

## What this repo is for

Use this repository to track and improve:

- 3D printable product ideas
- active design projects
- product catalog entries
- market research and product analysis
- MakerWorld descriptions and tags
- weekly and daily agenda planning
- visual task planning
- customer feedback and complaints
- MakerWorld and Cults3D listings
- release checklists
- product templates
- lessons learned from previous models

## What this repo is not

This is not currently an app, codebase, or automation system.

Unless intentionally changed later, keep it as a clean Markdown planning system.

## Current business focus

The current direction is to prioritize practical, printable models that are useful, visually appealing, and not overly complicated to produce.

Main product directions:

1. **Miniature transport and storage organizers**
2. **Knight and fantasy miniature series**
3. **Wild animal models**
4. **Practical gaming accessories**
5. **Improved versions of previous models based on customer feedback**

## Recommended workflow

### 1. Capture ideas quickly

Add rough ideas to:

```text
ideas/product-ideas.md
```

Do not worry about making them perfect right away.

### 2. Record market observations

When the user notices something about what sells, what gets downloads, what customers complain about, or what competitors are doing, store it under:

```text
market-research/
```

Use:

```text
market-research/market-observations.md
market-research/product-analysis-log.md
market-research/opportunity-map.md
market-research/competitor-observations.md
```

### 3. Promote promising ideas

When an idea becomes serious, track it in:

```text
products/active-projects.md
```

Then create a product catalog entry under:

```text
product-catalog/
```

Use:

```text
templates/product-catalog-entry-template.md
```

### 4. Keep one product record per product

Every serious product should eventually have its own Markdown file in:

```text
product-catalog/
```

Each product record should include:

- product concept
- status
- target users
- problem solved
- design notes
- print settings
- included files
- MakerWorld title
- MakerWorld description
- MakerWorld print profile notes
- exactly 50 MakerWorld tags when possible
- Cults3D listing notes if useful
- customer feedback
- version history
- next actions

### 5. Plan the week visually

Use:

```text
planning/visual-dashboard.md
planning/visual-agenda.md
```

The dashboard gives the visual overview. The agenda gives the day-by-day checklist.

### 6. Track feedback

When customers complain, ask questions, or request features, add it to:

```text
feedback/customer-feedback.md
```

Also add product-specific feedback inside the matching file in:

```text
product-catalog/
```

### 7. Prepare releases

Before publishing a model, use:

```text
planning/launch-pipeline.md
templates/release-checklist.md
```

Then finalize the MakerWorld or Cults3D listing inside the product catalog entry.

## Repository structure

```text
AI_CONTEXT.md
DASHBOARD.md
NOTIFICATION_CONTACT.md
README.md

ideas/
  product-ideas.md
  future-opportunities.md
  rejected-or-paused-ideas.md

market-research/
  README.md
  market-observations.md
  product-analysis-log.md
  competitor-observations.md
  opportunity-map.md

planning/
  weekly-agenda.md
  daily-notes.md
  priorities.md
  visual-agenda.md
  visual-dashboard.md
  launch-pipeline.md

product-catalog/
  README.md
  miniature-transport-organizer.md

products/
  active-projects.md
  miniature-transport-organizer.md
  knight-series.md

feedback/
  customer-feedback.md

templates/
  product-template.md
  product-catalog-entry-template.md
  product-scorecard.md
  release-checklist.md
  visual-agenda-template.md
  cults3d-description-template.md
  makerworld-description-template.md
```

## File guide

| File | Purpose |
|---|---|
| `DASHBOARD.md` | Main command center |
| `AI_CONTEXT.md` | Master guide for future AI assistants accessing this repo |
| `NOTIFICATION_CONTACT.md` | Private notification instructions |
| `market-research/README.md` | Market research rules and file map |
| `market-research/market-observations.md` | Running observations about trends, demand, and marketplace behavior |
| `market-research/product-analysis-log.md` | Structured analysis of specific product ideas |
| `market-research/opportunity-map.md` | Product category opportunities and gaps |
| `market-research/competitor-observations.md` | Competitor patterns and notes, without copying designs |
| `product-catalog/README.md` | Product catalog rules and index |
| `product-catalog/miniature-transport-organizer.md` | First complete product record |
| `templates/product-catalog-entry-template.md` | Template for every future product record |
| `ideas/product-ideas.md` | Main idea bank |
| `ideas/future-opportunities.md` | Longer-term opportunities and expansion ideas |
| `ideas/rejected-or-paused-ideas.md` | Paused ideas and lessons learned |
| `planning/visual-dashboard.md` | Mermaid visual overview |
| `planning/visual-agenda.md` | Day-by-day agenda and checklist |
| `planning/launch-pipeline.md` | Product launch process |
| `planning/weekly-agenda.md` | Weekly plan and review |
| `planning/daily-notes.md` | Messy daily capture notes |
| `planning/priorities.md` | Current priority ranking |
| `products/active-projects.md` | Serious current projects |
| `products/miniature-transport-organizer.md` | Working notes for the miniature organizer idea |
| `products/knight-series.md` | Working notes for the knight product line |
| `feedback/customer-feedback.md` | Customer complaints, requests, and lessons |
| `templates/product-template.md` | General product planning template |
| `templates/product-scorecard.md` | Product idea scoring template |
| `templates/release-checklist.md` | Checklist before publishing |
| `templates/visual-agenda-template.md` | Reusable agenda template |
| `templates/cults3d-description-template.md` | Cults3D listing template |
| `templates/makerworld-description-template.md` | MakerWorld listing template |

## Product catalog rule

The `product-catalog/` folder is the long-term product memory.

Use it for polished product records and marketplace-ready information.

The older `products/` folder can still be used for rougher working notes, active project planning, and product family notes.

## Market research rule

The `market-research/` folder is the long-term market memory.

Use it to store observations, competitor patterns, product analysis, and opportunity maps.

Separate evidence from assumptions.

## Guiding principles

Prefer models that:

- solve a real problem
- are easy to understand from a thumbnail
- are reliable to print
- avoid fragile mechanisms
- avoid unnecessary tight tolerances
- can become a product family
- look clean and professional
- are realistic to finish without burning out
- have at least some market signal or useful observation supporting them

Avoid or pause models that:

- take too long without clear upside
- rely on fragile screws or tight threads
- are too generic
- are hard to explain visually
- create likely customer complaints
- are complicated mainly for the sake of being complicated

## Current best next direction

The strongest current practical direction is the **miniature transport and storage organizer**.

Main record:

```text
product-catalog/miniature-transport-organizer.md
```

Why:

- It solves a clear problem.
- It can be made sleek and practical.
- It can become a product family.
- It builds on lessons from previous tolerance and screw complaints.
- It is a manageable project after an exhausting school period.

Recommended first move:

Create a simple version 1 prototype, likely a tray or compact case for common miniature base sizes, before attempting a larger modular system.
