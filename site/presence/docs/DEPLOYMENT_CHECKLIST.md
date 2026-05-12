# DEPLOYMENT CHECKLIST — Presence v0.1.1 at /presence

## Pre-deploy verification

- [ ] `site/presence/index.html` contains exact physics block:
      `flat sector: h = 0 → x = 0 → W_M = 0  [forbidden]`  (separate line from mode-locking)
      `mode-locking: h = ±2 → h = ±1  at  β_lock(N)`
- [ ] Final three lines present:
      `Do not force closure.`
      `Read what remains.`
      `Place it in the right register.`
- [ ] No analytics, tracking scripts, or external calls except Google Fonts CDN
- [ ] Title: `Presence — Movement of Nothing`
- [ ] Mobile breakpoint present (`max-width: 540px`)
- [ ] Root route (`/`) untouched

## Deploy steps (Cloudflare Workers / Pages)

```bash
# If using Cloudflare Pages:
git add site/presence/index.html
git commit -m "deploy: Presence v0.1.1 at /presence"
git push origin main
# Cloudflare auto-deploys on push

# If using Wrangler:
wrangler pages deploy site/ --project-name=movementofnothing
```

## Post-deploy

- [ ] Open `[domain]/presence` in browser
- [ ] Verify physics block renders in monospace
- [ ] Verify final three lines visible at bottom
- [ ] Record in DECISION_LOG.md:
      URL: [domain]/presence
      Date: 2026-05-12
      Version: Presence v0.1.1

## Then stop.

Next pressure will announce itself.
