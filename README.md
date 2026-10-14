# BumpStory website

A small, responsive static marketing site for BumpStory. It is intentionally
kept in its own folder so it can later become a separate repository and be
published with GitHub Pages.

## Preview locally

Open `index.html` in a browser, or start a local static server from this
folder:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

The site has no build step or root-relative asset paths, so it works as a
GitHub Pages project site. When ready, move the contents of this folder into a
new repository, push them to its `main` branch, then enable Pages for the root
of `main` in the repository settings.

## Content notes

- The example portrait photos are the BumpStory photo-guidance samples.
- The App Store and Google Play availability labels say “Coming soon” until
  the public listing URLs are available.
- Update those labels and add store links in `index.html` after launch.
- Colors, responsive layout, and phone mockups are all in `styles.css` and
  plain HTML; there are no framework, font-hosting, or analytics dependencies.
