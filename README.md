# Tokyo Developers Map — Expanded v3

**What's new**
- Added **Mitsui Fudosan Nihonbashi** cluster (COREDO Muromachi 1–3, Nihonbashi Mitsui Tower, Muromachi Mitsui Tower, Takashimaya S.C. East).
- Added **other major developers** with representative projects:
  - **Sumitomo Realty & Development** — Shinjuku Sumitomo Building; Roppongi Grand Tower.
  - **Nomura Real Estate** — Shinjuku Nomura Building.
  - **Heiwa Real Estate** — KABUTO ONE (Nihonbashi Kabutocho).
  - **Tokyo Tatemono** — Tokyo Square Garden (Kyobashi).
  - **Mori Trust** — Kamiyacho Trust Tower (Tokyo World Gate).

## Deploy on GitHub Pages
1. Create a public repo and upload all files (keep `data/` folder).
2. Go to **Settings → Pages** and set **Branch: main**, **/(root)**, then **Save**.
3. Open: `https://<username>.github.io/<repo-name>/`

## Files
- `index.html` — Leaflet map loading `data/projects_v3.geojson`.
- `data/projects_v3.geojson` — all points (Lng/Lat + properties).
- `data/projects_v3.csv` — same data in CSV for editing.

> Coordinates are approximate for demo. You can refine positions & attributes and push again.