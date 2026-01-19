
# JP Consulting – Jekyll + GitHub Actions Starter

This repository contains a **Jekyll** site deployed to **GitHub Pages** via **GitHub Actions**.

## How to use

1. Create a public repo named `janpeterhirt.github.io` (User Page).  
2. Upload all files from this folder to the repo root.  
3. In **Settings → Pages**: leave Source = **GitHub Actions** (auto when workflow exists).  
4. Commit & push – the site builds and deploys automatically.

### Custom domain (optional)
- Add a file named `CNAME` in repo root with your domain (e.g. `jpconsulting.sg`).  
- Set a DNS **CNAME**: `@` → `janpeterhirt.github.io` at your registrar.  
- Pages will issue HTTPS automatically.

## Structure
- `_config.yml` — site settings, theme, plugins, navigation  
- `Gemfile` — Jekyll & plugin versions  
- `_layouts/`, `_includes/` — templates  
- `index.md`, `services/`, `projects/`, `contact/` — content pages  
- `.github/workflows/pages.yml` — build & deploy pipeline

## Notes
- Uses GitHub‑supported theme **pages-themes/minimal** via `jekyll-remote-theme`.  
- Actions workflow uses `upload-pages-artifact` + `deploy-pages` to publish.  
- You can add posts (`_posts/YYYY-MM-DD-title.md`) if you want a blog later.

