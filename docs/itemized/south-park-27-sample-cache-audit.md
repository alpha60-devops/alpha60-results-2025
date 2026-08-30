---
layout: default
title: "south-park-27 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# south-park-27 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | South Park |
| Collection key | `south-park-27` |
| imdb_id | [tt0121955](https://www.imdb.com/title/tt0121955/) |
| wikipedia_url | [South Park](https://en.wikipedia.org/wiki/South_Park) |
| Sample dates | 2025-07-25-to-2026-01-22 |
| Sample days | 182 |
| BTIH count | 358 |
| Unique BTIH count | 309 |
| Downloaders total | 36,702,582 |
| Uploaders total | 4,433,579 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-07-25-to-2026-01-22`
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

![South Park collection size histogram](figures/south-park-27-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/south-park-27-downloads-by-week-south-park-27-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![south-park-27 downloads by day](figures/south-park-27-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.17 | 19.08 | 27.96 | 46.04 | 2.05 | 0.60 |

### Cumulative network infrastructure

[![South Park cumulative map](figures/south-park-27-carto.png)](figures/south-park-27-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/south-park-27-data-ge-1080p.webp)](figures/south-park-27-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/south-park-27-data-lt-1080p.webp)](figures/south-park-27-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
