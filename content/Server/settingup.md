---
title: setting up server
---

# prerequisite

- [uv](https://docs.astral.sh/uv/)

> [!warning]
> Make sure that [judge0](https://docs.astral.sh/uv/) server is running.

# setting up development server

To run the server locally, install necessary dependency with `uv sync`. Copy the `.env.example` content file to `.env` (create one if you haven't done so) and configure judge0 endpoint (`JUDGE0_ENDPOINT`) and authentication key (`JUDGE0_AUTH_KEY`).
