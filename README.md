# srinagesh.github.io

Personal research website. One static page (`index.html`), no build step.

## Files

- `index.html` — the whole site (content, styles, and the orbit animation).
- `images/profile.jpg` — your photo (square, at least 400×400). Until it exists, the page shows your initials.
- `cv.pdf` — the CV linked from the header. Use a public version without your phone number.
- `.nojekyll` — tells GitHub Pages to serve the files as-is instead of running Jekyll.

## Preview locally

    cd ~/src/srinagesh.github.io && python3 -m http.server 8000
    # open http://localhost:8000

## Publish on GitHub Pages

1. Push to `main` (this repo, `srinagesh/srinagesh.github.io`).
2. First time only: on GitHub, Settings → Pages → Build and deployment → Source: "Deploy from a branch",
   Branch: `main`, folder `/ (root)`.
3. The site appears at https://srinagesh.github.io within a minute or two; later pushes update it the same way.

## Updating

- News, publications, and patents are plain HTML lists in `index.html`; copy an existing `<li>` and edit it.
- Keep the footer's "Last updated" date current.
- Accent colour and fonts are set in the `:root` block at the top of the `<style>` section.
