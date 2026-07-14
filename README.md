# GitBlock

A tower raised one stone at a time.

Enter a GitHub username and watch their contribution history materialize as a medieval stone tower. Every commit lays one stone — the more they build, the taller the tower rises.

## How It Works

1. Enter a GitHub username
2. Click **RAISE THE TOWER** (or press Enter)
3. The app fetches the last 365 days of public contributions via the [GitHub Contributions API](https://github-contributions-api.jogruber.de)
4. Each contribution becomes a textured stone block, laid in a running bond pattern
5. Contribution intensity (level 1–4) maps to stone shading — busier days produce darker, more weathered stone
6. For very active accounts, stones are scaled so the tower stays under ~1400 blocks; milestone plaques mark progress

## Features

- **Running bond masonry** — offset courses with half-stone fillers create authentic vertical joint staggering
- **Three stone textures** — speckled radial-gradient patterns so no two neighbors look identical
- **Animated construction** — stones rise into place sequentially with cascading delays
- **Crown details** — crenellated parapet, machicolations, conical roof with weather vane
- **Environmental touches** — drifting clouds, flying birds, flickering torch sconces, creeping ivy
- **Reduced motion** — respects `prefers-reduced-motion` by disabling all animations

## Usage

Open `index.html` in a browser. No build step, no dependencies — just a single HTML file.

```sh
open index.html
```

## License

Data sourced from GitHub's public contribution graph. Not affiliated with GitHub.
