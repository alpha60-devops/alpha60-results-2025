---
layout: default
title: "moana-2 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# moana-2 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Moana 2 |
| Collection key | `moana-2` |
| imdb_id | [tt13622970](https://www.imdb.com/title/tt13622970/) |
| wikipedia_url | [Moana 2](https://en.wikipedia.org/wiki/Moana_2) |
| Sample dates | 2025-01-28-to-2025-07-28 |
| Sample days | 182 |
| BTIH count | 446 |
| Unique BTIH count | 401 |
| Downloaders total | 72,860,499 |
| Uploaders total | 7,714,949 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-01-28-to-2025-07-28`
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

![Moana 2 collection size histogram](figures/moana-2-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/moana-2-downloads-by-week-moana-2-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![moana-2 downloads by day](figures/moana-2-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.58 | 14.82 | 29.15 | 49.58 | 0.98 | 0.59 |

### Cumulative network infrastructure

[![Moana 2 cumulative map](figures/moana-2-carto.png)](figures/moana-2-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/moana-2-data-ge-1080p.webp)](figures/moana-2-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/moana-2-data-lt-1080p.webp)](figures/moana-2-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
