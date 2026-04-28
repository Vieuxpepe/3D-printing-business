# 3D Printing Business Hub

A simple Markdown-based planning hub for the **Vieux Pepe / Vieux Pépé** 3D printing business.

This repository is designed to organize product ideas, active model projects, customer feedback, release preparation, and weekly planning without becoming a complicated software project.

## What this repo is for

Use this repository to track and improve:

- 3D printable product ideas
- active design projects
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

### 2. Promote promising ideas

When an idea becomes serious, move it into:

```text
products/active-projects.md
```

Or create a dedicated product page under:

```text
products/
```

### 3. Plan the week visually

Use:

```text
planning/visual-agenda.md
```

This file acts like a simple Markdown Kanban board with Now / Next / Later sections.

### 4. Track feedback

When customers complain, ask questions, or request features, add it to:

```text
feedback/customer-feedback.md
```

### 5. Prepare releases

Before publishing a model, use:

```text
templates/release-checklist.md
```

Then use the marketplace template that fits the release:

```text
templates/makerworld-description-template.md
templates/cults3d-description-template.md
```

## Repository structure

```text
AI_CONTEXT.md
README.md

ideas/
  product-ideas.md
  future-opportunities.md
  rejected-or-paused-ideas.md

planning/
  weekly-agenda.md
  daily-notes.md
  priorities.md
  visual-agenda.md

products/
  active-projects.md
  miniature-transport-organizer.md
  knight-series.md

feedback/
  customer-feedback.md

templates/
  product-template.md
  release-checklist.md
  visual-agenda-template.md
  cults3d-description-template.md
  makerworld-description-template.md
```

## File guide

| File | Purpose |
|---|---|
| `AI_CONTEXT.md` | Master guide for future AI assistants accessing this repo |
| `ideas/product-ideas.md` | Main idea bank |
| `ideas/future-opportunities.md` | Longer-term opportunities and expansion ideas |
| `ideas/rejected-or-paused-ideas.md` | Paused ideas and lessons learned |
| `planning/weekly-agenda.md` | Weekly plan and review |
| `planning/daily-notes.md` | Messy daily capture notes |
| `planning/priorities.md` | Current priority ranking |
| `planning/visual-agenda.md` | Visual Markdown agenda / Kanban board |
| `products/active-projects.md` | Serious current projects |
| `products/miniature-transport-organizer.md` | Dedicated page for the miniature organizer idea |
| `products/knight-series.md` | Dedicated page for the knight product line |
| `feedback/customer-feedback.md` | Customer complaints, requests, and lessons |
| `templates/product-template.md` | Template for new product pages |
| `templates/release-checklist.md` | Checklist before publishing |
| `templates/visual-agenda-template.md` | Reusable agenda template |
| `templates/cults3d-description-template.md` | Cults3D listing template |
| `templates/makerworld-description-template.md` | MakerWorld listing template |

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

Avoid or pause models that:

- take too long without clear upside
- rely on fragile screws or tight threads
- are too generic
- are hard to explain visually
- create likely customer complaints
- are complicated mainly for the sake of being complicated

## Current best next direction

The strongest current practical direction is the **miniature transport and storage organizer**.

Why:

- It solves a clear problem.
- It can be made sleek and practical.
- It can become a product family.
- It builds on lessons from previous tolerance and screw complaints.
- It is a manageable project after an exhausting school period.

Recommended first move:

Create a simple version 1 prototype, likely a tray or compact case for common miniature base sizes, before attempting a larger modular system.
