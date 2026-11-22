# Tripboard

A deployable, local-first trip item application. Data is held in browser localStorage.

## Run

Run npm install, npm run dev, npm test, and npm run build. For a production check, run npm run preview after building.

## Deployment

Deploy the generated dist directory to any static host configured to return index.html for client-side hash routes. No server, account, or secret is required.

## Limitations

Local data can be removed with browser storage. Export JSON for a portable backup.
