---
layout: default
title: "lazarus-108 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# lazarus-108 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Lazarus |
| Collection key | `lazarus-108` |
| imdb_id | [tt28454008](https://www.imdb.com/title/tt28454008/) |
| wikipedia_url | [Lazarus (Japanese TV series)](https://en.wikipedia.org/wiki/Lazarus_(Japanese_TV_series)) |
| Sample dates | 2025-05-25-to-2025-08-02 |
| Sample days | 70 |
| BTIH count | 103 |
| Unique BTIH count | 100 |
| Downloaders total | 4,133,117 |
| Uploaders total | 206,271 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-05-25-to-2025-08-02`
- Sample days: 70
- Serialized week intervals: 10
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![Lazarus collection size histogram](figures/lazarus-108-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/lazarus-108-downloads-by-week-lazarus-108-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![lazarus-108 downloads by day](figures/lazarus-108-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.92 | 16.04 | 29.24 | 48.66 | 1.02 | 0.65 |

### Cumulative network infrastructure

[![Lazarus cumulative map](figures/lazarus-108-carto.png)](figures/lazarus-108-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/lazarus-108-data-ge-1080p.webp)](figures/lazarus-108-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/lazarus-108-data-lt-1080p.webp)](figures/lazarus-108-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
