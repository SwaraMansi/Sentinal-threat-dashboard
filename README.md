# Sentinel – Cyber Threat Monitor

A single-page security operations center (SOC) dashboard built with plain HTML, CSS and JavaScript. All data is simulated in the browser.

## Live demo

Open the deployed dashboard here:

**https://swaramansi.github.io/Sentinal-threat-daahboard/**

The site is hosted with GitHub Pages from the `main` branch.

## Features
- Live attack map (canvas) with animated arcs from source cities to three targets
- Live alert feed with severity filters, attack-type filter and search
- Alert detail panel with Block source and Mark resolved actions
- KPI counters, severity doughnut chart, top attack types and alerts-over-time chart
- SOC product shell with operational status bar, response queue and platform health
- Light/dark theme toggle and CSV export for the simulated alert stream
- Analyst workspace navigation, focus mode, keyboard search shortcut and response queue actions
- Threat level indicator based on recent alert severity
- Pause/resume, clear alerts, keyboard support (Esc), responsive layout, reduced-motion support

## Tech
HTML, CSS, vanilla JavaScript, Canvas, SVG. No build step, no dependencies.

## Run locally

No installation or build step is required. Open `index.html` directly in a browser, or serve the folder with any static web server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Next steps
- Connect to a real threat-intelligence feed through a backend API
- Persist alerts and analyst actions in a database
- Add user login and role-based access
