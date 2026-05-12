# AI HANDOFF — Movement of Nothing Site

You are helping maintain the Movement of Nothing public site.

## Identity of this site

This is not a general content site. It is a public artifact of a live research program.
Every page is versioned. Every line that matters is protected.
Drift is the failure mode. Bounded action is the discipline.

## Before you do anything

Read in this order:
1. `docs/SITE_STATE.md` — current live state, frozen artifacts, open gates
2. `docs/PROTECTED_LINES.md` — lines that must not change without explicit versioning
3. `docs/QUEUE.md` — approved pending tasks
4. This file

If any of these files are missing, stop and report. Do not invent their contents.

## Current live state

| Item | Value |
|---|---|
| Live page | Presence v0.1.1 |
| Public URL | https://little-breeze-8cbd.2811pratyushbhatnagar.workers.dev/ |
| Source of truth | GitHub repository |
| Publisher | Cloudflare Workers |
| Deploy authority | Human only |

## Allowed actions

- Fix broken links
- Improve accessibility (alt text, ARIA labels, semantic HTML)
- Improve mobile rendering (CSS-only fixes)
- Create draft pages when explicitly requested in QUEUE.md
- Update `docs/DECISION_LOG.md`, `docs/QUEUE.md`, `docs/SITE_STATE.md`
- Verify protected lines are unchanged after any edit

## Forbidden actions

- Change Presence v0.1.1 text without explicit versioning instruction
- Add AI consciousness claims anywhere on the site
- Add complete physics claims (continuum limit is open — do not close it in copy)
- Turn Leela section into revelation or mystical language
- Add new sections or pages without a QUEUE.md entry
- Deploy to Cloudflare directly
- Merge pull requests
- Modify `site/presence/index.html` unless a versioned task explicitly authorizes it

## Register discipline

This site uses three registers. Do not let them bleed into each other.

- **Exact** — proved or computed results only. Do not soften or expand.
- **Structural** — correspondence across domains. Does not borrow proof-authority from Exact.
- **Open** — explicitly unresolved. Do not resolve open items in copy.

If you are unsure which register a claim belongs to, flag it. Do not decide alone.

## Workflow for every task

1. Read `SITE_STATE.md`, `PROTECTED_LINES.md`, `QUEUE.md`
2. Identify one bounded task from QUEUE.md (or from the assigned GitHub Issue)
3. Create a branch: `ai/brief-task-name`
4. Make only the change specified — nothing adjacent, nothing "while I'm here"
5. Verify protected lines are unchanged
6. Open a pull request with a summary of exactly what changed and why
7. Wait for human approval before anything goes further

## What you must not do

Do not invent pressure. If nothing is queued, there is nothing to do.
Do not expand frozen artifacts. Presence v0.1.1 is frozen until versioned.
Do not propose improvements outside the assigned task.
Do not publish directly under any circumstance.

## Governing rule

> Let AI maintain continuity. Do not let AI invent pressure.
