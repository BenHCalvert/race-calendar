# Ben Calvert — Race Calendar

Personal athlete site covering race calendar, training plan, and athlete profile across the 2026–2027 seasons (XC MTB, trail running, skimo).

**Live site:** https://benhcalvert.github.io/race-calendar/

## Pages

| Page | Description |
|------|-------------|
| [Calendar](index.html) | 9-event race calendar from May 2026 through March 2027, with hand-coded SVG map (western US projection with detail inset) |
| [Training](training.html) | 12-month periodization arc, HR zone visualization, key session types, load balance status |
| [Profile](profile.html) | Performance benchmarks, season goals, home terrain |

## Tech

Static HTML/CSS — no build step, no frameworks, no JavaScript. Hosted on GitHub Pages.

- Single shared stylesheet (`style.css`) for design system tokens, nav, hero, and layout primitives
- Page-specific styles scoped per-file
- SVG map uses a manual linear lon/lat → pixel projection; label halos via `paint-order: stroke fill`
- Fully responsive down to 375px
