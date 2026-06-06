# Smart Money Moves - Personal Finance Blog

## Quick Start

```bash
# 1. Install Hugo Extended (if not installed)
# Download from: https://github.com/gohugoio/hugo/releases

# 2. Clone with theme
git clone --recurse-submodules https://github.com/adityatelange/hugo-PaperMod themes/PaperMod

# 3. Run local server
hugo server -D

# 4. Build for production
hugo --minify
```

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to Settings > Pages
3. Source: GitHub Actions
4. The included workflow (`.github/workflows/hugo-deploy.yml`) will auto-deploy on push to `main`

## Custom Domain Setup

1. Add `CNAME` file (already included) with your domain
2. In your domain registrar, point DNS to Cloudflare
3. In Cloudflare, add CNAME record: `@` → `yourusername.github.io`

## Content Structure

```
content/
├── pages/          # Static pages (about, contact, resources)
├── posts/          # Blog articles
└── _index.md       # Homepage content
```

## Brand Info

- **Blog Name:** Smart Money Moves
- **Domain:** ipotato.top
- **Author:** Alex
- **TikTok:** @smartmoneymoves
- **YouTube:** Smart Money Moves
