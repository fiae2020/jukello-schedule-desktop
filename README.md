# Jukello Schedule Desktop

Download page and release host for the Jukello Schedule Desktop trial installer — a Windows appointment-scheduling app for service businesses (booking, staff scheduling, waiting lists, one PC, no server).

- **Live page:** https://jukello.github.io/jukello-schedule-desktop/
- **Full product & pricing:** https://scheduler.jukello.com/
- **On-premise web version:** https://schedule-onpremise.jukello.com/

## Structure

- `index.html` — the download landing page (GitHub Pages serves this)
- `img/` — screenshot assets
- Trial installer (`jukello-schedule-trial-setup.msi`) is attached to [Releases](../../releases), not committed to the repo — GitHub Pages isn't meant for hosting large binaries, and Releases gives a stable `/releases/latest/download/<filename>` URL that never changes even as you publish new versions.

## Updating the trial build

1. Build the new `.msi`.
2. Go to **Releases → Draft a new release** (tag it, e.g. `v1.1`).
3. Attach the `.msi` as a release asset, named exactly `jukello-schedule-trial-setup.msi` so the download link on the page keeps working without edits.
4. Publish. The `/releases/latest/download/...` link on the page will automatically point at the new file.
