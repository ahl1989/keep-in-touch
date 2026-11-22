# Keep in Touch

A small installable web app to remember who to reach out to, what to ask them, and when you last talked.

This repo holds only the app's code. Your friends' information is **not** here: it is saved in a separate private repo (`keep-in-touch-data`) that the app syncs with.

## Use it
Open https://ahl1989.github.io/keep-in-touch/ on your phone, then use the browser's "Add to Home Screen". In the app, open **Settings** and connect your data repo with a GitHub token (a fine-grained token with *Contents: read and write* on the data repo only).

## Updating
Edit the files here and commit. GitHub Pages republishes in a minute or two. If you change `index.html`, also bump `CACHE` in `sw.js` so phones pick up the new version.
