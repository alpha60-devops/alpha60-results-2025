---
layout: default
title: "pluribus-107 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# pluribus-107 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Pluribus |
| Collection key | `pluribus-107` |
| imdb_id | [tt22202452](https://www.imdb.com/title/tt22202452/) |
| wikipedia_url | [Pluribus (TV series)](https://en.wikipedia.org/wiki/Pluribus_(TV_series)) |
| Sample dates | 2025-12-12-to-2026-04-02 |
| Sample days | 112 |
| BTIH count | 257 |
| Unique BTIH count | 235 |
| Downloaders total | 29,646,480 |
| Uploaders total | 4,073,805 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-12-12-to-2026-04-02`
- Sample days: 112
- Serialized week intervals: 16
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![Pluribus collection size histogram](figures/pluribus-107-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/pluribus-107-downloads-by-week-pluribus-107-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![pluribus-107 downloads by day](figures/pluribus-107-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.57 | 17.12 | 29.88 | 46.38 | 1.71 | 0.62 |

### Cumulative network infrastructure

[![Pluribus cumulative map](figures/pluribus-107-carto.png)](figures/pluribus-107-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/pluribus-107-data-ge-1080p.webp)](figures/pluribus-107-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/pluribus-107-data-lt-1080p.webp)](figures/pluribus-107-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
