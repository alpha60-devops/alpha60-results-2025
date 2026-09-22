---
layout: default
title: "hacks-408 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# hacks-408 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Hacks |
| Collection key | `hacks-408` |
| imdb_id | [tt11815682](https://www.imdb.com/title/tt11815682/) |
| wikipedia_url | [Hacks](https://en.wikipedia.org/wiki/Hacks) |
| Sample dates | 2025-05-16-to-2025-08-28 |
| Sample days | 105 |
| BTIH count | 202 |
| Unique BTIH count | 200 |
| Downloaders total | 13,170,002 |
| Uploaders total | 541,650 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-05-16-to-2025-08-28`
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

![Hacks collection size histogram](figures/hacks-408-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/hacks-408-downloads-by-week-hacks-408-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![hacks-408 downloads by day](figures/hacks-408-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/hacks-408-cumulative-aggregate.geojson.gz" data-map-title="Hacks — hacks-408" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Hacks (hacks-408) cumulative data map in new window" title="Opens interactive map for Hacks (hacks-408) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.83 | 15.74 | 29.67 | 50.41 | 1.14 | 0.61 |

### Network infrastructure

[![Hacks cumulative map](figures/hacks-408-carto.png)](figures/hacks-408-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/hacks-408-data-ge-1080p.webp)](figures/hacks-408-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/hacks-408-data-lt-1080p.webp)](figures/hacks-408-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
