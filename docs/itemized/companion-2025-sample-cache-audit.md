---
layout: default
title: "companion-2025 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# companion-2025 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Companion |
| Collection key | `companion-2025` |
| imdb_id | [tt26584495](https://www.imdb.com/title/tt26584495/) |
| wikipedia_url | [Companion (film)](https://en.wikipedia.org/wiki/Companion_(film)) |
| Sample dates | 2025-02-18-to-2025-06-09 |
| Sample days | 112 |
| BTIH count | 265 |
| Unique BTIH count | 245 |
| Downloaders total | 28,082,545 |
| Uploaders total | 3,064,171 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-02-18-to-2025-06-09`
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

![Companion collection size histogram](figures/companion-2025-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/companion-2025-downloads-by-week-companion-2025-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![companion-2025 downloads by day](figures/companion-2025-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.66 | 14.17 | 26.86 | 52.06 | 0.97 | 0.57 |

### Cumulative network infrastructure

[![Companion cumulative map](figures/companion-2025-carto.png)](figures/companion-2025-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/companion-2025-data-ge-1080p.webp)](figures/companion-2025-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/companion-2025-data-lt-1080p.webp)](figures/companion-2025-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
