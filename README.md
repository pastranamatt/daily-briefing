# Daily Briefing

A personal daily-news site generated as a self-contained HTML newsletter and published with GitHub Pages.

## Structure

- `index.html` — latest briefing
- `archive.html` — archive index
- `archive/YYYY-MM-DD.html` — dated editions
- `.nojekyll` — serves the site as plain static HTML

## Publishing workflow

Each morning, the briefing is generated from fresh web searches, then the latest issue replaces `index.html`, a dated copy is added under `archive/`, and `archive.html` is updated with the new edition.

Live site: https://pastranamatt.github.io/daily-briefing/
