# kevingao25.github.io

Personal blog and portfolio — built with [Astro](https://astro.build/) and [Astro Theme Pure](https://github.com/cworld1/astro-theme-pure).

## Local Development

```bash
bun install
bun dev        # start dev server
bun run build  # production build
bun preview    # preview build
```

## Adding a New Post

Create a folder under `src/content/blog/` with an `index.md`:

```markdown
---
title: "Post Title"
description: "Brief description."
publishDate: "2026-03-14"
tags: ["tag1", "tag2"]
---

Content here.
```

Push to `main` and GitHub Actions will auto-deploy.
