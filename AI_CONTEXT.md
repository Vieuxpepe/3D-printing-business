# AI Context for This Repository

This is the master context file for any future AI assistant, coding agent, planning agent, or automation tool that accesses this repository.

Read this file first before editing anything.

## Core identity of the repository

This repository is a **Markdown-based planning hub** for a 3D printing business under the **Vieux Pepe / Vieux Pépé** brand.

It is **not** currently a software project.

Do not add app code, dependencies, package files, build systems, or complex automation unless the user explicitly asks for that later.

The purpose of this repo is to reduce mental clutter and help the user make better product decisions, especially around 3D printable models for MakerWorld, Cults3D, and similar marketplaces.

## What this repo should help with

Use this repository to organize:

- raw 3D printable product ideas
- active model projects
- weekly and daily planning
- visual agenda planning
- MakerWorld and Cults3D release preparation
- customer feedback and complaints
- product description templates
- future opportunities and product families
- lessons learned from models that were too complicated, fragile, or unclear

## User context

The user creates 3D printable models and publishes/sells them online.

Important current context:

- Knight and fantasy models are among the user's best sellers.
- The user is considering wild animal models as a future category.
- The user recently spent about two weeks on a complex articulated modular dragon stand concept, but felt it was too complicated and did not work as clearly as expected.
- The user is interested in a simpler, sleeker, more practical miniature transport/storage organizer.
- A previous model sold somewhat better, but some customers complained that a screw mechanism did not work, even though it worked on the user's printer.
- The user recently finished an exhausting end-of-semester rush for mechanical engineering final exams, so planning should respect energy and recovery.
- The user wants help organizing ideas, writing agendas, choosing what to work on, and turning messy thoughts into clear product plans.

## Tone and collaboration style

When helping the user through this repository:

- Be practical, encouraging, clear, and direct.
- Be a little enthusiastic, but not fake or corporate.
- Avoid overwhelming the user with too many directions at once.
- Prefer one strong next action over a huge list.
- Respect that the user may be tired after school workload.
- Help rebuild momentum with manageable projects.
- Use Markdown checklists and clean sections.
- Avoid em dashes and unnatural wording.

## Current strategic direction

The repo currently prioritizes practical, printable models that are:

- useful or strongly appealing
- easy to understand from a thumbnail
- reliable to print
- not overly complicated to design
- not dependent on extremely tight tolerances
- able to become product families
- compatible with MakerWorld/Cults3D listing strategy

Current priority order:

1. **Miniature transport and storage organizer**
2. **Knight and fantasy miniature series**
3. **Wild animal models**
4. **Practical gaming accessories**
5. **Improved versions of previous models based on customer feedback**

## Current best next project

The **miniature transport/storage organizer** is currently the strongest practical product direction.

Reasons:

- It solves a clear real-world problem.
- It can be made simpler and sleeker than the previous complicated dragon stand concept.
- It can become a product family.
- It can use lessons learned from screw/tolerance complaints.
- It is practical enough to build momentum without needing an overly ambitious sculpt.

Recommended first step:

Create a very simple version 1 prototype, likely a tray or compact case for common miniature base sizes, before attempting a full modular system.

## Main file map

### Top-level files

#### `README.md`

Public-facing overview of the repository.

Use it to explain:

- what the repo is for
- the main folder structure
- the business planning workflow
- guiding principles

Update this only when the overall structure or workflow changes.

#### `AI_CONTEXT.md`

This master file.

Use it to brief future AI agents quickly.

Update this when:

- the user's main direction changes
- new rules or workflows are created
- new major files are added
- current priorities change significantly

### Ideas folder

#### `ideas/product-ideas.md`

The main idea bank.

Use it for:

- raw ideas
- priority grouping
- possible product families
- early-stage product concepts
- idea scoring

When the user mentions a new idea, this is usually the first file to update.

#### `ideas/future-opportunities.md`

Longer-term opportunities and expansion paths.

Use it for:

- marketplace strategy
- branding ideas
- future product categories
- experiments to revisit later
- collection strategy

#### `ideas/rejected-or-paused-ideas.md`

Ideas that are not currently worth pursuing.

Use it for:

- ideas that were too complicated
- ideas that were too fragile
- ideas that had unclear value
- ideas that were too generic
- lessons learned from paused projects

Do not delete paused ideas unless the user explicitly asks. They are useful for decision-making.

### Planning folder

#### `planning/weekly-agenda.md`

Weekly planning file.

Use it to define:

- weekly focus
- 1 to 3 priorities
- small action steps
- optional tasks
- end-of-week review

Keep it realistic.

#### `planning/daily-notes.md`

Quick capture file.

Use it for:

- messy notes
- rough thoughts
- quick reminders
- things to organize later

#### `planning/priorities.md`

Current ranking of what matters most.

Use it when the user asks:

- what should I work on next?
- which idea is strongest?
- should I pause this?
- how should I prioritize my 3D modeling time?

