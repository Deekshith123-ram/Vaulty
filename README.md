# Vaultly

A personal document vault in a single HTML file (`index.html`). No build step, no dependencies.

## Features
- Upload PDFs, images and other files (tap to pick, or drag and drop on desktop)
- Rename files before saving, plus rename, favorite, categorize, move, download and share afterwards
- Folders, categories, search and sorting
- Preview images and PDFs; basic image editing (rotate, crop, brightness, draw)
- Scan documents with the camera into a multi-page PDF
- Optional PIN lock (hides the screen only; it does **not** encrypt files)

## Storage and privacy
Files are stored locally in the browser's IndexedDB, separately for each web address. Nothing is uploaded and there is no cloud backup. Clearing site data deletes your documents.

## Run
Open `index.html` in a browser, or serve the folder over HTTPS. Live camera scanning needs HTTPS (or `localhost`).

## Deploy with GitHub Pages
1. Push these files to a GitHub repository.
2. Go to Settings > Pages, choose the `main` branch and the `/ (root)` folder, then Save.
3. Open the `https://<your-username>.github.io/<repo>/` link and allow Camera when asked.

The included `netlify.toml` is only used if you deploy on Netlify instead.
