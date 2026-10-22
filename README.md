# Kiran Khanna: Developer Portfolio

The production build of my personal developer portfolio, published with GitHub Pages. It's based on the **DeveloperFolio** React template.

## What's included

- `index.html` and `static/`: the compiled React app (JS, CSS and media, including my resume PDF)
- `profile.json`: GitHub profile data shown on the site
- `blogs.json`: my Medium articles, shown in the blog section
- `manifest.json`, `browserconfig.xml`, `robots.txt`: PWA and SEO metadata

## Viewing the site

The site is served by GitHub Pages from this repository's default branch. To view it locally, serve the folder with any static file server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

> This repo holds only the built output. To change the content, edit the template's source project and rebuild it, then copy the `build/` output here.
