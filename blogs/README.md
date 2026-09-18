# Blog posts

Add new Markdown posts in this folder, then add an entry to `posts.json`.

Each `posts.json` item needs:

- `slug`: URL key used by `blog.html?post=your-slug`
- `title`: card and page title
- `date`: `YYYY-MM-DD`
- `excerpt`: homepage card summary
- `file`: Markdown file path, e.g. `blogs/your-post.md`

The homepage automatically renders cards from `blogs/posts.json`. The Read More link opens `blog.html`, which renders the selected Markdown file.
