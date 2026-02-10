# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static personal biography website hosted on GitHub Pages with custom domain (deok.ai). Single-page HTML application with embedded CSS, no build process required.

## Architecture

- **Single HTML file structure**: All content lives in `index.html` with inline CSS styling
- **No JavaScript framework**: Pure HTML/CSS implementation
- **Timeline-based layout**: Biographical content displayed chronologically using CSS-based timeline with alternating left/right positioning
- **Static assets**: Images (favicon.png, bio_main_image.png) and placeholder image references

## Development

Since this is a static site with no build process:
- Edit `index.html` directly for content or styling changes
- Preview changes by opening `index.html` in a browser
- Test responsiveness for mobile/desktop viewports

## Deployment

This site is deployed via GitHub Pages:
- Push changes to the `main` branch to deploy
- Custom domain configured via `CNAME` file (deok.ai)
- Site accessible at https://deok.ai

## Key Files

- `index.html`: Main page with all content and styling
- `CNAME`: Custom domain configuration
- `sitemap.xml`: SEO sitemap
- `robots.txt`: Search engine crawler directives
- `favicon.png`, `bio_main_image.png`: Site images
