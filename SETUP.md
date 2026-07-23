# Setup Notes

This repo works immediately after you push it as `Code-Domain/Rohit-Jha`
(a GitHub **profile repo** must be named exactly your username — here that's
`Rohit-Jha`... actually GitHub profile READMEs require the repo to be named
exactly `Code-Domain`. See step 1 below).

## 1. Repo name
GitHub only renders a profile README automatically when the repository is
named **exactly your username**: `Code-Domain`. If you want the special
profile page (the one shown at github.com/Code-Domain), rename this repo to
`Code-Domain` after pushing — or simply keep it as `Rohit-Jha` as a normal
portfolio repo and copy `README.md` into your `Code-Domain/Code-Domain` repo.

## 2. Push
```bash
git init
git add .
git commit -m "Initial commit: futuristic AI profile"
git branch -M main
git remote add origin https://github.com/Code-Domain/Code-Domain.git
git push -u origin main
```

## 3. Let the Actions run once
Go to the **Actions** tab and manually trigger:
- `Generate Snake Animation` — creates the `output` branch with the snake SVGs
- `Update Profile Metrics` — generates `images/metrics.svg`

Both are also scheduled to re-run automatically (daily / every 12 hours).

## 4. Update your real links
In `README.md`, replace the `#` placeholders in the **Connect With Me**
section with your actual LinkedIn, X/Twitter, and email links.

## 5. Optional: swap SVGs for PNGs
Every graphic ships as a hand-built SVG in `assets/` so the repo works with
zero external dependencies. If you'd rather use AI-generated raster art, see
`assets/PROMPTS.md` for ready-to-use prompts, then update the file extensions
referenced in `README.md`.
