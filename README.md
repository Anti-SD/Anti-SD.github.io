# AntiSD — Project Page

Static project page for **Anti-Self-Distillation for Reasoning RL via Pointwise Mutual Information**.

- **Paper:** https://www.alphaxiv.org/abs/2605.11609
- **Code:** https://github.com/FloyedShen/AntiSD
- **W&B runs:** https://wandb.ai/brain-cog/AntiSD

## Layout

```
website/
├── index.html              # the page (self-contained; Bulma + FontAwesome + MathJax via CDN)
├── .nojekyll               # serve static assets verbatim on GitHub Pages
└── static/images/          # paper figures (PNG)
```

## Preview locally

```bash
cd website && python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy (GitHub Pages)

Push the contents of `website/` to a `*.github.io` repo (or set Pages source to this
folder). No build step — it is a single static `index.html` with CDN dependencies.
