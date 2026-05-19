# Global Earthquake Tracker

Single-file Mapbox + GeoJSON app showing recent earthquakes.

Setup

1. Copy `.env.example` to `.env` and set your token:

   MAPBOX_ACCESS_TOKEN=pk.your_token_here

2. Edit `index.html` and replace `YOUR_MAPBOX_ACCESS_TOKEN` with your token, or use a build step to inject it.

Run locally

- With Python 3:

```bash
cd "d:/Desktop/Code Projects/Eathquake Map"
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Push to GitHub

Use the commands provided by the assistant (or the GitHub web UI). Recommended remote name: `origin` and branch `main`.

Security

- Do not commit your real Mapbox token. If you accidentally committed it, rotate it in your Mapbox account immediately.
