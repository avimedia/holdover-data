# holdover-data

Published FAA holdover time guideline datasets consumed by the
Cold Temperate Compensation app's in-app update check.

Served via GitHub Pages from `/docs`:
- `docs/manifest.json` — index of available datasets, their URLs and SHA-256 checksums.
- `docs/faa-2026-27.json` — FAA Winter 2026-2027 Holdover Time Guidelines, converted to JSON.

The app only installs a downloaded dataset after its checksum matches the
manifest entry and it passes full structural validation.