#### `planning/visual-agenda.md`

A more visual, board-style agenda that can be edited in Markdown.

Use it for:

- Now / Next / Later planning
- weekly focus blocks
- small task cards
- energy-aware workload planning
- quick status overview

This is the recommended agenda format for the user because it is easy for an AI to modify and easy for the user to read on GitHub.

### Products folder

#### `products/active-projects.md`

Tracks projects that are actively being considered or worked on.

Status labels:

- Idea
- Planning
- Prototype
- Testing
- Listing prep
- Released
- Paused

Use this when an idea becomes more serious than a brainstorm.

#### `products/miniature-transport-organizer.md`

Dedicated page for the miniature organizer concept.

Focus on:

- target users
- real pain points
- base sizes
- version 1 scope
- printability
- tolerances
- avoiding unreliable mechanisms
- future product family potential

#### `products/knight-series.md`

Dedicated page for knight and fantasy miniature products.

Important design rules:

- include stable bases
- use the base to support swords, capes, banners, or weapons when possible
- avoid floating thin details
- prioritize readable silhouettes
- think about support-free or low-support printing from the start

### Feedback folder

#### `feedback/customer-feedback.md`

Tracks comments, complaints, requests, and lessons from customers.

Important existing feedback:

- Screw mechanism complaints on a previous model.
- Lesson: design for imperfect printers, not only the user's own printer.

Use this whenever the user mentions customer comments, reviews, problems, or recurring marketplace issues.

### Templates folder

#### `templates/product-template.md`

Reusable product planning template.

Use it when creating a new product page under `products/`.

#### `templates/release-checklist.md`

Checklist before publishing a model.

Use it before MakerWorld/Cults3D releases.

#### `templates/cults3d-description-template.md`

Template for paid or premium Cults3D listings.

#### `templates/makerworld-description-template.md`

Template for MakerWorld listings, print profiles, and download-focused releases.

#### `templates/visual-agenda-template.md`

Reusable board-style planning template.

Use it to create or refresh `planning/visual-agenda.md`.

## How future AI should update the repo

### When the user gives a new product idea

1. Add the idea to `ideas/product-ideas.md`.
2. Give it a rough priority: High, Medium, Low, or Paused.
3. If it is promising, create or update a product page under `products/`.
4. If it affects current direction, update `planning/priorities.md`.
5. If it becomes immediate work, update `products/active-projects.md` and `planning/visual-agenda.md`.

### When the user mentions customer feedback

1. Add it to `feedback/customer-feedback.md`.
2. Identify the affected product.
3. Summarize the problem clearly.
4. Add possible causes.
5. Add possible fixes.
6. If urgent, update the related product page and release checklist.

### When the user asks what to work on next

1. Read `planning/priorities.md`.
2. Check `products/active-projects.md`.
3. Check `planning/visual-agenda.md`.
4. Recommend one primary next action and one optional secondary action.
5. Avoid suggesting five new projects at once.

### When the user wants an agenda

Use `planning/visual-agenda.md` as the main agenda.

Recommended format:

- Week focus
- Now / Next / Later board
- Energy-aware task blocks
- Product pipeline cards
- End-of-day reset
- Decisions needed

### When the user is preparing a model release

1. Use `templates/release-checklist.md`.
2. Use `templates/makerworld-description-template.md` or `templates/cults3d-description-template.md`.
3. Update the relevant product page.
4. Add post-release feedback tracking.

## Product decision principles

Prefer ideas that satisfy most of these:

- solves a real problem
- easy to understand from thumbnail
- reliable to print
- not dependent on tight tolerances
- not too fragile
- not too generic
- reasonable to finish in a short time
- strong enough to become a product family
- easy to explain in a product listing
- likely to produce useful customer feedback

Avoid or pause ideas that:

- take too long without clear upside
- require fragile mechanisms
- depend heavily on screws or tight threads
- are hard to explain visually
- are too easy for anyone to copy without a unique angle
- create likely customer complaints
- need too much testing before proving the concept

## Visual agenda recommendation

For this repo, the best visual agenda format is a **Markdown Kanban + weekly focus board**.

Reason:

- GitHub displays it cleanly.
- AI assistants can edit it easily.
- It does not require external software.
- It works well on mobile.
- It keeps the user focused without becoming a heavy project management system.

Recommended columns:

| Now | Next | Later | Waiting / Feedback |
|---|---|---|---|
| The 1 to 3 things that matter now | What comes after | Ideas to keep visible | Things blocked by testing, comments, or decisions |

Use `planning/visual-agenda.md` for the live agenda and `templates/visual-agenda-template.md` as the reusable template.

## Important reminder

This repository should make the user's work easier, not heavier.

When in doubt, organize information into:

1. ideas
2. priorities
3. active projects
4. visual agenda
5. customer feedback
6. release preparation

The best AI help here is not just writing more text. It is reducing confusion, choosing the next useful step, and keeping the user's product direction realistic.