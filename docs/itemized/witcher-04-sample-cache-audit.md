---
layout: default
title: "witcher-04 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# witcher-04 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Witcher |
| Collection key | `witcher-04` |
| imdb_id | [tt5180504](https://www.imdb.com/title/tt5180504/) |
| wikipedia_url | [The Witcher (TV series)](https://en.wikipedia.org/wiki/The_Witcher_(TV_series)) |
| Sample dates | 2025-10-30-to-2026-04-29 |
| Sample days | 182 |
| BTIH count | 439 |
| Unique BTIH count | 385 |
| Downloaders total | 61,178,147 |
| Uploaders total | 3,202,719 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-10-30-to-2026-04-29`
- Sample days: 182
- Serialized week intervals: 26
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. File sizes histogram *median[lowest, highest]*

![Witcher collection size histogram](figures/witcher-04-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/witcher-04-downloads-by-week-witcher-04-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![witcher-04 downloads by day](figures/witcher-04-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/witcher-04-cumulative-aggregate.geojson.gz" data-map-title="Witcher — witcher-04" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Witcher (witcher-04) cumulative data map in new window" title="Opens interactive map for Witcher (witcher-04) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.55 | 14.96 | 32.70 | 47.86 | 1.19 | 0.68 |

### Network infrastructure

[![Witcher cumulative map](figures/witcher-04-carto.png)](figures/witcher-04-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/witcher-04-data-ge-1080p.webp)](figures/witcher-04-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/witcher-04-data-lt-1080p.webp)](figures/witcher-04-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
