# Kirthana D — Portfolio

A single-page portfolio site for Kirthana D, Delivery Manager. Static HTML/CSS/JS — no build step, no dependencies beyond Google Fonts.

## Preview locally

Just open `index.html` in a browser.

## Deploy to GitHub Pages (project site)

This will publish it at:
**https://f1hunterr.github.io/Kirthana/**

### 1. Create the repo

Go to https://github.com/new
- Owner: `f1hunterr`
- Repository name: `Kirthana`
- Public
- Do **not** initialize with a README (this folder already has one)

### 2. Push this folder

From inside this folder, run:

```bash
git init
git add .
git commit -m "Initial commit: Kirthana D portfolio"
git branch -M main
git remote add origin https://github.com/f1hunterr/Kirthana.git
git push -u origin main
```

If you use SSH instead of HTTPS for GitHub auth, use this remote instead:
```bash
git remote add origin git@github.com:f1hunterr/Kirthana.git
```

### 3. Turn on GitHub Pages

- Go to the repo → **Settings** → **Pages**
- Under "Build and deployment" → Source: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Save

GitHub will build and publish within a minute or two, at:
`https://f1hunterr.github.io/Kirthana/`

### Updating later

Edit `index.html`, then:
```bash
git add .
git commit -m "Update portfolio"
git push
```

Pages redeploys automatically on every push to `main`.
