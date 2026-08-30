---
layout: default
title: "invincible-301 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# invincible-301 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Invincible |
| Collection key | `invincible-301` |
| imdb_id | [tt6741278](https://www.imdb.com/title/tt6741278/) |
| wikipedia_url | [Invincible (TV series)](https://en.wikipedia.org/wiki/Invincible_(TV_series)) |
| Sample dates | 2025-02-06-to-2025-05-21 |
| Sample days | 105 |
| BTIH count | 231 |
| Unique BTIH count | 214 |
| Downloaders total | 18,105,319 |
| Uploaders total | 2,007,730 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-02-06-to-2025-05-21`
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

![Invincible collection size histogram](figures/invincible-301-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/invincible-301-downloads-by-week-invincible-301-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![invincible-301 downloads by day](figures/invincible-301-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.50 | 16.94 | 26.35 | 49.94 | 1.32 | 0.50 |

### Cumulative network infrastructure

[![Invincible cumulative map](figures/invincible-301-carto.png)](figures/invincible-301-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/invincible-301-data-ge-1080p.webp)](figures/invincible-301-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/invincible-301-data-lt-1080p.webp)](figures/invincible-301-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
