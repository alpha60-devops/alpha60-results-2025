---
layout: default
title: "ballard-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# ballard-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Ballard |
| Collection key | `ballard-01` |
| imdb_id | [tt26676904](https://www.imdb.com/title/tt26676904/) |
| wikipedia_url | [Ballard (TV series)](https://en.wikipedia.org/wiki/Ballard_(TV_series)) |
| Sample dates | 2025-07-10-to-2026-01-07 |
| Sample days | 182 |
| BTIH count | 448 |
| Unique BTIH count | 439 |
| Downloaders total | 55,535,522 |
| Uploaders total | 1,915,904 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-07-10-to-2026-01-07`
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

## 3. Media objects file size histogram

![Ballard collection size histogram](figures/ballard-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/ballard-01-downloads-by-week-ballard-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![ballard-01 downloads by day](figures/ballard-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.52 | 16.17 | 31.45 | 48.27 | 1.14 | 0.63 |

### Cumulative network infrastructure

[![Ballard cumulative map](figures/ballard-01-carto.png)](figures/ballard-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/ballard-01-data-ge-1080p.webp)](figures/ballard-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/ballard-01-data-lt-1080p.webp)](figures/ballard-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
