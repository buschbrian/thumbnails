# thumbnails

Custom thumbnail images for the City of Millcreek, Utah ArcGIS Hub site and the
ArcGIS Online items it features.

Every image is a 600 × 400 PNG, the thumbnail size ArcGIS Online recommends.
This repo holds images only.

## Contents

| File | Item |
| --- | --- |
| `CIP-thumbnail-2024.png` | Capital Improvement Projects |
| `SWUF-thumbnail-2024.png` | Stormwater Utility Fee Projects |
| `swufstorymapthumb.png` | Stormwater Utility Fee Projects (earlier version) |
| `digitalequity-thumbnail-2025.png` | Digital Equity Story Map |
| `pavementpresexp-thumbnail-2024.png` | Pavement Preservation Experience |
| `planning-thumbnail-2024.png` | Planning and Zoning Experience |
| `planningmap-thumbnail-2026.png` | Planning Map |
| `producecollectionthumb-2025.png` | Produce Collection Web App |
| `propertylookup-thumbnail-2026.png` | Property Lookup |
| `resinfo-thumbnail-2024.png` | Millcreek Resident Information |
| `traffic-thumbnail-2025.png` | Traffic Conditions |

## Using a thumbnail

- **ArcGIS Online item:** download the PNG, then on the item page choose
  **Edit thumbnail** and upload it.
- **By URL** (for example, a Hub card or page image): use the raw file URL.

  ```text
  https://raw.githubusercontent.com/buschbrian/thumbnails/main/traffic-thumbnail-2025.png
  ```

Renaming or deleting a file breaks any link that points to it.

## Adding a thumbnail

- Export at 600 × 400 PNG.
- Most files are named `<item>-thumbnail-<year>.png`.
- Install the pre-commit hooks once per clone (`pre-commit install`). They check
  for secrets and reject files over 5 MB.
