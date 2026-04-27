# depmedic

Tools that take the boring, expensive parts of CI and dependency management
off your plate.

Built with AI assistance, reviewed line by line, shipped only when tests pass.

## Free, MIT, on npm and GitHub

| Tool | What it does |
| - | - |
| [`depmedic`](https://www.npmjs.com/package/depmedic) | Surgical npm vulnerability triage. Reads `npm audit --json`, prints the smallest set of bumps that close the reported vulns. Prod/dev split. CI exit codes. |
| [`ci-doctor`](https://www.npmjs.com/package/ci-doctor) | Audit GitHub Actions workflows for waste, cost, and security gaps. CLI and Action. Sticky PR comment with findings and fixes. |

```bash
npx depmedic
npx ci-doctor
```

## Paid, on Polar

| Product | Price | What's in it |
| - | - | - |
| [Senior Dev System Prompt](https://polar.sh/depmedicdev/cursor-prompt) | $3 | One hand-tuned system prompt that makes any chat-based AI tool act like a senior dev. Drops into Cursor, Claude, ChatGPT, local LLMs. |
| [Senior Dev Cursor Rules pack](https://polar.sh/depmedicdev/cursor-rules) | $7 | 24 `.cursorrules` files plus 3 system prompts. Stack overlays for TypeScript, React, Next.js App Router, Python, Node, REST, Postgres, testing, security, and more. |
| [Cut Your CI Bill cookbook](https://polar.sh/depmedicdev/gha-cookbook) | $19 | 30 patterns for cheaper, faster, less leaky GitHub Actions. 5 paste-ready snippet workflows. Companion to the free ci-doctor. |

## What's coming

A Pro tier for `depmedic` and `ci-doctor`: org-wide policy files, audit
history pages, private-repo support, dollar-based cost projections, and a
reachability check for npm vulnerabilities. License via Polar.

## How to reach me

- Open issues on the relevant repo.
- Email `depmedic.dev@gmail.com` for licensing or commercial questions.

## Voice

I keep my output short and on-topic. Comments only when intent isn't obvious
from the code. No marketing adjectives. No em-dashes used as a sentence
break. PRs land small and reviewable. Bigger changes split into stages.

If anything I ship breaks for you, open an issue. I read them.
