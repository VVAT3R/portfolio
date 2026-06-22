# portfolio

Terminal-inspired personal portfolio. Pulls repos, skills, and experience live from GitHub.

## Pages

| Path | Description |
|------|-------------|
| `index.html` | Portfolio — projects, forks, skills, experience, contribution graph |
| `build/index.html` | System build — Lenovo Legion 5 15ACH6H specs and config |

## What it does

- Fetches all repos (own + forks) from the GitHub API dynamically
- Skills auto-populate from languages used across repos
- Experience section generates descriptions from repo metadata
- Dark/light theme toggle
- Typewriter effect, custom cursors, hover transforms
- Live contribution chart via ghchart.rshah.org
- Keyboard shortcuts: `P` (projects), `E` (experience)
- Logout modal (theatrical, not functional)
- Scroll-to-top button

## Run locally

```bash
npx serve .
```

## Deploy

Push to `main` — GitHub Pages handles the rest.
