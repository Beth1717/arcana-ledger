ARCANA LEDGER v0.2 — Cloudflare Pages direct upload

1. Extract the zip (index.html must be at the website root).
2. Open Cloudflare Dashboard > Workers & Pages > Create > Pages > Direct Upload.
3. Upload the folder arcana-ledger-pwa (or drag the extracted files) and deploy.
4. Visit the assigned https://YOURPROJECT.pages.dev URL.
5. On Android Chrome, choose menu > Install app / Add to Home screen.
6. Test adding a character, closing/reopening, airplane mode, and JSON export before relying on it.

All player and character records are stored in the browser's localStorage on that device.
The app does NOT synchronize characters between different players/devices.
Export/import JSON to transfer or back up data. It includes uploaded portraits.
The spell reference list is deliberately empty until your book photos are
transcribed and edition-specific rules verified. Daily slot totals are editable.
No server backend, accounts, account sync, or AI extraction is included.
Use the same Cloudflare Pages project for future updated deployments.
