---
layout: default
title: "wednesday-02.2 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# wednesday-02.2 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Wednesday |
| Collection key | `wednesday-02.2` |
| imdb_id | [tt13443470](https://www.imdb.com/title/tt13443470/) |
| wikipedia_url | [Wednesday (TV series)](https://en.wikipedia.org/wiki/Wednesday_(TV_series)) |
| Sample dates | 2025-09-03-to-2026-03-03 |
| Sample days | 182 |
| BTIH count | 359 |
| Unique BTIH count | 318 |
| Downloaders total | 57,670,556 |
| Uploaders total | 4,788,136 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-09-03-to-2026-03-03`
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

![Wednesday collection size histogram](figures/wednesday-02.2-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/wednesday-02-2-downloads-by-week-wednesday-02.2-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![wednesday-02.2 downloads by day](figures/wednesday-02-2-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.49 | 15.64 | 30.52 | 47.91 | 1.19 | 0.63 |

### Cumulative network infrastructure

[![Wednesday cumulative map](figures/wednesday-02.2-carto.png)](figures/wednesday-02.2-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/wednesday-02.2-data-ge-1080p.webp)](figures/wednesday-02.2-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/wednesday-02.2-data-lt-1080p.webp)](figures/wednesday-02.2-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
