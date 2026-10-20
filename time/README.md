# Waktu & Kalender (Time & Calendar)

5 datasets — 1,352 records

> Browse at [listbase.org/id/time/](https://listbase.org/id/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Hari Libur Nasional & Cuti Bersama Indonesia (1946–2030, multibahasa)](id-hari-libur-completos.json) | 1,231 | 612 KB | [CSV](id-hari-libur-completos_ID.csv) | [Excel](id-hari-libur-completos_ID.xlsx) | [View](https://listbase.org/id/time/id-hari-libur-completos/) |
| [Nama bulan menurut kalender (CLDR bahasa Indonesia)](id-bulan-kalender.json) | 74 | 13 KB | [CSV](id-bulan-kalender_ID.csv) | [Excel](id-bulan-kalender_ID.xlsx) | [View](https://listbase.org/id/time/id-bulan-kalender/) |
| [Hari, kuartal, periode hari dan era — nama dalam bahasa Indonesia (CLDR)](id-hari-kuartal-era.json) | 23 | 4 KB | [CSV](id-hari-kuartal-era_ID.csv) | [Excel](id-hari-kuartal-era_ID.xlsx) | [View](https://listbase.org/id/time/id-hari-kuartal-era/) |
| [Dataset Lengkap Hewan Zodiak Cina (12 Tanda)](time-chinese-zodiac.json) | 12 | 11 KB | [CSV](time-chinese-zodiac_ID.csv) | [Excel](time-chinese-zodiac_ID.xlsx) | [View](https://listbase.org/id/time/time-chinese-zodiac/) |
| [Data Zodiak Barat Komprehensif](time-zodiac-signs.json) | 12 | 9 KB | [CSV](time-zodiac-signs_ID.csv) | [Excel](time-zodiac-signs_ID.xlsx) | [View](https://listbase.org/id/time/time-zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/time/id-hari-libur-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/time/)
