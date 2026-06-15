# omercanyy.github.io — Onboarding

## What Is This?

Static single-page portfolio site for showcasing developer productivity tools. Hosted via GitHub Pages.

## Context Map

- Site entry point → `index.html`
- All styling → `style.css` (design tokens at top, components below)
- Interactions (nav, scroll, reveal) → `script.js`

## Tech Stack

- Pure HTML/CSS/JS — no framework, no build step
- Fonts: Inter + JetBrains Mono via Google Fonts CDN
- Hosting: GitHub Pages (main branch)

## Development Lifecycle

1. Branch from main
2. Implement changes
3. Commit → PR → CI → Squash Merge → Sync main

## Gotchas

- No `npm` or build step — just open `index.html` in a browser or use a static server.
- The `.css` design tokens in `:root` are the single source of truth for colors, spacing, and typography.
- The copyright year in the footer is hardcoded — update manually.
