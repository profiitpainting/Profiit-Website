# PROFiiT Painting Consultants - GitHub Pages Site

This folder is ready to publish with GitHub Pages.

## Files

- `index.html` - the full website
- `assets/profiit-commercial-hero.png` - hero/background image
- `.nojekyll` - tells GitHub Pages to serve the files directly

## Easiest GitHub Upload Steps

1. Go to GitHub and create a new repository.
2. Name it something like `profiit-painting-website`.
3. Keep it public if you want free GitHub Pages hosting.
4. Upload everything inside this folder:
   - `index.html`
   - `.nojekyll`
   - the `assets` folder
5. After uploading, open the repository settings.
6. Go to **Pages**.
7. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
8. Save.
9. GitHub will give you a live website URL after a minute or two.

## GoDaddy Domain Later

After GitHub Pages is live, you can connect your GoDaddy domain to it.

In GitHub Pages, add your custom domain.
In GoDaddy DNS, point the domain to GitHub Pages using GitHub's current DNS instructions.

GitHub's official guide is the safest source for the exact DNS records:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Editing

To change the website text, edit `index.html`.

To replace the hero image:

1. Add the new image inside `assets`.
2. Update this reference in `index.html`:
   `assets/profiit-commercial-hero.png`

