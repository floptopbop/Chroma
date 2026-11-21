# CHROMA

Palette tool: full-screen color bars, Harmony / Together / Stay linking, live gamut wheel, image picker with exact pixel circles.

Works offline after one online visit, and has its own home screen icon.

## Files (all three stay in the top level of the repo)
- `index.html` is the tool
- `chroma-sw.js` saves it for offline use (keep this exact name)
- `manifest.json` names the app and points to the icons (this is what your iPhone reads)
- `icon.svg` is the home screen icon, same setup as the ODM World site
- `chroma-icon.png`, `chroma-icon-192.png`, `chroma-icon-512.png` are backup copies of the icon the manifest also lists

## Publish
Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
Live at `https://floptopbop.github.io/<repo-name>/`
