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

## GitHub Actions deployment setup
This repository deploys via GitHub Actions workflow:
`/.github/workflows/deploy.yml`

One-time repository setting:
1. Go to repository `Settings`.
2. Open `Pages` in the left menu.
3. Under **Build and deployment**:
   - Source: `GitHub Actions`
4. Save (if prompted).

Deployment behavior:
- Every push to `main` triggers deployment.
- You can also deploy manually via `Actions` -> `Deploy static site to GitHub Pages` -> `Run workflow`.

Site URL:
`https://janjanssen-ship-it.github.io/Scrolly/`

Note: first publish can take 1-5 minutes after the workflow run completes.
