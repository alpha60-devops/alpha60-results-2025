---
layout: default
title: "wicked-2024 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# wicked-2024 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Wicked Part 1 |
| Collection key | `wicked-2024` |
| imdb_id | [tt1262426](https://www.imdb.com/title/tt1262426/) |
| wikipedia_url | [Wicked (2024 film)](https://en.wikipedia.org/wiki/Wicked_(2024_film)) |
| Sample dates | 2025-01-02-to-2025-07-02 |
| Sample days | 182 |
| BTIH count | 354 |
| Unique BTIH count | 299 |
| Downloaders total | 56,705,664 |
| Uploaders total | 5,039,775 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-01-02-to-2025-07-02`
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

![Wicked Part 1 collection size histogram](figures/wicked-2024-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/wicked-2024-downloads-by-week-wicked-2024-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![wicked-2024 downloads by day](figures/wicked-2024-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/wicked-2024-cumulative-aggregate.geojson.gz" data-map-title="Wicked Part 1 — wicked-2024" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Wicked Part 1 (wicked-2024) cumulative data map in new window" title="Opens interactive map for Wicked Part 1 (wicked-2024) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.40 | 15.88 | 27.82 | 49.85 | 1.15 | 0.55 |

### Network infrastructure

[![Wicked Part 1 cumulative map](figures/wicked-2024-carto.png)](figures/wicked-2024-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/wicked-2024-data-ge-1080p.webp)](figures/wicked-2024-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/wicked-2024-data-lt-1080p.webp)](figures/wicked-2024-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
