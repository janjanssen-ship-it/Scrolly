# Scrolly: Minnesota Anti-ICE Protest Story

This repository is ready for GitHub Pages deployment as a static site.

## Project structure
- `index.html`: GitHub Pages entrypoint (fullscreen scrollytelling)
- `article-minnesota-ice.html`: same story as standalone article page
- `assets/`: local image files used by the scrollytelling section

## Local preview
Open `index.html` in a browser, or run a local static server.

Example:
```bash
python3 -m http.server 8080
```
Then open `http://localhost:8080`.

## GitHub Pages setup
1. Go to repository `Settings`.
2. Open `Pages` in the left menu.
3. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Click `Save`.

After deployment, your site URL should be:
`https://janjanssen-ship-it.github.io/Scrolly/`

Note: first publish can take 1-5 minutes.
