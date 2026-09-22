---
layout: default
title: "american-primeval Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# american-primeval sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | American Primeval |
| Collection key | `american-primeval` |
| imdb_id | [tt24069848](https://www.imdb.com/title/tt24069848/) |
| wikipedia_url | [American Primeval](https://en.wikipedia.org/wiki/American_Primeval) |
| Sample dates | 2025-01-10-to-2025-05-04 |
| Sample days | 115 |
| BTIH count | 290 |
| Unique BTIH count | 269 |
| Downloaders total | 31,775,512 |
| Uploaders total | 3,087,361 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-01-10-to-2025-05-04`
- Sample days: 115
- Serialized week intervals: 17
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. File sizes histogram *median[lowest, highest]*

![American Primeval collection size histogram](figures/american-primeval-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/american-primeval-downloads-by-week-american-primeval-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![american-primeval downloads by day](figures/american-primeval-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/american-primeval-cumulative-aggregate.geojson.gz" data-map-title="American Primeval — american-primeval" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open American Primeval (american-primeval) cumulative data map in new window" title="Opens interactive map for American Primeval (american-primeval) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.66 | 14.36 | 26.29 | 52.50 | 0.88 | 0.56 |

### Network infrastructure

[![American Primeval cumulative map](figures/american-primeval-carto.png)](figures/american-primeval-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/american-primeval-data-ge-1080p.webp)](figures/american-primeval-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/american-primeval-data-lt-1080p.webp)](figures/american-primeval-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
