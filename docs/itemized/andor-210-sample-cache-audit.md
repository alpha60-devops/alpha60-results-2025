---
layout: default
title: "andor-210 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# andor-210 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Andor |
| Collection key | `andor-210` |
| imdb_id | [tt9253284](https://www.imdb.com/title/tt9253284/) |
| wikipedia_url | [Andor](https://en.wikipedia.org/wiki/Andor) |
| Sample dates | 2025-05-14-to-2025-11-12 |
| Sample days | 183 |
| BTIH count | 509 |
| Unique BTIH count | 493 |
| Downloaders total | 66,180,153 |
| Uploaders total | 4,227,954 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-05-14-to-2025-11-12`
- Sample days: 183
- Serialized week intervals: 27
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![Andor collection size histogram](figures/andor-210-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/andor-210-downloads-by-week-andor-210-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![andor-210 downloads by day](figures/andor-210-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.09 | 17.03 | 29.05 | 49.63 | 1.27 | 0.59 |

### Cumulative network infrastructure

[![Andor cumulative map](figures/andor-210-carto.png)](figures/andor-210-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/andor-210-data-ge-1080p.webp)](figures/andor-210-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/andor-210-data-lt-1080p.webp)](figures/andor-210-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
