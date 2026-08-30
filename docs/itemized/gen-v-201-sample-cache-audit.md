---
layout: default
title: "gen-v-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# gen-v-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Gen V |
| Collection key | `gen-v-201` |
| imdb_id | [tt13159924](https://www.imdb.com/title/tt13159924/) |
| wikipedia_url | [Gen V](https://en.wikipedia.org/wiki/Gen_V) |
| Sample dates | 2025-09-17-to-2026-03-17 |
| Sample days | 182 |
| BTIH count | 352 |
| Unique BTIH count | 324 |
| Downloaders total | 61,932,288 |
| Uploaders total | 2,438,916 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-09-17-to-2026-03-17`
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

![Gen V collection size histogram](figures/gen-v-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/gen-v-201-downloads-by-week-gen-v-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![gen-v-201 downloads by day](figures/gen-v-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.47 | 15.95 | 32.19 | 47.32 | 1.11 | 0.63 |

### Cumulative network infrastructure

[![Gen V cumulative map](figures/gen-v-201-carto.png)](figures/gen-v-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/gen-v-201-data-ge-1080p.webp)](figures/gen-v-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/gen-v-201-data-lt-1080p.webp)](figures/gen-v-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
