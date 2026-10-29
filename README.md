# gs-vs-planning.github.io

Project page of the dichotomic visual-servoing planner in 3DGS maps: one HTML file on the Nerfies template (Bulma from a CDN), no build step.
Preview locally with `python3 -m http.server` in this folder, then open http://localhost:8000 (the 3D views fetch
their `.viser` recordings, which a `file://` page cannot do).
Images in `assets/img`, videos in `assets/video`, viser recordings in `assets/recordings`, viser's static client in
`viser/index.html` (viser 1.0.30). Recordings are made by
`gs_vs_dichotomic_planner/experiments/interiorgs/record_route_viser.py`.
