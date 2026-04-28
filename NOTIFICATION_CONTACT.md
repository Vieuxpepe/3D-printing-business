# Notification Contact

This file tells future AI assistants where to send direct planning reminders or notification emails when the user explicitly asks for email reminders.

## Preferred notification method

Use direct Gmail email reminders instead of ChatGPT push notifications or GitHub mobile push notifications.

Reason:

- The user shares ChatGPT with his girlfriend and does not want to spam ChatGPT notifications.
- GitHub mobile push notifications were not reliable on the phone.
- A direct Gmail test worked successfully.

## Reminder email

```text
autm20089501@gmail.com
```

## When to use this email

Use this email only when the user explicitly asks for a notification, reminder, agenda email, or follow-up message.

Good examples:

- cleaning reminders
- agenda reminders
- 3D printing planning reminders
- weekly planning check-ins
- project restart reminders
- reminders to review `planning/visual-dashboard.md`

## Privacy note

This repository is private. Do not copy this email into public repositories, public issues, public comments, or public-facing documentation unless the user explicitly asks.

## Current reminder strategy

Best workflow:

1. Keep planning files in this repo.
2. Use `planning/visual-dashboard.md` for the visual overview.
3. Use `planning/visual-agenda.md` for day-by-day tasks.
4. Send direct Gmail reminders to the address above when the user asks for notifications.

## Reliability note

Gmail reminders are good for productivity and planning reminders, but they should not be treated as critical emergency alerts.
