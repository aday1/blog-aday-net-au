# blog.aday.net.au

Blog at blog.aday.net.au.

## Sources

- Live (Cloudflare): https://blog.aday.net.au
- Backup mirror (GitHub Pages): https://aday1.github.io/blog-aday-net-au/
- Source code: this repo

## Source of truth

Edit files under [public/](./public). Pushing to `main` deploys to:

- Cloudflare via [.github/workflows/deploy.yml](.github/workflows/deploy.yml) (requires `CLOUDFLARE_API_TOKEN` secret)
- GitHub Pages via [.github/workflows/pages-backup.yml](.github/workflows/pages-backup.yml) (no secret needed)

## Layout

- `public/index.html` - the page
- `wrangler.toml` - Cloudflare config
- `.github/workflows/` - deploy automation
