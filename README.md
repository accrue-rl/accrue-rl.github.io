# ACCRUE project website

Published at <https://accrue-rl.github.io/>.

Static HTML, CSS, JavaScript, and media; no build step is required. GitHub Pages publishes the `main` branch from `/ (root)`. `.nojekyll` disables Jekyll processing.

Edit `index.html`, `style.css`, `app.js`, or `content-overrides.json`, then push to `main` to deploy. The website omits author information; the paper PDF retains its original author list. The editor can export JSON on this static host; direct server-side saving is unavailable.

For a local preview:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000/>.
