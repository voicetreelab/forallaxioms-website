# forallaxioms.com

The landing page for [forallaxioms.com](https://forallaxioms.com) — the company site for
ForAllAxioms Pty Ltd, makers of [VoiceTree](https://voicetree.io).

It is a single static `index.html` (no build step, no framework). Keep it that way unless
the site genuinely outgrows one page.

## Hosting

Deployed on **Cloudflare Pages**, git-connected to this repo:

```
git push  ──▶  Cloudflare Pages  ──▶  https://forallaxioms.com  (auto HTTPS)
```

Every push to `main` triggers an automatic deploy. There is no build command; the output
directory is the repo root.

## Editing

1. Edit `index.html`.
2. `git commit && git push`.
3. Cloudflare Pages deploys automatically within a minute.
