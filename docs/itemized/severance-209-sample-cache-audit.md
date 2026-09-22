---
layout: default
title: "severance-209 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# severance-209 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Severance |
| Collection key | `severance-209` |
| imdb_id | [tt11280740](https://www.imdb.com/title/tt11280740/) |
| wikipedia_url | [Severance (TV series)](https://en.wikipedia.org/wiki/Severance_(TV_series)) |
| Sample dates | 2025-03-14-to-2025-07-02 |
| Sample days | 111 |
| BTIH count | 301 |
| Unique BTIH count | 275 |
| Downloaders total | 27,580,339 |
| Uploaders total | 3,292,539 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-03-14-to-2025-07-02`
- Sample days: 111
- Serialized week intervals: 16
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. File sizes histogram *median[lowest, highest]*

![Severance collection size histogram](figures/severance-209-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/severance-209-downloads-by-week-severance-209-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![severance-209 downloads by day](figures/severance-209-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/severance-209-cumulative-aggregate.geojson.gz" data-map-title="Severance — severance-209" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Severance (severance-209) cumulative data map in new window" title="Opens interactive map for Severance (severance-209) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.43 | 17.57 | 25.89 | 50.90 | 1.52 | 0.55 |

### Network infrastructure

[![Severance cumulative map](figures/severance-209-carto.png)](figures/severance-209-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/severance-209-data-ge-1080p.webp)](figures/severance-209-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/severance-209-data-lt-1080p.webp)](figures/severance-209-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
