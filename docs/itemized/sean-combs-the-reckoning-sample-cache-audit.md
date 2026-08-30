---
layout: default
title: "sean-combs-the-reckoning Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# sean-combs-the-reckoning sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Sean Combs: The Reckoning |
| Collection key | `sean-combs-the-reckoning` |
| imdb_id | [tt33473000](https://www.imdb.com/title/tt33473000/) |
| wikipedia_url | [Sean Combs: The Reckoning](https://en.wikipedia.org/wiki/Sean_Combs:_The_Reckoning) |
| Sample dates | 2025-12-02-to-2026-06-01 |
| Sample days | 182 |
| BTIH count | 136 |
| Unique BTIH count | 112 |
| Downloaders total | 20,854,594 |
| Uploaders total | 1,194,038 |
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

![Sean Combs: The Reckoning collection size histogram](figures/sean-combs-the-reckoning-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/sean-combs-the-reckoning-downloads-by-week-sean-combs-the-reckoning-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![sean-combs-the-reckoning downloads by day](figures/sean-combs-the-reckoning-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.43 | 14.94 | 31.61 | 45.62 | 1.22 | 0.69 |

### Cumulative network infrastructure

[![Sean Combs: The Reckoning cumulative map](figures/sean-combs-the-reckoning-carto.png)](figures/sean-combs-the-reckoning-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/sean-combs-the-reckoning-data-ge-1080p.webp)](figures/sean-combs-the-reckoning-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/sean-combs-the-reckoning-data-lt-1080p.webp)](figures/sean-combs-the-reckoning-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
