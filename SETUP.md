# Publish your GitHub Profile — V7

This version blends into GitHub's native theme instead of using dark-blue dashboard graphics.

## Upload the files

1. Open your **public** repository `3rfun77/3rfun77`.
2. Upload `README.md`, the complete `assets/` directory, and `game/` directory from this package to the **repository root**.
3. Commit on `main` (or your site's publishing branch). The profile README is shown at `https://github.com/3rfun77`.

## Light/dark appearance

The README uses GitHub's `<picture>` support to serve `hero-light.svg` / `hero-dark.svg` and `game-light.svg` / `game-dark.svg`, plus mobile-sized versions for narrow screens. The **Core stack uses native `<kbd>` elements**, so colors and text wrapping are handled by GitHub rather than a fixed-width image. If your browser/OS theme differs from GitHub's manually chosen theme, the source-selection behavior may vary. The default/fallback images are light.

## Enable the playable game

1. In the profile repository go to **Settings → Pages**.
2. Select **Deploy from a branch** → `main` → `/(root)` → **Save**.
3. After successful deployment, the game will appear at `https://3rfun77.github.io/3rfun77/game/`.

The game is a standalone `game/index.html` page and includes CSS and JavaScript. It follows your system's light/dark preference. GitHub README pages themselves do not run standalone HTML, CSS or JS games.

## Clean-up

You can delete the older `assets/hero.svg`, `assets/typing.svg`, `assets/focus.svg`, `assets/stack.svg`, and `assets/game-card.svg` from previous versions; the new README no longer references them. The new files are `hero-light.svg`, `hero-dark.svg`, `hero-light-mobile.svg`, `hero-dark-mobile.svg`, `game-light.svg`, `game-dark.svg`, `game-light-mobile.svg`, and `game-dark-mobile.svg`.

The public README stays general: no employer names, internal project names, or company-specific accomplishments.
