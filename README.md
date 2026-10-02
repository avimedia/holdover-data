# holdover-data

Published FAA holdover time guideline datasets consumed by the
Cold Temperate Compensation app's in-app update check.

Served via GitHub Pages from `/docs`:
- `docs/manifest.json` — index of available datasets, their URLs and SHA-256 checksums.
- `docs/faa-2026-27.json` — FAA Winter 2026-2027 Holdover Time Guidelines, converted to JSON.

The app only installs a downloaded dataset after its checksum matches the
manifest entry and it passes full structural validation.

## Disclaimer

This repository is an unofficial, independently maintained conversion of
publicly published FAA Holdover Time Guidelines. It is not affiliated with,
endorsed by, or reviewed by the FAA. Datasets are machine-converted from the
FAA's own documents and may contain conversion errors or carry over
inconsistencies present in the source material itself (see each dataset's
`known-discrepancies` notes, where applicable).

Holdover times are safety-critical. Always verify values against the current
official FAA Holdover Time Guidelines before operational use. Do not rely on
this data as your sole source for deicing/anti-icing decisions. This data is
provided "as is", without warranty of any kind, and the maintainers accept no
liability for its accuracy or for decisions made based on it.
