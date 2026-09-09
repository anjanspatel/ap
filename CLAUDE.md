# CLAUDE.md

## gstack

This project uses [gstack](https://github.com/garrytan/gstack) — a suite of Claude Code slash-command skills.

**Web browsing:** Use the `/browse` skill from gstack for all web browsing. Never use `mcp__claude-in-chrome__*` tools.

**Available skills:**

| Skill | Description |
|-------|-------------|
| `/office-hours` | YC Office Hours — product interrogation with forcing questions |
| `/plan-ceo-review` | CEO/founder-mode plan review |
| `/plan-eng-review` | Eng manager-mode plan review |
| `/plan-design-review` | Designer's eye plan review |
| `/design-consultation` | Full design system proposal |
| `/design-shotgun` | Generate multiple design variants for comparison |
| `/design-html` | Production-quality HTML/CSS design finalization |
| `/review` | Pre-landing PR review |
| `/ship` | Ship workflow: merge, test, review, bump version, push, create PR |
| `/land-and-deploy` | Land and deploy workflow |
| `/canary` | Post-deploy canary monitoring |
| `/benchmark` | Performance regression detection |
| `/browse` | Drive a real browser to read pages, click flows, take screenshots |
| `/connect-chrome` | Launch AI-controlled Chromium with sidebar extension |
| `/qa` | Systematically QA test a web app and fix bugs found |
| `/qa-only` | Report-only QA testing |
| `/design-review` | Visual inconsistency and AI slop detection |
| `/scrape` | Pull data from a web page |
| `/setup-browser-cookies` | Import cookies from real Chromium into headless session |
| `/setup-deploy` | Configure deployment settings for /land-and-deploy |
| `/setup-gbrain` | Set up gbrain knowledge base |
| `/retro` | Weekly engineering retrospective |
| `/investigate` | Systematic root cause debugging |
| `/document-release` | Post-ship documentation update |
| `/document-generate` | Generate missing documentation |
| `/codex` | OpenAI Codex CLI wrapper |
| `/cso` | Chief Security Officer mode — OWASP + STRIDE audit |
| `/autoplan` | Full auto-review pipeline (CEO + design + eng + DX) |
| `/plan-devex-review` | Interactive developer experience plan review |
| `/devex-review` | Live developer experience audit |
| `/careful` | Safety guardrails for destructive commands |
| `/freeze` | Restrict edits to a specific directory |
| `/guard` | Full safety mode |
| `/unfreeze` | Clear freeze boundary |
| `/gstack-upgrade` | Upgrade gstack to latest version |
| `/learn` | Manage project learnings |
