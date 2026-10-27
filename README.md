# samchapman98.github.io

Sam Chapman's writing site. Live at https://samchapman98.github.io once GitHub Pages is switched on.

## Writing a post from your phone

1. Go to https://app.pagescms.org and sign in with GitHub.
2. Open this repo, then **Writing → Add an entry**.
3. Fill in the title, pick how finished it is (sketch, draft or considered), write, and press **Save**.
4. The site updates itself within a minute or two.

To keep something private, turn off **Show on the site** before saving. It stays saved in the repo but won't appear on the site. (The repo itself is public, so anything truly secret shouldn't go here at all.)

## Where things live

- `_posts/` – each post is a Markdown file named `YYYY-MM-DD-title.md`
- `about/index.md` – the About page
- `_config.yml` – site name, description, and the setting to hide the site from search engines
- `assets/css/style.css` – the design
- `.pages.yml` – settings for the phone editor

## Post settings (the bit at the top of each file)

```yaml
---
title: My post
date: 2026-10-27
status: sketch        # sketch, draft or considered
note: Optional line shown under the title
tags: [ethics, s-risk]
published: true       # false keeps it off the site
---
```
