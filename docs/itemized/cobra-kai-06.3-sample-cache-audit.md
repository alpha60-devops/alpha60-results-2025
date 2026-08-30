---
layout: default
title: "cobra-kai-06.3 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# cobra-kai-06.3 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Cobra Kai |
| Collection key | `cobra-kai-06.3` |
| imdb_id | [tt7221388](https://www.imdb.com/title/tt7221388/) |
| wikipedia_url | [Cobra Kai](https://en.wikipedia.org/wiki/Cobra_Kai) |
| Sample dates | 2025-02-13-to-2025-05-28 |
| Sample days | 105 |
| BTIH count | 241 |
| Unique BTIH count | 236 |
| Downloaders total | 12,846,209 |
| Uploaders total | 614,957 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-02-13-to-2025-05-28`
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

![Cobra Kai collection size histogram](figures/cobra-kai-06.3-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/cobra-kai-06-3-downloads-by-week-cobra-kai-06.3-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![cobra-kai-06.3 downloads by day](figures/cobra-kai-06-3-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.34 | 15.94 | 26.23 | 52.54 | 1.03 | 0.53 |

### Cumulative network infrastructure

[![Cobra Kai cumulative map](figures/cobra-kai-06.3-carto.png)](figures/cobra-kai-06.3-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/cobra-kai-06.3-data-ge-1080p.webp)](figures/cobra-kai-06.3-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/cobra-kai-06.3-data-lt-1080p.webp)](figures/cobra-kai-06.3-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
