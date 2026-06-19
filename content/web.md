---
title: Website
---

> [!warning]
> This is under construction

The main interface for student to code problems.

# Configurations

> [!warning]
> This guide assumes [coolify](https://coolify.io/self-hosted) and backend server is installed.

You would need Node.js and Git installed.

Install `pnpm` if you haven't already done so via [this guide](https://pnpm.io/installation).

Ensure that both server and judge0 is up and running.

In web directory, copy `.env.example` to .env, and configures the following variables:

- `VITE_BACKEND_URL` - URL of backend server. Defaults to local development.
