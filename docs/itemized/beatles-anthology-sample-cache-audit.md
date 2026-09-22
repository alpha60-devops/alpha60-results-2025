---
layout: default
title: "beatles-anthology Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# beatles-anthology sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Beatles: Anthology |
| Collection key | `beatles-anthology` |
| imdb_id | [tt0111893](https://www.imdb.com/title/tt0111893/) |
| wikipedia_url | [The Beatles Anthology (TV series)](https://en.wikipedia.org/wiki/The_Beatles_Anthology_(TV_series)) |
| Sample dates | 2025-11-26-to-2026-03-10 |
| Sample days | 105 |
| BTIH count | 123 |
| Unique BTIH count | 112 |
| Downloaders total | 11,704,363 |
| Uploaders total | 141,073 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-11-26-to-2026-03-10`
- Sample days: 105
- Serialized week intervals: 15
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. File sizes histogram *median[lowest, highest]*

![The Beatles: Anthology collection size histogram](figures/beatles-anthology-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/beatles-anthology-downloads-by-week-beatles-anthology-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![beatles-anthology downloads by day](figures/beatles-anthology-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/beatles-anthology-cumulative-aggregate.geojson.gz" data-map-title="The Beatles: Anthology — beatles-anthology" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Beatles: Anthology (beatles-anthology) cumulative data map in new window" title="Opens interactive map for The Beatles: Anthology (beatles-anthology) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.77 | 14.11 | 32.56 | 48.00 | 1.05 | 0.68 |

### Network infrastructure

[![The Beatles: Anthology cumulative map](figures/beatles-anthology-carto.png)](figures/beatles-anthology-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/beatles-anthology-data-ge-1080p.webp)](figures/beatles-anthology-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/beatles-anthology-data-lt-1080p.webp)](figures/beatles-anthology-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
