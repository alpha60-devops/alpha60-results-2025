---
layout: default
title: "duster-106 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# duster-106 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Duster |
| Collection key | `duster-106` |
| imdb_id | [tt12160826](https://www.imdb.com/title/tt12160826/) |
| wikipedia_url | [Duster (TV series)](https://en.wikipedia.org/wiki/Duster_(TV_series)) |
| Sample dates | 2025-06-21-to-2025-10-04 |
| Sample days | 106 |
| BTIH count | 273 |
| Unique BTIH count | 263 |
| Downloaders total | 18,062,082 |
| Uploaders total | 396,077 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-06-21-to-2025-10-04`
- Sample days: 106
- Serialized week intervals: 16
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![Duster collection size histogram](figures/duster-106-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/duster-106-downloads-by-week-duster-106-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![duster-106 downloads by day](figures/duster-106-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.97 | 16.00 | 30.48 | 49.44 | 1.13 | 0.61 |

### Cumulative network infrastructure

[![Duster cumulative map](figures/duster-106-carto.png)](figures/duster-106-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/duster-106-data-ge-1080p.webp)](figures/duster-106-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/duster-106-data-lt-1080p.webp)](figures/duster-106-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
