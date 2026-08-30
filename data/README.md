# Alpha60 results: 2025 release, revision 2

This directory is the corrected 2025 Alpha60 AAO results dataset. Revision 2
supersedes the 2026-08-07 release while preserving that release's exact
`README.md`, `SHA256SUMS`, and `release.json` bytes in the repository's
`release-history/2026-08-07/` directory.

## Revision 2 correction

`long-story-short-01` now uses its authoritative sample window,
`2025-08-22-to-2026-02-19` (182 calendar days), from canonical cache archive
`cache.20260219.tar.xz`. Its AAO products contain 26 weekly intervals. This
replaces the earlier 24-week, February 5 cutoff; all affected weekly,
cumulative, and companion-analysis products were regenerated together.
The associated day augmentation contains 181 paired products; day index 4 is
the sole authoritative gap.

## Layout

- `geojson.cumulative/`: one cumulative aggregate and one cumulative BTIHA
  gzip object for each of 83 media objects.
- `geojson.week/`: numbered weekly GeoJSON gzip objects.
- `json/`: four JSON index or summary products for each media object.
- `txt/year-2025-0-media-objects.txt`: canonical list of the 83 media-object
  identifiers.
- `SHA256SUMS`: sorted SHA-256 checksums for the AAO payload, including this
  README but excluding `SHA256SUMS` and `release.json` to avoid circular
  checksums.
- `release.json`: revision description, inventory, integrity record, and
  completion marker.

The cumulative aggregate files are standard GeoJSON `FeatureCollection`
objects and are the intended Leaflet-facing products. Files ending in
`.geojson.gz` are stored as deterministic gzip bytes. Browser clients that
explicitly use `DecompressionStream("gzip")` expect
`Content-Type: application/gzip` and no `Content-Encoding` response header.

## Sparse weekly intervals

Weekly numbering intentionally omits two intervals that are also absent from
their authoritative weekly JSON indexes:

- `andor-201`, week 8: 2025-06-11 through 2025-06-17
- `predator-killer-of-killers`, week 9: 2025-08-03 through 2025-08-09

No empty placeholder objects were manufactured for these intervals.
