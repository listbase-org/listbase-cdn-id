# Budaya & Agama (Culture & Religion)

3 datasets — 219 records

> Browse at [listbase.org/id/culture/](https://listbase.org/id/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Museum di Indonesia (Museums in Indonesia)](id-museum.json) | 129 | 28 KB | [CSV](id-museum_ID.csv) | [Excel](id-museum_ID.xlsx) | [View](https://listbase.org/id/culture/id-museum/) |
| [Lembaga Amil Zakat (LAZ) Indonesia (Registered Zakat Agencies)](id-lembaga-amil-zakat.json) | 81 | 13 KB | [CSV](id-lembaga-amil-zakat_ID.csv) | [Excel](id-lembaga-amil-zakat_ID.xlsx) | [View](https://listbase.org/id/culture/id-lembaga-amil-zakat/) |
| [Situs Warisan Dunia UNESCO di Indonesia](id-situs-warisan-dunia-unesco.json) | 9 | 11 KB | [CSV](id-situs-warisan-dunia-unesco_ID.csv) | [Excel](id-situs-warisan-dunia-unesco_ID.xlsx) | [View](https://listbase.org/id/culture/id-situs-warisan-dunia-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/culture/id-museum.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/culture/)
