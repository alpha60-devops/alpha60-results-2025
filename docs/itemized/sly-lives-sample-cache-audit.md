---
layout: default
title: "sly-lives Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# sly-lives sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Sly Lives |
| Collection key | `sly-lives` |
| imdb_id | [tt26424928](https://www.imdb.com/title/tt26424928/) |
| wikipedia_url | [Sly Lives! (aka The Burden of Black Genius)](https://en.wikipedia.org/wiki/Sly_Lives!_(aka_The_Burden_of_Black_Genius)) |
| Sample dates | 2025-02-14-to-2025-05-29 |
| Sample days | 105 |
| BTIH count | 21 |
| Unique BTIH count | 20 |
| Downloaders total | 1,065,964 |
| Uploaders total | 34,267 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-02-14-to-2025-05-29`
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

![Sly Lives collection size histogram](figures/sly-lives-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/sly-lives-downloads-by-week-sly-lives-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![sly-lives downloads by day](figures/sly-lives-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2025/refs/heads/main/data/geojson.cumulative/sly-lives-cumulative-aggregate.geojson.gz" data-map-title="Sly Lives — sly-lives" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Sly Lives (sly-lives) cumulative data map in new window" title="Opens interactive map for Sly Lives (sly-lives) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.73 | 12.31 | 22.39 | 43.18 | 0.78 | 0.46 |

### Network infrastructure

[![Sly Lives cumulative map](figures/sly-lives-carto.png)](figures/sly-lives-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/sly-lives-data-ge-1080p.webp)](figures/sly-lives-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/sly-lives-data-lt-1080p.webp)](figures/sly-lives-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
