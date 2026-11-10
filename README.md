# Pawprint

A QR code maker that installs to your home screen and works offline.

## Put it online (GitHub Pages)

1. On GitHub, create a new **public** repository called `pawprint`.
2. Choose **Add file → Upload files** and upload every file in this folder, so `index.html` sits at the top level of the repository. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. After a minute or two the app is live at `https://<your-username>.github.io/pawprint/`.

## Add it to your phone

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open the link in Chrome, tap ⋮, then **Install app** (or **Add to Home screen**).

Open it once while online. After that it works offline.

## Saving a code

On a phone, **Save PNG** and **Save SVG** open the share sheet. Choose **Save Image** to put the code in Photos, or **Save to Files**. On a computer, the buttons download the file.

## Updating later

If you change any file, also change `VERSION` in `sw.js` (for example to `pawprint-v2`) so phones pick up the new copy.
