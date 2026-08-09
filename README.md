# Surgeo Services — Static Website

A responsive multi-page static website for Surgeo Services.

## Pages
- Home
- About
- Services
- Projects
- Contact

## Deploy to GitHub Pages
1. Create a GitHub repository, e.g. `surgeo-website`.
2. Upload all files in this folder to the repository root.
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. The included `CNAME` file tells GitHub Pages to use `surgeo.in`.
6. In your domain registrar DNS settings, configure the domain for GitHub Pages. GitHub's current Pages documentation lists the exact A/AAAA and/or CNAME records to use.
7. In GitHub Pages, add `surgeo.in` under **Custom domain** and enable **Enforce HTTPS** after DNS has propagated.

## Before publishing
The address, phone number and second co-founder shown on the site are sample information requested for this mockup. Replace them before going live.

The photographs are loaded from Unsplash URLs so the repository stays lightweight. For a production site, download/licence the final images and serve them locally from an `assets` folder.
