# Victor Oizamsi Daudu — Portfolio

Static portfolio site. No build step: `index.html` plus the `assets/` folder.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, e.g. `victordaudu.github.io`
   (using `<your-username>.github.io` gives you the cleanest URL).
2. Upload everything in this folder (`index.html`, `assets/`, `.nojekyll`, `README.md`)
   to the root of the repository: **Add file → Upload files**, drag them in, **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to
   *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/`
   (or `https://<your-username>.github.io/<repo-name>/` for any other repo name).

## Custom domain (optional)

Buy a domain, then in **Settings → Pages → Custom domain** enter it and follow
GitHub's DNS instructions. Tick **Enforce HTTPS** once it becomes available.

## Updating

- Resume: replace `assets/Victor_Oizamsi_Daudu_Resume.pdf` with your new PDF (same file name).
- Text: edit `index.html` directly on GitHub (pencil icon) and commit.
