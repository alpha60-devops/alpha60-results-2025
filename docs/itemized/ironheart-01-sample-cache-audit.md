---
layout: default
title: "ironheart-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# ironheart-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Ironheart |
| Collection key | `ironheart-01` |
| imdb_id | [tt13623126](https://www.imdb.com/title/tt13623126/) |
| wikipedia_url | [Ironheart (miniseries)](https://en.wikipedia.org/wiki/Ironheart_(miniseries)) |
| Sample dates | 2025-06-25-to-2025-12-23 |
| Sample days | 182 |
| BTIH count | 612 |
| Unique BTIH count | 601 |
| Downloaders total | 82,908,802 |
| Uploaders total | 2,976,333 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-06-25-to-2025-12-23`
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

![Ironheart collection size histogram](figures/ironheart-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/ironheart-01-downloads-by-week-ironheart-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![ironheart-01 downloads by day](figures/ironheart-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.71 | 16.91 | 31.21 | 47.87 | 1.10 | 0.62 |

### Cumulative network infrastructure

[![Ironheart cumulative map](figures/ironheart-01-carto.png)](figures/ironheart-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/ironheart-01-data-ge-1080p.webp)](figures/ironheart-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/ironheart-01-data-lt-1080p.webp)](figures/ironheart-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
