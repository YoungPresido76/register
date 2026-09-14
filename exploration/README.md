# Exploration

A small, dependency-free GitHub Pages prototype for a future 3D world-exploration experience. It lives inside the larger repository intentionally, so it can be reviewed and tested before it is moved into a product surface.

## Preview locally

From the repository root, serve the files with any static server:

```sh
python3 -m http.server 8080
```

Then open [http://localhost:8080/exploration/](http://localhost:8080/exploration/). The page loads its sample locations from `world-mockup.json`, so a web server (rather than opening the HTML file directly) is required.

## GitHub Pages test

Enable GitHub Pages for this repository and publish from the branch root. The prototype will be available at:

```
https://<owner>.github.io/<repository>/exploration/
```

The mockup is deliberately standalone: it uses no build step, packages, or external assets.

## Included

- `index.html` — the interactive visual mockup.
- `world-mockup.json` — sample exploration zones and points of interest that can later be replaced with real world/3D data.
