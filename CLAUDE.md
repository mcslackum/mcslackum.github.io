# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal GitHub Pages site hosted at `mcslackum.github.io`. It is a static site with no build system, no framework, and no dependencies.

## Development

There are no build, test, or lint commands — files are served directly by GitHub Pages. To preview locally, use any static file server, for example:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in a browser.

## Deployment

Pushing to the `main` branch automatically deploys the site via GitHub Pages. There is no CI pipeline.

## Structure

Currently a single `index.html` at the repository root. GitHub Pages serves `index.html` as the homepage. Additional pages can be added as `.html` files or in subdirectories with their own `index.html`.
