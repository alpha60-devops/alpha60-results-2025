---
layout: default
title: "last-of-us-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# last-of-us-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Last of Us |
| Collection key | `last-of-us-201` |
| imdb_id | [tt3581920](https://www.imdb.com/title/tt3581920/) |
| wikipedia_url | [The Last of Us (TV series)](https://en.wikipedia.org/wiki/The_Last_of_Us_(TV_series)) |
| Sample dates | 2025-04-14-to-2025-10-26 |
| Sample days | 196 |
| BTIH count | 448 |
| Unique BTIH count | 432 |
| Downloaders total | 72,627,362 |
| Uploaders total | 7,088,622 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-30T16:41:11-07:00
- Release complete: true
- Manifest payloads verified: 2266/2266
- Manifest SHA-256: `f7cccd77fa83baa7a24036fc961f1c1131634582d18b5ad42de6adbd4b42c313`
- Sample duration: `2025-04-14-to-2025-10-26`
- Sample days: 196
- Serialized week intervals: 28
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![Last of Us collection size histogram](figures/last-of-us-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/last-of-us-201-downloads-by-week-last-of-us-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![last-of-us-201 downloads by day](figures/last-of-us-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.89 | 18.02 | 28.10 | 48.51 | 1.63 | 0.57 |

### Cumulative network infrastructure

[![Last of Us cumulative map](figures/last-of-us-201-carto.png)](figures/last-of-us-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/last-of-us-201-data-ge-1080p.webp)](figures/last-of-us-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/last-of-us-201-data-lt-1080p.webp)](figures/last-of-us-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
