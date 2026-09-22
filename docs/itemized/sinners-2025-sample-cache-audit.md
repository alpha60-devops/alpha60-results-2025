---
layout: default
title: "sinners-2025 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# sinners-2025 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Sinners |
| Collection key | `sinners-2025` |
| imdb_id | [tt31193180](https://www.imdb.com/title/tt31193180/) |
| wikipedia_url | [Sinners (2025 film)](https://en.wikipedia.org/wiki/Sinners_(2025_film)) |
| Sample dates | 2025-05-30-to-2025-11-28 |
| Sample days | 183 |
| BTIH count | 349 |
| Unique BTIH count | 322 |
| Downloaders total | 63,350,097 |
| Uploaders total | 5,730,663 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-05-30-to-2025-11-28`
- Sample days: 183
- Serialized week intervals: 27
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. File sizes histogram *median[lowest, highest]*

![Sinners collection size histogram](figures/sinners-2025-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/sinners-2025-downloads-by-week-sinners-2025-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![sinners-2025 downloads by day](figures/sinners-2025-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/sinners-2025-cumulative-aggregate.geojson.gz" data-map-title="Sinners — sinners-2025" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Sinners (sinners-2025) cumulative data map in new window" title="Opens interactive map for Sinners (sinners-2025) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.66 | 17.03 | 30.38 | 46.05 | 1.15 | 0.57 |

### Network infrastructure

[![Sinners cumulative map](figures/sinners-2025-carto.png)](figures/sinners-2025-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/sinners-2025-data-ge-1080p.webp)](figures/sinners-2025-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/sinners-2025-data-lt-1080p.webp)](figures/sinners-2025-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
