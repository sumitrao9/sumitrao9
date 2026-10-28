# Hi — I'm Sumit Yadav

MCA student at Shoolini University, Solan. Building practical software: Python,
Django, FastAPI, and full-stack TypeScript apps.

## What I'm working on

**Hound** — a token-budgeted, self-healing browser automation MCP server.

Every mainstream browser-automation MCP server returns the full accessibility tree
on every action (~10,162 tokens/action, ~114,000 for a 10-step flow). Hound budgets
every response and returns only what changed.

| Site | Conventional | Hound | Reduction |
|---|---:|---:|---:|
| news.ycombinator.com | 93,194 | 805 | **99.1%** |
| en.wikipedia.org/wiki/Web_scraping | 210,272 | 1,003 | **99.5%** |
| python.org | 47,100 | 936 | **98.0%** |
| **Total** | **350,566** | **2,744** | **99.2%** |

- 38 unit tests, no browser required
- Self-healing selector store with verification before adoption
- 7 tools, deliberate O(1) per-action design

## Other projects

- **ClientFlow** — Django 5 + DRF freelance invoicing API (33 tests, Docker, CI)
- **Job Hunter OS** — local-first job tracker: FastAPI + React/Electron (53 tests)
- **Maison Atelier** — Next.js 14 e-commerce with Prisma, NextAuth, Stripe
- **Arix** — Electron + React + TypeScript desktop workbench

## Stack

`Python` `Django` `DRF` `FastAPI` `PostgreSQL` `MCP` `Playwright` `React`
`TypeScript` `Next.js` `Electron` `Prisma` `Tailwind` `Docker` `pytest`

## Currently

First-year MCA student at Shoolini University. Focused on fundamentals: data
structures, databases, testing, and shipping working code. Open to
internship and entry-level opportunities.

- [Hound](https://github.com/sumitrao9/hound)
- [ClientFlow](https://github.com/sumitrao9/clientflow)
- [Job Hunter OS](https://github.com/sumitrao9/job-hunter-os)
- [Maison Atelier](https://github.com/sumitrao9/clothing-store)
