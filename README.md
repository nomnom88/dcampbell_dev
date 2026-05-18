# dcampbell.dev

This is a Jekyll blog for GitHub Pages.

## Writing a Post

Create a Markdown file in `_posts/` using this filename format:

```text
YYYY-MM-DD-post-title.md
```

Each post starts with front matter:

```markdown
---
layout: post
title: "Post Title"
date: 2026-05-18 00:00:00 -0400
categories: blog
---

Write your post here.
```

## Local Preview

Install dependencies:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
