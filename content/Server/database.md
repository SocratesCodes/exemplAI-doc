---
title: Database
---

> [!warning]
> This is a work in progress

This guides helps developer setting up places to store courses and user data for the application.

Requires [Convex](https://www.convex.dev/) account.

> [!warning]
> This assumes project is cloned and prerequisite are met.

1. In the project directory, move into the `/web` location:

```bash
cd ./web  # in the project
```

2. Installs dependencies

```bash
pnpm install
```

3. Setting up a convex project via CLI by using convex CLI's development mode:

```bash
pnpm dlx convex dev
```

Visit [here](https://docs.convex.dev/understanding/workflow) for more information on setting up convex (locally).

You may see a generated `.env.local` with convex's environment variables. These are for establishing information with convex's database.
