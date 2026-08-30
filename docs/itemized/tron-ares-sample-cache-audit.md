---
layout: default
title: "tron-ares Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# tron-ares sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Tron Ares |
| Collection key | `tron-ares` |
| imdb_id | [tt6604188](https://www.imdb.com/title/tt6604188/) |
| wikipedia_url | [Tron: Ares](https://en.wikipedia.org/wiki/Tron:_Ares) |
| Sample dates | 2025-12-02-to-2026-06-01 |
| Sample days | 182 |
| BTIH count | 318 |
| Unique BTIH count | 296 |
| Downloaders total | 62,306,843 |
| Uploaders total | 2,655,366 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

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

## 3. Media objects file size histogram

![Tron Ares collection size histogram](figures/tron-ares-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/tron-ares-downloads-by-week-tron-ares-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![tron-ares downloads by day](figures/tron-ares-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.26 | 14.28 | 34.46 | 46.95 | 1.03 | 0.70 |

### Cumulative network infrastructure

[![Tron Ares cumulative map](figures/tron-ares-carto.png)](figures/tron-ares-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/tron-ares-data-ge-1080p.webp)](figures/tron-ares-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/tron-ares-data-lt-1080p.webp)](figures/tron-ares-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
