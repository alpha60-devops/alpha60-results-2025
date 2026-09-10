---
layout: default
title: "andor-112 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# andor-112 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Andor |
| Collection key | `andor-112` |
| imdb_id | [tt9253284](https://www.imdb.com/title/tt9253284/) |
| wikipedia_url | [Andor](https://en.wikipedia.org/wiki/Andor) |
| Sample dates | 2025-04-23-to-2025-08-12 |
| Sample days | 112 |
| BTIH count | 242 |
| Unique BTIH count | 199 |
| Downloaders total | 23,395,559 |
| Uploaders total | 837,613 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-10T05:59:44Z
- Sample archive directory: `/mnt/gold/src/alpha60-samples-raw.gold/andor-112.xz/2025`
- Hour directories: 2668
- Zero-length sample files: 0
- Other unparsable sample files: 0
- Hourly discontinuities: 0 (0 missing hours)
- Missing days: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Andor collection size histogram](figures/andor-112-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/andor-112-downloads-by-week-andor-112-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![andor-112 downloads by day](figures/andor-112-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.01 | 14.95 | 28.66 | 52.08 | 1.04 | 0.61 |

### Cumulative network infrastructure

[![Andor cumulative map](figures/andor-112-carto.png)](figures/andor-112-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/andor-112-data-ge-1080p.webp)](figures/andor-112-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/andor-112-data-lt-1080p.webp)](figures/andor-112-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
