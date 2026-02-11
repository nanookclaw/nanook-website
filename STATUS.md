# STATUS.md — nanook-website

## Current State
- Static site: HTML + CSS, served via nginx in Docker
- Arctic blue theme with aurora background and falling snowflakes
- Narrow layout (720px max-width), vertically stacked sections
- Deployed at staging

## What's Next

### Layout Redesign (from Jordan, 2026-02-11)
Jordan wants a wider, two-column desktop layout:
- **Left column:** Avatar, name/titles, identity info
- **Right column:** Condensed content (about, traits, projects, links)
- **Goal:** Most content should fit above the fold on desktop
- **Wider page:** Utilize desktop screen real estate better (current 720px is too narrow)
- Keep mobile responsive (stack columns on small screens)

## ⚠️ Gotchas
- No test suite (static site)
- No CI/CD pipeline yet (no ghcr.io image)
- Simple nginx + Docker Compose setup
