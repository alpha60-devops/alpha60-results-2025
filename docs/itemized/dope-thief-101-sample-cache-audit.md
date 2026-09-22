---
layout: default
title: "dope-thief-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dope-thief-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dope Thief |
| Collection key | `dope-thief-101` |
| imdb_id | [tt21638826](https://www.imdb.com/title/tt21638826/) |
| wikipedia_url | [Dope Thief](https://en.wikipedia.org/wiki/Dope_Thief) |
| Sample dates | 2025-03-14-to-2025-06-26 |
| Sample days | 105 |
| BTIH count | 240 |
| Unique BTIH count | 226 |
| Downloaders total | 19,595,583 |
| Uploaders total | 892,095 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-03-14-to-2025-06-26`
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

![Dope Thief collection size histogram](figures/dope-thief-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dope-thief-101-downloads-by-week-dope-thief-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dope-thief-101 downloads by day](figures/dope-thief-101-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/dope-thief-101-cumulative-aggregate.geojson.gz" data-map-title="Dope Thief — dope-thief-101" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Dope Thief (dope-thief-101) cumulative data map in new window" title="Opens interactive map for Dope Thief (dope-thief-101) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.08 | 14.96 | 27.36 | 51.33 | 1.06 | 0.58 |

### Network infrastructure

[![Dope Thief cumulative map](figures/dope-thief-101-carto.png)](figures/dope-thief-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/dope-thief-101-data-ge-1080p.webp)](figures/dope-thief-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/dope-thief-101-data-lt-1080p.webp)](figures/dope-thief-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
