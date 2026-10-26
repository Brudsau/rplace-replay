# r/place 2022 — interactive replay

A static replay of the shared canvas, prepared for Bruno Sales's presentation
*New Frontiers and the Reallocation of Conflict*, Insper, 29 October 2026.

Drag the time slider, play/pause, jump to either expansion, scroll to zoom, and
drag the canvas to pan. All assets use relative URLs, so the site works on a
GitHub Pages project path without a server or build step.

## Data

500 ten-minute snapshots, labeled at the end of each interval, reconstructed
from the public Reddit r/place 2022 placement history. Times are UTC. The
display samples the full canvas at 1,000 × 1,000 pixels. This is a historical,
accelerated replay; it does not connect to a live game.

The original history is available from [Reddit's canvas-history archive](https://placedata.reddit.com/data/canvas-history/index.html).

## GitHub Pages

Publish the `main` branch from the repository root in **Settings → Pages**.
Keep `index.html`, `frames.js`, `.nojekyll`, and the `frames/` directory together.
No Node.js, Python, database, tunnel, login, or running laptop is needed by
visitors once GitHub Pages has published the site.
