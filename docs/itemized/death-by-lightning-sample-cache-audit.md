---
layout: default
title: "death-by-lightning Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# death-by-lightning sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Death by Lightning |
| Collection key | `death-by-lightning` |
| imdb_id | [tt31121364](https://www.imdb.com/title/tt31121364/) |
| wikipedia_url | [Death by Lightning](https://en.wikipedia.org/wiki/Death_by_Lightning) |
| Sample dates | 2025-11-07-to-2026-02-19 |
| Sample days | 105 |
| BTIH count | 175 |
| Unique BTIH count | 149 |
| Downloaders total | 19,091,382 |
| Uploaders total | 298,221 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-11-07-to-2026-02-19`
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

![Death by Lightning collection size histogram](figures/death-by-lightning-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/death-by-lightning-downloads-by-week-death-by-lightning-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![death-by-lightning downloads by day](figures/death-by-lightning-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.04 | 14.72 | 32.58 | 47.89 | 1.05 | 0.68 |

### Cumulative network infrastructure

[![Death by Lightning cumulative map](figures/death-by-lightning-carto.png)](figures/death-by-lightning-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/death-by-lightning-data-ge-1080p.webp)](figures/death-by-lightning-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/death-by-lightning-data-lt-1080p.webp)](figures/death-by-lightning-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
