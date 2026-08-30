---
layout: default
title: "long-story-short-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# long-story-short-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Long Story Short |
| Collection key | `long-story-short-01` |
| imdb_id | [tt33247080](https://www.imdb.com/title/tt33247080/) |
| wikipedia_url | [Long Story Short (TV series)](https://en.wikipedia.org/wiki/Long_Story_Short_(TV_series)) |
| Sample dates | 2025-08-22-to-2026-02-05 |
| Sample days | 168 |
| BTIH count | 156 |
| Unique BTIH count | 155 |
| Downloaders total | 14,721,946 |
| Uploaders total | 249,162 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-08-22-to-2026-02-05`
- Sample days: 168
- Serialized week intervals: 24
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![The Long Story Short collection size histogram](figures/long-story-short-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/long-story-short-01-downloads-by-week-long-story-short-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![long-story-short-01 downloads by day](figures/long-story-short-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.84 | 16.56 | 31.52 | 47.10 | 0.98 | 0.62 |

### Cumulative network infrastructure

[![The Long Story Short cumulative map](figures/long-story-short-01-carto.png)](figures/long-story-short-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/long-story-short-01-data-ge-1080p.webp)](figures/long-story-short-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/long-story-short-01-data-lt-1080p.webp)](figures/long-story-short-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
