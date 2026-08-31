# faithteo.com

Faith Teo's website — Be Your Own Hero. Built with [Astro](https://astro.build), deployed on Cloudflare Pages.

## Structure

- `src/pages/` — site pages (homepage, blog listing, blog post template)
- `src/content/blog/` — blog articles, one Markdown file per post
- `src/layouts/` — shared page layout

## Adding a new blog post

Add a new `.md` file to `src/content/blog/` with frontmatter:

```md
---
title: "Post title"
description: "One-sentence summary for SEO and previews"
publishDate: 2026-09-01
draft: false
---

Post content goes here.
```

## Local development

```
npm install
npm run dev
```

## Deployment

Connected to Cloudflare Pages — every push to `main` rebuilds and republishes the live site automatically.
