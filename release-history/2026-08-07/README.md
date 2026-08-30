# Alpha60 results: 2025 release

This directory is the 2025 Alpha60 results dataset. Object paths beneath this
directory are preserved beneath the S3 prefix `alpha60-results/2025/`.

## Layout

- `geojson.cumulative/`: one cumulative aggregate and one cumulative BTIHA gzip
  object for each of 83 media objects.
- `geojson.week/`: numbered weekly GeoJSON gzip objects.
- `json/`: four JSON index or summary products for each media object.
- `txt/year-2025-0-media-objects.txt`: canonical list of the 83 media-object
  identifiers.
- `SHA256SUMS`: sorted SHA-256 checksums for the payload, including this README
  but excluding `SHA256SUMS` and `release.json` to avoid circular checksums.
- `release.json`: release description and remote completion marker. It is
  uploaded only after the other objects pass remote verification.

The cumulative aggregate files are standard GeoJSON `FeatureCollection`
objects and are the intended Leaflet-facing products. Files ending in
`.geojson.gz` are stored as gzip bytes. Browser clients that explicitly use
`DecompressionStream("gzip")` expect `Content-Type: application/gzip` and no
`Content-Encoding` response header.

## Sparse weekly intervals

Weekly numbering intentionally omits two intervals that are also absent from
their authoritative weekly JSON indexes:

- `andor-201`, week 8: 2025-06-11 through 2025-06-17
- `predator-killer-of-killers`, week 9: 2025-08-03 through 2025-08-09

No empty placeholder objects were manufactured for these intervals.

