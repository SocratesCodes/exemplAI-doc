---
title: Admin authentication system
---

You can set your desired admin account with `ADMIN_EMAIL` and `ADMIN_PASSWORD` configuration on Convex dashboard or CLI with the same defined project in web. See [this page](https://docs.convex.dev/production/environment-variables#setting-environment-variables) for more information.

Optionally, declare those values in `.env` if you run CI/CD and/or running test suite for coverage. A way to do this is to wrote it to `.env` beforehand, then pasting to convex directly.

> [!warning]
> make sure that you initialize convex database in `/web` beforehand with `pnpm dlx convex dev`.


Create another separate convex instances then initialize it in `/admin` directory. You could visit (guide about convex configuration) for more detail on setting up. Afterward, run this command once it is done to setup an admin account (make sure that the terminal is currently running in `/admin`):

```bash
pnpm dlx convex run api:init:createAdminUser
```
