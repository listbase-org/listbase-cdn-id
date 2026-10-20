# Musik (Music)

2 datasets — 162 records

> Browse at [listbase.org/id/music/](https://listbase.org/id/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Dataset Referensi Bagan Akor Piano Esensial](music-piano-chords.json) | 84 | 21 KB | [CSV](music-piano-chords_ID.csv) | [Excel](music-piano-chords_ID.xlsx) | [View](https://listbase.org/id/music/music-piano-chords/) |
| [Dataset Bagan Kunci Gitar Komprehensif](music-guitar-chords.json) | 78 | 23 KB | [CSV](music-guitar-chords_ID.csv) | [Excel](music-guitar-chords_ID.xlsx) | [View](https://listbase.org/id/music/music-guitar-chords/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/music/music-piano-chords.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/music/)
