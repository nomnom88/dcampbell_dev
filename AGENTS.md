# AGENTS.md

This repository contains a personal blog built with Jekyll and published through GitHub Pages.

## Project Context

- Treat this as a static Jekyll site intended for GitHub Pages compatibility.
- Prefer standard Jekyll conventions for layouts, includes, posts, pages, collections, and front matter.
- Keep content and implementation simple, maintainable, and friendly to GitHub Pages' supported Jekyll environment.
- Avoid adding custom build steps, unsupported plugins, or heavy dependencies unless explicitly requested.

## Editing Guidance

- Blog posts should use Markdown with valid YAML front matter.
- Preserve existing permalink, layout, category, tag, and date conventions when adding or editing content.
- Keep Liquid templates readable and avoid unnecessary abstraction.
- Use relative links or Jekyll helpers where appropriate so the site works correctly on GitHub Pages.
- Do not rewrite generated output or local build artifacts unless the repository intentionally tracks them.

## Validation

- For theme, layout, or configuration changes, prefer a local Jekyll build or serve check when practical.
- Keep verification lightweight for content-only edits.
