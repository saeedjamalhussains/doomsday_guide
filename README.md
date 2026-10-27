# Doomsday Guide

**A watch-order guide for what to catch up on before *Avengers: Doomsday*.**

A curated viewing list with runtime estimates, progress tracking, and a split
between the essential main story and the optional side material — so you can
see how much time catching up actually costs before you commit to it.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![No build step](https://img.shields.io/badge/build-none-brightgreen)

<!-- Add the live URL here once Pages is enabled, and set it as the repo's
     Website field in the About box. A static-site repo with no live link
     gives a visitor nothing to look at. -->

## Features

- **Tracked progress** — tick things off as you watch; your place is remembered
  between visits.
- **Runtime estimates** so you can budget the catch-up realistically.
- **Main story vs. side material**, separated, so the optional stuff is clearly
  optional.
- **Export and import your progress** as JSON — no account, nothing leaves your
  browser.
- **One file, no build step.** Open it and it works.

## Running it

Open `index.html` in any browser. That's the whole setup.

To publish: enable GitHub Pages under **Settings → Pages**, source `main` /
root. The included workflow in `.github/workflows/` deploys on every push to
`main`.

## How it's built

Everything — HTML, CSS, JavaScript, and the data — lives in the single
`index.html`. No backend, no framework, no bundler. Progress and settings are
stored in the visitor's browser via `localStorage`, and can be exported or
imported as JSON.

## Maintaining the data

Runtimes and links are curated by hand, and series runtimes are estimates. The
News tab is static: when you edit it, update both its dated entries and the
"last verified" date in `index.html`.

## Contributing

Corrections to runtimes, ordering, or links are welcome — open an issue or a PR.
