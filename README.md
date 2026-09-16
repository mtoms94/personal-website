# Mai Toms — Personal Website

Simple personal site built with [Astro](https://astro.build) 7, deployed on Netlify.

**Requires Node 22.12.0+** (see `.nvmrc`).

## Local development

```bash
nvm use          # or ensure Node >= 22.12.0
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321).

## Editing content

### Intro (home page)

Edit `src/content/intro/intro.md` — markdown with frontmatter, README-style.

### Blog posts

Add markdown files to `src/content/blog/`:

```yaml
---
title: Post title
description: Short summary shown on the blog listing
pubDate: 2026-08-17
---
```

Set `draft: true` to hide a post without deleting it.

### Resume

Place your PDF at `public/MaireadTomsResume.pdf`. It is served at `/MaireadTomsResume.pdf` and linked from the nav.

## Deploy

Push to your connected Git repo — Netlify builds and deploys automatically.

Build command: `npm run build`  
Publish directory: `dist`
