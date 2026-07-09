# Ansh Singh — Portfolio

Personal portfolio site. Static HTML/CSS, no build step.

## Files
- `index.html` — the site (edit content and the GitHub link here)
- `Ansh_Singh_CV.pdf` — downloadable CV (must stay next to index.html)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy with GitHub Pages

### Option A — via the GitHub website (no command line)
1. Sign in at github.com and click **New repository**.
2. Name it `your-username.github.io` (use your actual username — this gives the cleanest URL). Set it to **Public**. Create it.
3. On the new repo page, click **uploading an existing file**.
4. Drag in `index.html`, `Ansh_Singh_CV.pdf`, `.nojekyll`, and this `README.md`. Commit.
5. Go to **Settings → Pages**. Under "Build and deployment", set Source = **Deploy from a branch**, Branch = **main**, folder = **/(root)**. Save.
6. Wait ~1 minute. Your site is live at `https://your-username.github.io`.

### Option B — command line
```bash
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```
Then enable Pages in Settings → Pages as in step 5 above.

## Before you publish
- In `index.html`, replace `github.com/your-username` with your real GitHub handle (appears twice: the contact row link and its href).
```
