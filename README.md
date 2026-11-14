# Sylvie Glow Guide

A skin-brightening quiz app: 9 questions, then personalized product picks and a morning and night routine.

| Path | What it is |
| --- | --- |
| `index.html` | The Sylvie Glow Guide app |
| `demo/index.html` | White-label demo for beauty businesses (`/demo/#lumiere`, `/demo/#beauty-supply`) |

Both are self-contained static pages with no build step.

## Host with GitHub Pages
Settings → Pages → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
The site goes live at `https://<username>.github.io/<repo>/`.

## Make a client version
1. Copy `demo/index.html` to a new folder, e.g. `clients/lumiere/index.html`.
2. Edit only the **CLIENT SETTINGS** block at the top (name, colors, booking link, products).
3. Set `showDemoSwitcher: false`, commit, and share `https://<username>.github.io/<repo>/clients/lumiere/`.

## Lead form (Pro plan)
Create a form at formspree.io, paste its URL into `leadEndpoint` and set `leadCapture: true`.

Educational skincare guidance, not medical advice.
