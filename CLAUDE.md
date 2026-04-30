# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static content project — a padel training drill reference sheet intended to be shared via GitHub Pages as a standalone HTML file.

## Files

- `Training Drills.md` — source content: warmup and drill tables with tags, details, and YouTube links
- `index.html` — the generated GitHub Pages site (single self-contained HTML file, no build step)

## Workflow

Edit content in `Training Drills.md`, then reflect changes manually in `index.html`. There is no build pipeline; the HTML file is maintained directly.

## GitHub Pages

The site is hosted via GitHub Pages from the `main` branch root. The entry point must be named `index.html`.

## Conventions

- Tags in the drill table use `#HashTag` format (e.g. `#Control`, `#Overheads`)
- YouTube links are embedded as anchor text using the channel/site name as label
- Keep warmup drills and main drills in separate sections
