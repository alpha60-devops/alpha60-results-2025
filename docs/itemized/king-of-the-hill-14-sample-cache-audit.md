---
layout: default
title: "king-of-the-hill-14 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# king-of-the-hill-14 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | King of the Hill |
| Collection key | `king-of-the-hill-14` |
| imdb_id | [tt0118375](https://www.imdb.com/title/tt0118375/) |
| wikipedia_url | [King of the Hill](https://en.wikipedia.org/wiki/King_of_the_Hill) |
| Sample dates | 2025-08-04-to-2025-11-16 |
| Sample days | 105 |
| BTIH count | 226 |
| Unique BTIH count | 226 |
| Downloaders total | 15,207,885 |
| Uploaders total | 1,031,063 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-08-04-to-2025-11-16`
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

![King of the Hill collection size histogram](figures/king-of-the-hill-14-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/king-of-the-hill-14-downloads-by-week-king-of-the-hill-14-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![king-of-the-hill-14 downloads by day](figures/king-of-the-hill-14-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/king-of-the-hill-14-cumulative-aggregate.geojson.gz" data-map-title="King of the Hill — king-of-the-hill-14" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open King of the Hill (king-of-the-hill-14) cumulative data map in new window" title="Opens interactive map for King of the Hill (king-of-the-hill-14) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.81 | 21.04 | 28.42 | 45.83 | 1.31 | 0.53 |

### Network infrastructure

[![King of the Hill cumulative map](figures/king-of-the-hill-14-carto.png)](figures/king-of-the-hill-14-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/king-of-the-hill-14-data-ge-1080p.webp)](figures/king-of-the-hill-14-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/king-of-the-hill-14-data-lt-1080p.webp)](figures/king-of-the-hill-14-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
