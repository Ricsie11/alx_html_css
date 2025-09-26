# Smileschool — CSS Advanced Demo

This repository contains a small collection of HTML/CSS exercise pages. This README documents the `css_advanced` demo and explains how to preview and extend it.

## About

`css_advanced/index.html` is a static HTML demo for a fictional "Smileschool" landing page. It showcases a multi-section layout with a header/nav, hero area, instructor cards, testimonials, a tutorials grid, a membership CTA, FAQ and a footer.

Key points taken from the HTML:
- Uses Font Awesome kit: https://kit.fontawesome.com/4a2b055604.js (loaded in the `<head>`).
- Main demo file: `css_advanced/index.html`.

## Features

- Header with logo and navigation links.
- Hero / call-to-action section with prominent register button.
- Instructor showcase (cards with image, name and short note).
- Testimonials blockquote with author.
- Tutorials grid with thumbnails, author and rating stars (Font Awesome icons).
- Free membership features and CTA.
- Multi-column FAQ section.
- Footer with social icons.

## Project structure

Relevant files and folders (top-level):

- `css_advanced/`
  - `index.html` — main demo HTML file (this file was used to create this README).

Open `css_advanced/index.html` to inspect structure and class/element choices.

## How to preview locally

Option A — Open directly in your default browser (Windows PowerShell):

```powershell
Start-Process (Resolve-Path .\css_advanced\index.html)
```

Option B — Run a simple local HTTP server (recommended for loading some assets reliably):

```powershell
# start a quick server in the repo root
python -m http.server 8000
# then open http://localhost:8000/css_advanced/index.html in your browser
```

Option C — Use VS Code Live Server extension and open the `css_advanced/index.html` file.
