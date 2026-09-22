---
layout: default
title: "common-side-effects-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# common-side-effects-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Common Side Effects |
| Collection key | `common-side-effects-01` |
| imdb_id | [tt28093628](https://www.imdb.com/title/tt28093628/) |
| wikipedia_url | [Common Side Effects](https://en.wikipedia.org/wiki/Common_Side_Effects) |
| Sample dates | 2025-02-03-to-2025-05-19 |
| Sample days | 106 |
| BTIH count | 411 |
| Unique BTIH count | 397 |
| Downloaders total | 19,886,918 |
| Uploaders total | 1,602,702 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-02-03-to-2025-05-19`
- Sample days: 106
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

![Common Side Effects collection size histogram](figures/common-side-effects-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/common-side-effects-01-downloads-by-week-common-side-effects-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![common-side-effects-01 downloads by day](figures/common-side-effects-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/common-side-effects-01-cumulative-aggregate.geojson.gz" data-map-title="Common Side Effects — common-side-effects-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Common Side Effects (common-side-effects-01) cumulative data map in new window" title="Opens interactive map for Common Side Effects (common-side-effects-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.84 | 17.92 | 25.94 | 51.04 | 1.46 | 0.54 |

### Network infrastructure

[![Common Side Effects cumulative map](figures/common-side-effects-01-carto.png)](figures/common-side-effects-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/common-side-effects-01-data-ge-1080p.webp)](figures/common-side-effects-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/common-side-effects-01-data-lt-1080p.webp)](figures/common-side-effects-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
