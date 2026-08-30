---
layout: default
title: "highest-2-lowest Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# highest-2-lowest sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Highest 2 Lowest |
| Collection key | `highest-2-lowest` |
| imdb_id | [tt31194612](https://www.imdb.com/title/tt31194612/) |
| wikipedia_url | [Highest 2 Lowest](https://en.wikipedia.org/wiki/Highest_2_Lowest) |
| Sample dates | 2025-09-05-to-2026-03-05 |
| Sample days | 182 |
| BTIH count | 110 |
| Unique BTIH count | 104 |
| Downloaders total | 18,532,509 |
| Uploaders total | 1,487,435 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-09-05-to-2026-03-05`
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

![Highest 2 Lowest collection size histogram](figures/highest-2-lowest-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/highest-2-lowest-downloads-by-week-highest-2-lowest-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![highest-2-lowest downloads by day](figures/highest-2-lowest-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.12 | 15.82 | 30.32 | 44.99 | 1.10 | 0.61 |

### Cumulative network infrastructure

[![Highest 2 Lowest cumulative map](figures/highest-2-lowest-carto.png)](figures/highest-2-lowest-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/highest-2-lowest-data-ge-1080p.webp)](figures/highest-2-lowest-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/highest-2-lowest-data-lt-1080p.webp)](figures/highest-2-lowest-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
