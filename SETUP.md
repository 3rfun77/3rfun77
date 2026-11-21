# GitHub profile V4 — publish guide

## 1. Upload the profile

1. Create a **public** repository named exactly **`3rfun77`** under your GitHub account `3rfun77`, or use your existing repository of that name.
2. Upload `README.md`, the whole `assets/` folder, and the whole `game/` folder to the **repository root**, keeping their paths.
3. Commit to `main`. Your profile README will appear on `https://github.com/3rfun77`.

## 2. Enable the playable mini-game

1. Open **Repository Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the **`main`** branch and **`/(root)`** folder; save.
4. When GitHub Pages publishes, the **Packet Runner** game link becomes:
   `https://3rfun77.github.io/3rfun77/game/`

The game can also be tested locally by opening `game/index.html` in a modern browser. It is **one standalone HTML file**, with CSS transitions and JavaScript built in and no external dependencies.

## 3. What animates where?

- `assets/hero.svg`: soft telemetry indicators and flowing packets, inside the README.
- `assets/typing.svg`: rotating intro lines, inside the README.
- `assets/capabilities.svg`: three clean technology and ability cards.
- `assets/game-card.svg`: animated packet mini-preview and a clickable link, inside the README.
- `game/index.html`: real interactive game with animated particles, hover effects, score effects, and transitions; it runs on **GitHub Pages**, not inside the README.

GitHub filters custom CSS and JavaScript from rendered Markdown. Animated SVGs are the best fit for a self-contained README. SVG animation behavior can vary by client or reduced-motion settings; the images retain a readable first frame.

## Customization

- Edit `README.md` to change copy, URLs or technology badges.
- SVG assets are plain-text vector files and can be edited directly.
- Game colors and sizes are in CSS variables at the top of `game/index.html`.
- Optional: rename the GitHub Pages repository or move the game only if you also update the link in `README.md`.

No contact phone/address is displayed. This version is intentionally skills-only. No employer names, internal system names, client projects, or work-specific metrics are included.
