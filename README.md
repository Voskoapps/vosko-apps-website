# vosko-apps.com

De website van Vosko-apps, gehost op Vercel.

- `index.html` – de startpagina (overgenomen van de live site op 17 oktober 2026).
- `app-ads.txt` – voor Google AdMob; moet in de hoofdmap blijven staan.
- `fluffpop/privacy/` – het privacybeleid van Fluffpop: https://vosko-apps.com/fluffpop/privacy
- `moesracers/` – Moesracers: privacy, voorwaarden en account verwijderen (https://vosko-apps.com/moesracers/privacy, /terms, /delete). De bron staat in de Moesracers-repo onder `Web/moesracers`.

Publiceren: de Vercel-koppeling met GitHub werkt niet (Vercel-team Ryma, GitHub-account Voskoapps). Zet de site online vanuit deze map met `npx.cmd vercel@latest deploy --prod --yes --scope myryma` (de map is gekoppeld via `.vercel/`; `.vercelignore` houdt `.env*` en de README buiten de site).
