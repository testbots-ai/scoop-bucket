# scoop-bucket

Scoop bucket for [testbot-agent](https://testbots.ai) — a free-tier local Playwright test runner.

Source code and CI live in a private repository; this bucket is kept in sync with each tagged
release automatically (see `testbot-agent`'s `.github/workflows/release.yml`). Don't hand-edit
`bucket/testbot-agent.json` — it will be overwritten on the next release.

## Install

```sh
scoop bucket add testbots-ai https://github.com/testbots-ai/scoop-bucket
scoop install testbot-agent
```
