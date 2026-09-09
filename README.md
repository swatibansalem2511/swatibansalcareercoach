# Swati Bansal · Career & Leadership Coach

Static single-page site for Swati Bansal's career and leadership coaching practice.
No build step — the page is a self-contained `index.html` (inline CSS and JS).

## Run locally

Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. In the repo: **Settings → Pages → Source → Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder, then Save.
4. The site goes live at `https://<your-username>.github.io/<repo-name>/`.

For a top-level URL (`https://<your-username>.github.io/`), name the repo
`<your-username>.github.io` and enable Pages on its `main` branch.

## Before going live

- Set `COACH_EMAIL` in `index.html` to the real contact address (search for
  `yourname@example.com`).
- Replace placeholder testimonials, talk titles, and company names (search for
  `[Replace` and `[Company`).
