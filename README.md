# AI Tools Lab

This repository is a personal index for AI earning, scraping, browser automation, and spec-driven development tools installed on this machine.

## Local Sources

All downloaded upstream projects are stored outside this repo to avoid committing large third-party source trees:

- `C:\Users\PC\Documents\AI落地应用\github-open-source\browser-act-skills`
- `C:\Users\PC\Documents\AI落地应用\github-open-source\spec-kit`
- `C:\Users\PC\Documents\AI落地应用\github-open-source\follow-builders`
- `C:\Users\PC\Documents\AI落地应用\github-open-source\AiToEarn`

## Installed Codex Skills

BrowserAct:

- `browser-act`
- `browser-act-skill-forge`

Scraping and research:

- `web-search-scraper-api-skill`
- `web-research-assistant`
- `google-search-serp`
- `xiaohongshu-search`
- `zhihu-search-api-skill`
- `youtube-transcript-extractor-api-skill`

Builder digest:

- `follow-builders`

## Installed CLIs

Spec Kit:

- `specify` installed via `uv tool install`
- Binary path: `C:\Users\PC\.local\bin\specify.exe`

pnpm:

- Installed globally with npm.

## Notes

AiToEarn backend dependencies were installed with `pnpm install`.

AiToEarn web dependency installation is currently blocked by its upstream `pnpm-lock.yaml`: the `xlsx` tarball entry is missing an integrity field. The safest next step is to run the project with its recommended Node 20.18.x environment and regenerate the web lockfile in a separate branch or copy.

## Upstream Repositories

- BrowserAct Skills: https://github.com/browser-act/skills
- Spec Kit: https://github.com/github/spec-kit
- Follow Builders: https://github.com/zarazhangrui/follow-builders
- AiToEarn: https://github.com/yikart/AiToEarn
