# virtualbuddy.in

Portfolio and blog of Banu Vinay, Fabric Data Engineer. Jekyll on GitHub Pages, no local build needed.

## Layout
- `index.html` – home page (uses `_layouts/default.html`; lists the latest 3 posts)
- `blog/index.html` – all posts
- `_posts/YYYY-MM-DD-slug.md` – one file per post; URL becomes `/blog/slug/`
- `assets/img/<slug>/` – screenshots for that post
- `assets/css/site.css` – all styles
- `_includes/` – head, header, footer, analytics snippet
- `CNAME` – custom domain (do not delete)

## Write a new post
1. Copy an existing file in `_posts/`, rename it `YYYY-MM-DD-your-slug.md`.
2. Edit the front matter (title, description, tags, video, repo).
3. Write in Markdown. Code in fenced blocks with a language: ```sql, ```python, ```powershell.
4. Put screenshots in `assets/img/your-slug/` and reference them as `/assets/img/your-slug/01-name.png`.
5. Commit. The site rebuilds in about a minute.
