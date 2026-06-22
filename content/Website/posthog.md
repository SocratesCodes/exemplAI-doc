---
title: Analytics
---

> [!warning]
> This is a work in progress

> [!warning]
> There is possibility that analytics could be incorrect due to user using privacy mode.

> [!note]
> We are working hard on this to ensure the data collection respects user privacy and research methodologies.

This application uses [PostHog](https://posthog.com/) for collecting user information. In the future, options are available to configure this behaviour as it may not be necessarily for research purpose;

Create a Posthog project in any region (EU or US), skip the onboarding screen that prompts to use wizard tool (since the project is already initialized), goes to setting and copy those credential to `/web/.env` (or `.env.local`):

```env
# Project metadata including

# Project token
VITE_PUBLIC_POSTHOG_PROJECT_TOKEN=

# Region (https://eu.i.posthog.com or https://us.i.posthog.com)
VITE_POSTHOG_HOST=
```
