# Minecraft PS5 Trophy Tracker

A static, no-build checklist for the Minecraft PS5 trophy list (137 trophies). Progress is saved in the visitor's browser (localStorage), with export/import to move it between devices.

## Put it on GitHub Pages
1. Create a new public repository on GitHub, for example `minecraft-trophies`.
2. Upload `index.html`, `data.js`, `.nojekyll` and this README (Add file > Upload files).
3. Repository Settings > Pages > Build and deployment: Source "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
4. After a minute the site is at `https://<your-username>.github.io/minecraft-trophies/`.

## Updating the trophy list
Everything is in `data.js`. Each row is `[name, type, short requirement, flag?]`, where type is P, G, S or B, and flag 1 means another player is needed. Tips live in `MC_TIPS`. Progress is keyed by pack and name, so renaming a trophy resets that one.

## Limits
- A static page can't read your PSN profile or control your PS5, so you tick trophies yourself.
- The list comes from a community tracker; Sony's own list is the authority.
