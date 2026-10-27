# Personal site

A single-page, desktop-style personal website. No build step.

- `index.html` — the whole site (HTML, CSS, JS in one file)
- `assets/cv.pdf` — the CV linked from the desktop and Finder
- `assets/photos/` — gallery images. Edit the `PHOTOS` list near the bottom of `index.html` to match your filenames and captions.

## Deploy on GitHub Pages

1. Create a repo named `<your-username>.github.io` (or any repo name).
2. Put these files at the repo root and push.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Wait a minute, then open `https://<your-username>.github.io/` (or `/<repo-name>/`).
