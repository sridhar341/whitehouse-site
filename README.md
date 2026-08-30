# White House Media — Website

Landing page for **White House Media**, a Bangalore media house for social media,
ads & branding. *Ideas. Content. Impact.*

**Live site:** https://whitehousemedia.in

## What's in this repo

| File          | Purpose                                              |
|---------------|------------------------------------------------------|
| `index.html`  | The entire website — HTML, CSS and JS in one file    |
| `og.png`      | Share-preview image (WhatsApp / Instagram / X cards) |
| `favicon.png` | Browser tab icon                                     |

No build step, no frameworks, no dependencies. Plain HTML/CSS/JS,
fonts loaded from Google Fonts.

## How it deploys

This repo is linked to **Netlify** (project: `eclectic-basbousa-ff2c74`).
Every commit to the `main` branch deploys automatically in ~30 seconds.

**To update the site:** edit or replace a file → commit to `main` → done.
No other steps.

**To roll back:** Netlify → Deploys → pick an earlier deploy → "Publish deploy".

## Domain & DNS

- Domain: `whitehousemedia.in`, registered at GoDaddy (expires Aug 26, 2027 — check auto-renew)
- DNS records that make the site work:
  - `A` record `@` → `75.2.60.5` (Netlify load balancer)
  - `CNAME` `www` → `eclectic-basbousa-ff2c74.netlify.app`
- HTTPS certificate is issued automatically by Netlify (Let's Encrypt)

## Contact

- hellowhitehousemedia@gmail.com · +91 73492 96896
- Instagram [@white.house_production](https://www.instagram.com/white.house_production)
  · X [@heyywhitehouse](https://x.com/heyywhitehouse)
