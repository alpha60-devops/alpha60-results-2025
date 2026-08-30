---
layout: default
title: "nouvelle-vague Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# nouvelle-vague sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Nouvelle Vauge |
| Collection key | `nouvelle-vague` |
| imdb_id | [tt31688586](https://www.imdb.com/title/tt31688586/) |
| wikipedia_url | [Nouvelle Vague (2025 film)](https://en.wikipedia.org/wiki/Nouvelle_Vague_(2025_film)) |
| Sample dates | 2025-11-14-to-2026-02-05 |
| Sample days | 84 |
| BTIH count | 23 |
| Unique BTIH count | 21 |
| Downloaders total | 1,597,942 |
| Uploaders total | 73,781 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-11-14-to-2026-02-05`
- Sample days: 84
- Serialized week intervals: 12
- Data version: `2026-06-18`
- IP geolocation version: `6:1777968300`

### Sparse weekly intervals

None recorded for this media object.

### Evidence boundary

This section reuses the checksum-verified AAO release evidence.
No raw sample was reopened and no week or cumulative product was
regenerated for the day-only augmentation.

## 3. Media objects file size histogram

![Nouvelle Vauge collection size histogram](figures/nouvelle-vague-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/nouvelle-vague-downloads-by-week-nouvelle-vague-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![nouvelle-vague downloads by day](figures/nouvelle-vague-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 0.87 | 13.73 | 28.57 | 42.53 | 0.94 | 0.64 |

### Cumulative network infrastructure

[![Nouvelle Vauge cumulative map](figures/nouvelle-vague-carto.png)](figures/nouvelle-vague-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/nouvelle-vague-data-ge-1080p.webp)](figures/nouvelle-vague-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/nouvelle-vague-data-lt-1080p.webp)](figures/nouvelle-vague-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
