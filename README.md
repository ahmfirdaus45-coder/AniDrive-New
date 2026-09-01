# AniDrive — Vercel Ready

- `frontend/index.html` — frontend AniDrive terbaru
- `api/media.js` — proxy video Dropbox + HTTP Range
- `api/dropbox-api/[...path].js` — proxy Dropbox API JSON
- `api/dropbox-content/[...path].js` — proxy Dropbox binary/content
- `vercel.json` — konfigurasi Vercel

Deploy repository root ke Vercel. Jangan set Root Directory ke `frontend`, karena folder `api` harus berada di root.

Dropbox refresh token dan client secret tidak disimpan di source code.
