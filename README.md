# Price Tracker (Starter)

A ready-to-deploy Vite + React app with a working `/api/search` (mock adapter).
Deploy on **Vercel** (default) or **Netlify**.

## Run locally
npm install
npm run dev
# open http://localhost:5173
# Try the API:
curl http://localhost:5173/api/health
curl "http://localhost:5173/api/search?q=diapers"

## Deploy (Vercel)
- vercel.com → New Project → Import from GitHub
- Build: npm run build
- Output: dist

## Deploy (Netlify)
- Build: npm run build
- Publish: dist
- Functions: netlify/functions
