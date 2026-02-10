# Markdown Viewer

A single-page web app to view and print markdown files as beautifully formatted documents.

## Features

- **Drag & drop** or browse to upload `.md` files (multiple at once)
- **Beautiful rendering** with proper typography, tables, code blocks, blockquotes
- **Dark / Light mode** toggle with persistence
- **Print / Save as PDF** button — print CSS hides controls, outputs clean content
- **File separators** with page breaks per file in print
- **No server needed** — just open `index.html` in a browser
- **Sanitized output** via DOMPurify

## Usage

1. Open `index.html` in any modern browser
2. Drop markdown files onto the page (or click to browse)
3. Click **Print / Save PDF** to export

## Dependencies (CDN)

- [marked.js](https://github.com/markedjs/marked) — Markdown parsing
- [DOMPurify](https://github.com/cure53/DOMPurify) — HTML sanitization
