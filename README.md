# Hotel System

- `backend/`  Node server (Render, Web Service). Root Directory: `backend`. Build: `npm install`. Start: `node server.js`.
- `frontend/` Static pages (Cloudflare Pages). Root Directory: `frontend`. No build command, output directory `/`.
- `tools/`    Load test script (not deployed).

Put `icon-192.png` and `icon-512.png` in `frontend/` (referenced by manifest.json and the service worker).
Secrets live only in Render's Environment settings; see `backend/.env.example` for the names.
