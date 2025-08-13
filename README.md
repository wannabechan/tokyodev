# Tokyo Developers Projects Map (Layers & Metrics)

This folder contains a single-page Leaflet/Folium map: **index.html**.
You can host it anywhere that serves static files (GitHub Pages, Netlify, Vercel, or any web server).

## Quick Deploy Options

### 1) Netlify (no code, drag & drop)
- Go to https://app.netlify.com/drop
- Drag the entire folder to deploy.
- You'll get a public URL immediately.

### 2) GitHub Pages
- Create a new GitHub repository (public).
- Upload **index.html** to the repository root.
- In the repository settings, enable **Pages** → **Branch: main** → **/(root)**.
- Your site will be available at `https://<your-username>.github.io/<repo-name>/`.

### 3) Vercel (CLI or dashboard)
- Create a new project, import this folder, and deploy.
- Vercel will give you a public URL.

### 4) Any static web host / your own server
- Copy **index.html** to your web root (e.g., `/var/www/html/`), then visit your domain.

## Notes
- The map uses Leaflet tiles from standard CDNs; it requires an internet connection for basemap tiles.
- If you need a custom basemap or want to serve tiles locally, switch the tiles URL in the Folium code before exporting.

## File List
- `index.html` — The interactive map (company layers toggle + metrics in popups).