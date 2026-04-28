# Context Recovery Guide

This file exists because chat context can be lost over time.

Use this guide when a new AI assistant, future chat, or automation needs to quickly rebuild what is known about the project without relying on the current conversation history.

## Purpose

The goal of this file is to make the repository self-explaining.

If an AI loses context, it should be able to recover by reading a small set of files in the correct order.

## Fast recovery order

Read these files first, in this order:

1. `PROJECT_CONTEXT.md`
2. `DASHBOARD.md`
3. `AI_CONTEXT.md`
4. `planning/visual-dashboard.md`
5. `planning/visual-agenda.md`
6. `product-catalog/README.md`
7. `product-catalog/miniature-transport-organizer.md`
8. `market-research/market-observations.md`
9. `market-research/opportunity-map.md`
10. `NOTIFICATION_CONTACT.md`, only if the user asks for reminders or notifications

## What each file restores

| File | Restores |
|---|---|
| `PROJECT_CONTEXT.md` | Big-picture project identity, current strategy, core workflow |
| `DASHBOARD.md` | Current focus, best next action, key links |
| `AI_CONTEXT.md` | Detailed rules for future AI assistants |
| `planning/visual-dashboard.md` | Mermaid visual overview of current agenda and product direction |
| `planning/visual-agenda.md` | Day-by-day agenda and current schedule constraints |
| `product-catalog/README.md` | Product catalog rules |
| `product-catalog/miniature-transport-organizer.md` | Current strongest product record and marketplace draft |
| `market-research/market-observations.md` | Key market lessons and observations |
| `market-research/opportunity-map.md` | Current product opportunities and priority levels |
| `NOTIFICATION_CONTACT.md` | Private notification method, only when needed |

## Current project summary

This is a private Markdown-based planning repository for the Vieux Pepe / Vieux Pépé 3D printing business.

The repository is not a code project. It is a business planning, product development, market research, and agenda system.

The current strongest product direction is:

> A miniature transport and storage organizer for tabletop miniatures.

The current strategic rule is:

> Prefer practical, printable, easy-to-explain products over overly complex designs.

## Current priorities

1. Miniature transport and storage organizer
2. Knight and fantasy miniature series
3. Wild animal models
4. Practical gaming accessories
5. Improved versions of previous products based on feedback

## Current schedule context

As of 2026-04-28:

- The user needs to clean the apartment in the next 2 days.
- Guests are coming Friday for 3 to 4 days.
- No 3D printing business work should be expected during the guest block.
- A gentle 3D planning restart is recommended around 2026-05-05.

If this schedule is outdated, ask the user for an update before planning the week.

## Important user context

The user creates 3D printable models for marketplaces like MakerWorld and Cults3D.

Known context:

- Knight and fantasy models are among the user's best sellers.
- The user is considering wild animals as a possible product direction.
- The user spent around two weeks on a complex articulated modular dragon stand concept and felt it was too complicated and not worth the effort compared with the payoff.
- A previous model sold somewhat well, but customers complained about a screw mechanism not working on their printers.
- The user recently finished an exhausting mechanical engineering semester and should not be pushed into huge projects immediately.
- The user wants help organizing ideas, writing agendas, creating product files, preparing MakerWorld/Cults3D descriptions, and tracking market observations.

## Important business lessons

### Complexity must be justified

Do not recommend a complex model only because it sounds impressive.

Complex models should be scored and validated before serious time investment.

### Print reliability matters

Designs should work for public users, not only on the user's own printer.

Avoid tight screw threads and sensitive tolerances unless carefully tested.

### Thumbnail clarity matters

If the product cannot be understood quickly from the thumbnail, it may not perform well.

### Product families are valuable

A strong product should ideally be expandable into versions, sizes, variants, or collections.

## Where to store new information

| New information type | Store it here |
|---|---|
| Raw product idea | `ideas/product-ideas.md` |
| Serious product record | `product-catalog/` |
| Product working notes | `products/` |
| Market observation | `market-research/market-observations.md` |
| Product analysis | `market-research/product-analysis-log.md` |
| Competitor observation | `market-research/competitor-observations.md` |
| Opportunity or product gap | `market-research/opportunity-map.md` |
| Customer complaint | `feedback/customer-feedback.md` and matching product catalog file |
| Weekly or daily plan | `planning/visual-agenda.md` |
| Visual overview | `planning/visual-dashboard.md` |
| Notification instructions | `NOTIFICATION_CONTACT.md` |

## How to recover the best next action

To determine what the user should do next:

1. Read `DASHBOARD.md`.
2. Read `planning/visual-agenda.md`.
3. Read `product-catalog/miniature-transport-organizer.md`.
4. Check `market-research/opportunity-map.md`.
5. Recommend only one primary next action and one optional secondary action.

Current best next action:

> After cleaning and the guest block, decide whether the miniature organizer version 1 should be a simple tray or a compact case.

## How to handle reminders

The user does not want ChatGPT push notification spam because ChatGPT is shared with his girlfriend.

GitHub push notifications were unreliable.

A direct Gmail test worked.

For reminder/email details, read:

```text
NOTIFICATION_CONTACT.md
```

Only use that file when the user explicitly asks for a notification, reminder, or email.

## Tone recovery

When helping the user:

- Be practical and encouraging.
- Keep structure clean.
- Avoid overwhelming lists unless organizing a repo file.
- Prefer clear recommendations.
- Be a bit enthusiastic.
- Do not use em dashes.
- Do not sound overly corporate.

## Golden rule

This repository is the memory.

If chat context is lost, update the repository so the next AI can continue from the files instead of guessing from conversation history.
