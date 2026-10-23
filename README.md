# Sentinel – Cyber Threat Monitor

A single-page security operations center (SOC) dashboard built with plain HTML, CSS and JavaScript. All data is simulated in the browser.

## Features
- Live attack map (canvas) with animated arcs from source cities to three targets
- Live alert feed with severity filters, attack-type filter and search
- Alert detail panel with Block source and Mark resolved actions
- KPI counters, severity doughnut chart, top attack types and alerts-over-time chart
- SOC product shell with operational status bar, response queue and platform health
- Light/dark theme toggle and CSV export for the simulated alert stream
- Threat level indicator based on recent alert severity
- Pause/resume, clear alerts, keyboard support (Esc), responsive layout, reduced-motion support

## Tech
HTML, CSS, vanilla JavaScript, Canvas, SVG. No build step, no dependencies.

## Run
Open `index.html` in a browser.

## Next steps
- Connect to a real threat-intelligence feed through a backend API
- Persist alerts and analyst actions in a database
- Add user login and role-based access
