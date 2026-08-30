---
layout: default
title: "predator-badlands Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# predator-badlands sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Predator Badlands |
| Collection key | `predator-badlands` |
| imdb_id | [tt31227572](https://www.imdb.com/title/tt31227572/) |
| wikipedia_url | [Predator: Badlands](https://en.wikipedia.org/wiki/Predator:_Badlands) |
| Sample dates | 2025-12-11-to-2026-06-10 |
| Sample days | 182 |
| BTIH count | 282 |
| Unique BTIH count | 267 |
| Downloaders total | 60,669,977 |
| Uploaders total | 3,868,098 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-12-11-to-2026-06-10`
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

![Predator Badlands collection size histogram](figures/predator-badlands-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/predator-badlands-downloads-by-week-predator-badlands-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![predator-badlands downloads by day](figures/predator-badlands-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.81 | 14.59 | 33.91 | 45.41 | 1.12 | 0.67 |

### Cumulative network infrastructure

[![Predator Badlands cumulative map](figures/predator-badlands-carto.png)](figures/predator-badlands-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/predator-badlands-data-ge-1080p.webp)](figures/predator-badlands-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/predator-badlands-data-lt-1080p.webp)](figures/predator-badlands-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
