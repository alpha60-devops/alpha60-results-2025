---
layout: default
title: "frankenstein-2025 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# frankenstein-2025 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Frankenstein |
| Collection key | `frankenstein-2025` |
| imdb_id | [tt1312221](https://www.imdb.com/title/tt1312221/) |
| wikipedia_url | [Frankenstein (2025 film)](https://en.wikipedia.org/wiki/Frankenstein_(2025_film)) |
| Sample dates | 2025-11-08-to-2026-05-08 |
| Sample days | 182 |
| BTIH count | 273 |
| Unique BTIH count | 254 |
| Downloaders total | 65,806,200 |
| Uploaders total | 6,184,634 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-11-08-to-2026-05-08`
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

![Frankenstein collection size histogram](figures/frankenstein-2025-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/frankenstein-2025-downloads-by-week-frankenstein-2025-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![frankenstein-2025 downloads by day](figures/frankenstein-2025-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/frankenstein-2025-cumulative-aggregate.geojson.gz" data-map-title="Frankenstein — frankenstein-2025" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Frankenstein (frankenstein-2025) cumulative data map in new window" title="Opens interactive map for Frankenstein (frankenstein-2025) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.83 | 14.13 | 32.90 | 46.77 | 1.05 | 0.65 |

### Network infrastructure

[![Frankenstein cumulative map](figures/frankenstein-2025-carto.png)](figures/frankenstein-2025-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/frankenstein-2025-data-ge-1080p.webp)](figures/frankenstein-2025-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/frankenstein-2025-data-lt-1080p.webp)](figures/frankenstein-2025-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
