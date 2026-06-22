---
title: setting up server
---

# prerequisite

- [uv](https://docs.astral.sh/uv/)

> [!warning]
> Make sure that [judge0](https://docs.astral.sh/uv/) server is running.

# setting up development server

To run the server locally, install necessary dependency with `uv sync`. Copy the `.env.example` content file to `.env` (create one if you haven't done so) and configure judge0 endpoint (`JUDGE0_ENDPOINT`) and authentication key (`JUDGE0_AUTH_KEY`).

> [!note]
> You can also configure the server to work with cloud version of this at RapidAPI by configuring the following environment variables: `RAPIDAPI_KEY`, `RAPIDAPI_HOST` and `IS_RAPIDAPI`. Check the example .env file for more details.

Then, run the server with `uv run fastapi dev`.
