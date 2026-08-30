---
layout: default
title: "dark-winds-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dark-winds-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dark Winds |
| Collection key | `dark-winds-301` |
| imdb_id | [tt15017118](https://www.imdb.com/title/tt15017118/) |
| wikipedia_url | [Dark Winds](https://en.wikipedia.org/wiki/Dark_Winds) |
| Sample dates | 2025-03-09-to-2025-06-21 |
| Sample days | 105 |
| BTIH count | 156 |
| Unique BTIH count | 155 |
| Downloaders total | 12,766,312 |
| Uploaders total | 514,478 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-03-09-to-2025-06-21`
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

## 3. Media objects file size histogram

![Dark Winds collection size histogram](figures/dark-winds-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dark-winds-301-downloads-by-week-dark-winds-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dark-winds-301 downloads by day](figures/dark-winds-301-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.01 | 15.37 | 27.74 | 52.02 | 1.08 | 0.59 |

### Cumulative network infrastructure

[![Dark Winds cumulative map](figures/dark-winds-301-carto.png)](figures/dark-winds-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/dark-winds-301-data-ge-1080p.webp)](figures/dark-winds-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/dark-winds-301-data-lt-1080p.webp)](figures/dark-winds-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
