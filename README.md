# Nissan X-Trail OBD data explorer

A static, mobile-friendly viewer for the recorded Nissan X-Trail OBD data.

- `index.html` is the new single-window explorer for the complete OBD log, with a scrolling signal menu and keyboard stepping.
- Event 3 (good) and Event 13 (bad) are compared by default; run selections persist across signals and can be reset to all or none.
- `EventsGraphs.html` is the original acceleration-event view and remains unchanged.
- `NissanXtrailOBDLog.html` is the original complete-log view and remains unchanged.

The site has no backend or build step. The existing GitHub Actions workflow publishes the repository directly to GitHub Pages whenever `main` is updated.

To preview it locally, serve this directory with any static web server and open `index.html`.
