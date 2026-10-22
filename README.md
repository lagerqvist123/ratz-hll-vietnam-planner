# Ratz HLL Vietnam Planner

Tactical planner for Hell Let Loose: Vietnam. Draw on the map, place icons (garrison, outpost, tunnel, etc.), measure distances, and pick active strongpoints across all six maps (CAM, DAK, HUE, QUA, THA, VAN).

Unofficial fan tool, not affiliated with the makers of Hell Let Loose: Vietnam. Plans are saved locally in your browser.

## Contents

This is the built (static) version of the app:

- `index.html` – entry page
- `assets/` – built JS/CSS
- `icons/` – icons and `icons.json`
- `maps/<CODE>/` – map images (terrain/tactical) and `meta.json` with capture points and sectors

## Running locally

A web server is required, since ES modules do not load over `file://`:

```
python -m http.server 8000
```

Then open http://localhost:8000
