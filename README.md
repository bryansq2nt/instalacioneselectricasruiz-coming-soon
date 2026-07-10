# Instalaciones Electricas Ruiz Coming Soon

Static coming soon page for `instalacioneselectricasruiz.com`.

## Structure

- `public/` is the Cloudflare Pages deploy directory.
- `.github/workflows/deploy.yml` runs SEO/GEO audit, deploys to Cloudflare Pages, and verifies production.
- IndexNow is intentionally disabled for the coming soon phase. Enable it only when the placeholder should be submitted to search engines.

## Required GitHub Actions secrets

- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`
- `CLOUDFLARE_ZONE_ID`

## Production URL

https://instalacioneselectricasruiz.com/
