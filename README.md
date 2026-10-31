# EnviroRock — Client Presentation

This repository contains the **client-facing presentation only**.

## Public website

GitHub Pages source: `main` branch, `/docs` folder.

- `docs/index.html` — presentation copy, responsive design, navigation, full-proposal printing and visual theme.
- `docs/assets/logo.svg` — an editable vector logo asset. The presentation also embeds the current logo setting in its client-side configuration.
- `docs/.nojekyll` — GitHub Pages compatibility marker.

## Navigation

The dark green "Build once. Publish with purpose." cover appears **only in the Overview tab**. Print Full Proposal / PDF prints the cover once, then each of the five presentation chapters.

## Edit and publish

Update `docs/index.html` via a local client-safe export, or edit the embedded JSON block marked `id="site-data"`. Commit changes to `main`; Pages redeploys automatically when configured.

**Never upload internal estimating, SKU catalogs, client approval notes, private working files, or tokens here.** Keep those on a local computer or in a separate private repository. This repository intentionally contains no internal calculator.
