---
layout: default
title: "white-lotus-307 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# white-lotus-307 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | White Lotus |
| Collection key | `white-lotus-307` |
| imdb_id | [tt13406094](https://www.imdb.com/title/tt13406094/) |
| wikipedia_url | [The White Lotus](https://en.wikipedia.org/wiki/The_White_Lotus) |
| Sample dates | 2025-03-31-to-2025-10-05 |
| Sample days | 189 |
| BTIH count | 259 |
| Unique BTIH count | 245 |
| Downloaders total | 35,783,863 |
| Uploaders total | 2,256,747 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-03-31-to-2025-10-05`
- Sample days: 189
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

![White Lotus collection size histogram](figures/white-lotus-307-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/white-lotus-307-downloads-by-week-white-lotus-307-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![white-lotus-307 downloads by day](figures/white-lotus-307-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/white-lotus-307-cumulative-aggregate.geojson.gz" data-map-title="White Lotus — white-lotus-307" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open White Lotus (white-lotus-307) cumulative data map in new window" title="Opens interactive map for White Lotus (white-lotus-307) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.07 | 16.17 | 28.05 | 50.34 | 1.40 | 0.60 |

### Network infrastructure

[![White Lotus cumulative map](figures/white-lotus-307-carto.png)](figures/white-lotus-307-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/white-lotus-307-data-ge-1080p.webp)](figures/white-lotus-307-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/white-lotus-307-data-lt-1080p.webp)](figures/white-lotus-307-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
