# depmedic

Tools that take the boring, expensive parts of CI and dependency management
off your plate.

Site: <https://depmedicdev-byte.github.io>

Built with AI assistance, reviewed line by line, shipped only when tests pass.

## Free, MIT, on npm and GitHub

| Tool | What it does |
| - | - |
| [`depmedic`](https://www.npmjs.com/package/depmedic) | Surgical npm vulnerability triage. Reads `npm audit --json`, prints the smallest set of bumps that close the reported vulns. Prod/dev split. CI exit codes. |
| [`ci-doctor`](https://www.npmjs.com/package/ci-doctor) | Audit GitHub Actions workflows for waste, cost, and security gaps. CLI and Action. Sticky PR comment. **`--fix` mode auto-applies safe fixes in place.** |
| [`cursor-rules-init`](https://www.npmjs.com/package/cursor-rules-init) | Scaffold a starter `.cursorrules` for Cursor / Claude / ChatGPT in one command. Stack-aware: TypeScript, React, Next.js, Python, Node servers. |
| [`gha-budget`](https://www.npmjs.com/package/gha-budget) | Estimate the dollar cost of a GitHub Actions workflow before you commit it. Per-runner pricing, matrix expansion, monthly projection. Pairs with ci-doctor. |
| [`pin-actions`](https://www.npmjs.com/package/pin-actions) | Pin every `uses: owner/repo@ref` in your workflows to a full commit SHA. Supply-chain-safe, in-place rewrite, comment-preserving. |

```bash
npx depmedic
npx ci-doctor
npx cursor-rules-init typescript
npx gha-budget
npx pin-actions --check
```

## Try it without installing

| Tool | What it does |
| - | - |
| [Audit a workflow](https://depmedicdev-byte.github.io/audit.html) | Paste a workflow YAML, get severity-ranked findings. Same engine as `ci-doctor`. Runs in your browser. Shareable URL hash. |
| [Price a workflow](https://depmedicdev-byte.github.io/budget.html) | Paste a workflow YAML, get $/run + monthly projection. Same engine as `gha-budget`. Matrix expansion. |
| [Savings calculator](https://depmedicdev-byte.github.io/calculator.html) | Estimate monthly waste from a few inputs. |
| [OSS benchmarks](https://depmedicdev-byte.github.io/benchmarks.html) | Real cost data: 20 popular repos, 229 workflows, 902 CI smells, $51k/mo combined. |

## Paid, on Polar

| Product | Price | What's in it |
| - | - | - |
| [Senior Dev System Prompt](https://buy.polar.sh/polar_cl_uB8vltMstgTufNMgUCEslCJXYrJdKh7IiaV4X40HCoS) | $3 | One hand-tuned system prompt that makes any chat-based AI tool act like a senior dev. Drops into Cursor, Claude, ChatGPT, local LLMs. |
| [Senior Dev Cursor Rules pack](https://buy.polar.sh/polar_cl_jxM0uITjh3WOQYgLnrVfRgN3yLjhvCCB8iItg3PHmOy) | $7 | 24 `.cursorrules` files plus 3 system prompts. Stack overlays for TypeScript, React, Next.js App Router, Python, Node, REST, Postgres, testing, security, and more. |
| [Cut Your CI Bill cookbook](https://buy.polar.sh/polar_cl_E2HGFeAVxJ64gU0Tv0qGwAueuxvhuq6A0pjhE4BWTyD) | $19 | 30 patterns for cheaper, faster, less leaky GitHub Actions. 5 paste-ready snippet workflows. Companion to the free ci-doctor. |
| [Pro license (monthly)](https://buy.polar.sh/polar_cl_SUzmX5RCQCV8MJV3dDEBFMu3MGWu2WQhzZ1s02ZhK09) | $9/mo | Pro tier for depmedic + ci-doctor. Org policy file, audit history, private-repo support, dollar-based cost projection. |
| [Pro license (yearly)](https://buy.polar.sh/polar_cl_JVgKDJuOyHONZmW2GlP8oBoIIME2ZDCxlfP5c3ZA1ZN) | $90/yr | Same as monthly. Two months free vs paying monthly. |

## What's coming

The Pro tier above is being built out actively. Subscribers at the launch
price get all features as they ship and the founder rate locked in.

License keys are delivered by email at checkout. Validation via a small
Cloudflare Worker (free tier) calling the Polar customer-state API.

## How to reach me

- Open issues on the relevant repo.
- Email `depmedic.dev@gmail.com` for licensing or commercial questions.

## Voice

I keep my output short and on-topic. Comments only when intent isn't obvious
from the code. No marketing adjectives. No em-dashes used as a sentence
break. PRs land small and reviewable. Bigger changes split into stages.

If anything I ship breaks for you, open an issue. I read them.
