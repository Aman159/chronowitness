# ChronoWitness V2

Source-led history + geography + astronomy-context prototype.

## What's new
- Redesigned cinematic responsive UI
- Live interactive Leaflet map
- Curated moment search and era filters
- Evidence cards and institutional source links
- Timeline navigation
- Sky-context panel linking to Stellarium Web
- Explicit separation between modern geography and historical claims

## Deploy
Replace the current repository `index.html` with this V2 `index.html`, then commit to `main`. Your connected Vercel project should create a new deployment from the Git push.

## Important map note
The prototype uses the standard OpenStreetMap tile server with visible attribution. OSM states its tile service is best-effort and capacity is limited. Do not use it for heavy traffic or bulk tile downloading. Before scaling, move to a suitable OSM-derived provider or infrastructure that matches your traffic.

## Accuracy design
- Exact dates only for documented events.
- Period labels for ancient sites where an exact day is not established.
- The interactive map is explicitly modern geographic context.
- The prototype does not fabricate astronomical positions. The Sky Context view links to Stellarium Web until a native astronomical layer is independently verified.
