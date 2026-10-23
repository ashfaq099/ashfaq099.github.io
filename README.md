# Personal academic site — Md Ashfaqur Rahman

Plain HTML, no build step. Everything is in `index.html`.

## Publish on GitHub Pages

1. The repository must be named exactly `<your-username>.github.io`. For the account `ashfaq099`, that is `ashfaq099.github.io`.
2. Put `index.html`, `README.md`, `cv.pdf`, and `assets/photo.jpg` in the repository root.
3. Go to **Settings → Pages**. Set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. The site goes live at `https://ashfaq099.github.io` within a few minutes.

## Before you publish

- Replace `your.email@example.com` in `index.html` with your real address.
- Add `cv.pdf` (your compiled LaTeX CV) to the repository root.
- Add a headshot at `assets/photo.jpg` (portrait crop, around 600 × 750 px). Without it, your initials show.
- Point the SOAP-note project's **Code** button at its own repository.
- Fill in your degree years in the Education section.

## Updating

- **News:** add a new `<li>` at the top of the list. The box starts scrolling on its own once it holds more than about six items.
- **Publications / Projects:** copy an existing `<article class="item">` block and edit it. Newest goes first.
- **Navigation:** if you add a section, give it an `id` and add a matching link in the `<nav>` at the top.
- Change the "Last updated" line in the footer each time.
