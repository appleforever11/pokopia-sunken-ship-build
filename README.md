# Pokopia Sunken Pirate Ship Build Tracker

This folder is a GitHub Pages-ready static site.

Upload the folder contents together:

- `index.html` — the root page for GitHub Pages.
- `Pokopia_Sunken_Ship_Build_Tracker.html` — the descriptive direct-link filename.
- `media/` — sixteen focused H.264 MP4 micro-clips: two action clips for each of the eight build passes.
- `assets/inventory/` — actual Pokopia item/UI PNGs copied from the local asset bundle used by the separate builder project.

For GitHub Pages, create or use a repository, upload these files to the repository root, then enable Pages from the repository’s main branch and root folder. The page has no build step or external JavaScript dependencies. The HTML embeds the screenshots; the companion `media` folder must remain beside the HTML files for the video clips to play.

The guide includes a dedicated Inventory tab with rounded starting quantities, saved checkboxes, recipe strips, and actual bag-style item icons. Hover over a still on desktop, or tap it on iPhone, to open the enlarged preview window. The clips are muted, 960×540, H.264/yuv420p MP4 files with `playsinline` and native controls so they work inside desktop browsers and iPhone Safari. Each clip opens at 0.5× playback and includes 0.25× extra-slow, 0.75×, and 1× speed buttons; the selected speed is remembered for the next clip, and starting one clip pauses the others. Every clip also has a saved Watched check plus a Next unwatched button, so the video walkthrough can be completed without losing your place.
