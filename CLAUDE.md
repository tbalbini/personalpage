# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Static personal portfolio website for Miguel Balbin, hosted on GitHub Pages at [miguelbalbin.com](https://miguelbalbin.com). No build tools, no dependencies — just plain HTML, CSS, and vanilla JS.

## Development

Open `index.html` directly in a browser, or use any static file server:

```bash
python3 -m http.server 8000
```

No build step, no compilation, no package manager.

## Architecture

Two-file layout:
- **[index.html](index.html)** — single-page site with all content and embedded SVG icons
- **[styles.css](styles.css)** — all styles; dark theme (`#1f1f1f` background, `#FF5C02` accent)

The page uses a two-column flex layout:
- **`.seccion1`** — sticky left sidebar with photo, bio, social links, and action buttons
- **`.seccion2`** — scrollable right column with experience/project cards

Each experience card references a company logo from `images/icons/` (PNG files named after the organization).

## SEO & Social

`index.html` includes Open Graph tags, Twitter cards, and a `schema.org` `Person` JSON-LD block. When updating the site's description or title, update all three locations to keep them in sync.
