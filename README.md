# Tread Social Playbook

The reference Tread Marketing checks before every post.

**Live:** https://clem-treads.github.io/tread-social-media/
**Owner:** Clem · Marketing
**Audience:** Internal (Tread team, sales enablement)
**Revisited:** Every 60 days against live performance data.

## What's in it

- **Strategy** — voice, persona cast, why Tread sounds the way it does
- **Generator** — Claude-powered drafting tool (users supply their own Anthropic API key, stored locally in their browser)
- **System** — 5 subjects × 7 treatments × 4 channels × 2 voices
- **Craft** — visual hierarchy, copy lengths, hook test, killed-phrases wall
- **Sameer** — Builder / Witness / Observer modes, receipts library
- **Operations** — Monday huddle, weekly workflow, MQL math, edge-case decisions
- **Reference** — FAQ + shipping checklist

## Updating

The canonical working file lives outside this repo. Drop the latest version into `index.html`, commit, push to `main`. GitHub Pages serves from `main` automatically.

```
cp /path/to/latest_playbook.html index.html
git add index.html
git commit -m "Update playbook to vX.Y"
git push origin main
```

## Versions

- **v1.3** (2026-05) — Operations pane, 8 persona anchors, expanded Sameer modes, live Claude-powered Generator
- **v1.1** (2026-05) — 6-tab structure, interactive UX, brand polish
- **v1.0** (2026-05) — Initial playbook
