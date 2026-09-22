---
layout: default
title: "sean-combs-the-reckoning Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# sean-combs-the-reckoning sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Sean Combs: The Reckoning |
| Collection key | `sean-combs-the-reckoning` |
| imdb_id | [tt33473000](https://www.imdb.com/title/tt33473000/) |
| wikipedia_url | [Sean Combs: The Reckoning](https://en.wikipedia.org/wiki/Sean_Combs:_The_Reckoning) |
| Sample dates | 2025-12-02-to-2026-06-01 |
| Sample days | 182 |
| BTIH count | 136 |
| Unique BTIH count | 112 |
| Downloaders total | 20,854,594 |
| Uploaders total | 1,194,038 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-12-02-to-2026-06-01`
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

![Sean Combs: The Reckoning collection size histogram](figures/sean-combs-the-reckoning-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/sean-combs-the-reckoning-downloads-by-week-sean-combs-the-reckoning-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![sean-combs-the-reckoning downloads by day](figures/sean-combs-the-reckoning-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/sean-combs-the-reckoning-cumulative-aggregate.geojson.gz" data-map-title="Sean Combs: The Reckoning — sean-combs-the-reckoning" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Sean Combs: The Reckoning (sean-combs-the-reckoning) cumulative data map in new window" title="Opens interactive map for Sean Combs: The Reckoning (sean-combs-the-reckoning) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.43 | 14.94 | 31.61 | 45.62 | 1.22 | 0.69 |

### Network infrastructure

[![Sean Combs: The Reckoning cumulative map](figures/sean-combs-the-reckoning-carto.png)](figures/sean-combs-the-reckoning-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/sean-combs-the-reckoning-data-ge-1080p.webp)](figures/sean-combs-the-reckoning-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/sean-combs-the-reckoning-data-lt-1080p.webp)](figures/sean-combs-the-reckoning-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
