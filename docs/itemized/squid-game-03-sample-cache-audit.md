---
layout: default
title: "squid-game-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# squid-game-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Squid Game |
| Collection key | `squid-game-03` |
| imdb_id | [tt10919420](https://www.imdb.com/title/tt10919420/) |
| wikipedia_url | [Squid Game](https://en.wikipedia.org/wiki/Squid_Game) |
| Sample dates | 2025-06-27-to-2025-12-26 |
| Sample days | 183 |
| BTIH count | 179 |
| Unique BTIH count | 173 |
| Downloaders total | 28,067,758 |
| Uploaders total | 2,816,500 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-06-27-to-2025-12-26`
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

![Squid Game collection size histogram](figures/squid-game-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/squid-game-03-downloads-by-week-squid-game-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![squid-game-03 downloads by day](figures/squid-game-03-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.49 | 14.35 | 32.66 | 45.88 | 1.01 | 0.58 |

### Cumulative network infrastructure

[![Squid Game cumulative map](figures/squid-game-03-carto.png)](figures/squid-game-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/squid-game-03-data-ge-1080p.webp)](figures/squid-game-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/squid-game-03-data-lt-1080p.webp)](figures/squid-game-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
