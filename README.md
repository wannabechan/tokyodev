# Tokyo Developers Map — 4 Companies (Mori / Tokyu / Mitsui Fudosan / Mitsubishi Estate)

This repo contains a lightweight **Leaflet** map that loads project points from **GeoJSON**.
You can deploy it directly with **GitHub Pages**.

## Files
- `index.html` — main map (pure JS/Leaflet). It fetches data from `data/projects_4cos.geojson`.
- `data/projects_4cos.geojson` — project data (coordinates + properties).
- `data/projects_4cos.csv` — same data in CSV for editing.
- `folium_export.html` — optional Folium-rendered map (no external data file).

## One-click Deploy (GitHub Pages)
1. Create a new public repo and upload all files (keep the folder structure).
2. In the repo, go to **Settings → Pages**.
3. Select **Branch: main** and **/(root)**, then **Save**.
4. Your site will be available at: `https://<username>.github.io/<repo-name>/`

## Edit / Add Projects
- Update `data/projects_4cos.csv` and/or `data/projects_4cos.geojson`.
- If you edit only CSV, re-generate GeoJSON or ensure your map reads the CSV via JS.
- For quick changes, you can also manually edit `projects_4cos.geojson`:
  - Each feature is a Point with `coordinates: [Lng, Lat]`.
  - Properties include: `Company`, `회사`, `Project`, `프로젝트`, `Year`, `Type`, `GFA`, `Floors`, `Public Benefit`.

## Notes
- Basemap tiles use OpenStreetMap.
- Layer toggles at top-right let you show/hide each company.
- Popups show bilingual names + GFA, floors, and public-benefit notes.