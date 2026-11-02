# TFS Fire Danger overlay viewer

Web page that overlays the Tasmania Fire Service Fire Danger Rating maps on a basemap,
showing either today's live maps (fire.tas.gov.au) or past days from a private archive.

Open: https://mountainvagabond.github.io/tfs-fdr-viewer/

To view the archive, set **Source** to *Archive* and paste an access key (a read-only
GitHub token for the archive repository). The key is stored only in that browser.
This repository holds only the page — no maps and no keys.

## Search and pins

- **Search bar** (bottom): an address or place (OpenStreetMap, biased to Tasmania),
  latitude/longitude (`-42.88, 147.33`, `42.88S 147.33E`) or MGA zone 55 grid
  (`525000 5250000`, `55G 525000E 5250000N`). Coordinates drop a pin straight away.
- **📍** then tap the map to drop a pin; or **long-press** (phone) / **right-click** (computer).
- **Pins** show lat/long, MGA55, and the Fire Danger Rating under them for the day shown
  (ratings can be read in *Archive* mode; the live TFS image can't be read by the page).
  Pins are coloured by rating, can be dragged, renamed, copied or opened in Google Maps,
  and are remembered in that browser. The panel lists them (tap to zoom).
- **🎯** shows your location (and its rating).

Not for safety decisions — check TFS directly.
