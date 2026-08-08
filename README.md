# samimalik.me

Personal portfolio for Sami ur Rehman — software engineer, full-stack and applied AI.

Static site. No build step: `index.html` plus `assets/` are served directly by
Cloudflare Pages from the repository root.

## Structure

    index.html        the entire site (inline CSS + JS, no external requests)
    assets/           images, video loops, and CV
    _headers          Cloudflare Pages cache + security headers
    robots.txt        crawler directives
    sitemap.xml       single-page sitemap

## Deploying

Cloudflare Pages is connected to this repository and deploys `main` automatically
on push. Build command: none. Build output directory: `/`.
