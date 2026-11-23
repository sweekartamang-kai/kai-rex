# KAI REX — Industrial SCADA Simulation

A browser-based, multi-layer industrial monitoring and automation control panel. Pure HTML, CSS and JavaScript: no build step, no dependencies, no hardware.

**Live demo:** https://YOUR-USERNAME.github.io/kai-rex/

## Screens
1. Main Dashboard: live gauges, KPIs, plant health, alarms
2. Live Monitoring: three-phase scope, harmonic spectrum, kVA/kW/kVAR, trends
3. Machine Control: motors, pumps, conveyor, fan, compressor, AUTO/MANUAL, LOTO, scenario presets
4. Automation Logic: protection rules, lead/lag, auto level, PF correction, start-up sequence
5. Fault Management: overload, dry-run and phase-loss fault injection
6. Process Visualization: animated plant diagram with live tuning
7. Event & History: filterable log with CSV export
8. Reports & Analytics: statistics, charts, CSV and printable PDF report
9. Single-Line Diagram: live electrical one-line view
10. Alarm Center: priority alarms with acknowledge

## Highlights
- Interconnected simulation (electrical, motor, pump, tank, cooling, compressor)
- Protection: overcurrent, over-temperature, voltage and phase-loss trip, dry-run, overflow
- Role-based access (demo PINs: operator `1234`, engineer `5678`; demonstration only)
- Emergency stop, lockout/tagout, interlocks, adjustable thresholds and simulation speed

## Run locally
Open `index.html` in any modern browser.

## Deploy (GitHub Pages)
Settings → Pages → Deploy from a branch → `main` / root.

## Tech
HTML5, CSS3, vanilla JavaScript, Canvas and SVG.
