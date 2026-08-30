---
layout: default
title: "peacemaker-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# peacemaker-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Peacemaker |
| Collection key | `peacemaker-201` |
| imdb_id | [tt13146488](https://www.imdb.com/title/tt13146488/) |
| wikipedia_url | [Peacemaker (TV series)](https://en.wikipedia.org/wiki/Peacemaker_(TV_series)) |
| Sample dates | 2025-08-22-to-2025-12-04 |
| Sample days | 105 |
| BTIH count | 276 |
| Unique BTIH count | 247 |
| Downloaders total | 20,782,331 |
| Uploaders total | 2,727,961 |
| Data version | `2026-06-18` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Evidence: completed year AAO release and serialized week product
- Release generated: 2026-08-07T04:29:58Z
- Release complete: true
- Manifest payloads verified: 2264/2264
- Manifest SHA-256: `4a4818facd85b709f0321b0a6de31b4a3eff6f108f3b9354c75632926e6baa48`
- Sample duration: `2025-08-22-to-2025-12-04`
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

![Peacemaker collection size histogram](figures/peacemaker-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/peacemaker-201-downloads-by-week-peacemaker-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![peacemaker-201 downloads by day](figures/peacemaker-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.12 | 19.31 | 29.33 | 42.96 | 1.86 | 0.52 |

### Cumulative network infrastructure

[![Peacemaker cumulative map](figures/peacemaker-201-carto.png)](figures/peacemaker-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/peacemaker-201-data-ge-1080p.webp)](figures/peacemaker-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/peacemaker-201-data-lt-1080p.webp)](figures/peacemaker-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
