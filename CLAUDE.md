# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Description

A static landing page for the emery.guru domain. Plain HTML/CSS with no build step — just open `index.html` in a browser.

## Architecture

- `index.html` — single-page site with a jumbotron header and bio sections
- `styles.css` — all styling, including dark mode via `body.dark` class
- Dark mode toggle uses Font Awesome icons (sun/moon) loaded via CDN, with preference saved to `localStorage` and `prefers-color-scheme` respected on first visit

## Key Files

- `drew.md` — personal bio source file (gitignored). Used as reference content when updating the site or reusing the bio in other projects.
