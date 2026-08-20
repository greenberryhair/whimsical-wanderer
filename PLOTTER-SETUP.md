# Whimsical Wanderer — Single Character Plotter

This package is ready to merge into the existing `greenberryhair/whimsical-wanderer` GitHub Pages repository.

## Files to upload

Copy these paths into the repository without changing the folder structure:

- `assets/css/plotter-v1.css`
- `assets/images/plotter/background.png`
- `assets/images/plotter/placeholder.png`
- `assets/images/plotter/app-icon.png`
- `assets/images/plotter/tracker-icon.png`
- `assets/images/plotter/shipper-icon.png`
- `assets/images/plotter/wanted-icon.png`
- `jcink/single-character-plotter.html`
- `jcink/single-character-plotter-selfhost.html`

After GitHub Pages deploys, the stylesheet URL is:

`https://greenberryhair.github.io/whimsical-wanderer/assets/css/plotter-v1.css`

## Recommended JCINK copy

Use `jcink/single-character-plotter-selfhost.html` after all package files are uploaded. It loads the CSS, background, placeholder, and Quick Links icons from the same GitHub Pages repository.

`jcink/single-character-plotter.html` is also included and keeps the current i.ibb image URLs while still loading CSS from GitHub Pages.

No CSS needs to be installed in the JCINK site's stylesheet. The post includes its own external stylesheet link inside `[dohtml]`.

## Editing the plotter

Change the portrait image URL, character name, quote, details, About text, Plot Ideas, Connections, OOC Notes, and destination URLs for the four Quick Links.

Traits use a 1–10 rating. Change only the number in `data-rating`, for example:

`data-rating="8"`

The ten bubbles are already in the HTML and the CSS automatically fills the correct number.

## Current Quick Links

1. Application
2. Character Tracker
3. Shipper Preferences
4. Wanted Ads
