# Lingkungan (Environment)

3 datasets — 197 records

> Browse at [listbase.org/id/environment/](https://listbase.org/id/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Pembangkit listrik di Indonesia](id-pembangkit-listrik.json) | 178 | 71 KB | [CSV](id-pembangkit-listrik_ID.csv) | [Excel](id-pembangkit-listrik_ID.xlsx) | [View](https://listbase.org/id/environment/id-pembangkit-listrik/) |
| [Satuan ukuran — kategori 'energy' (14)](id-satuan-ukuran-energy.json) | 14 | 4 KB | [CSV](id-satuan-ukuran-energy_ID.csv) | [Excel](id-satuan-ukuran-energy_ID.xlsx) | [View](https://listbase.org/id/environment/id-satuan-ukuran-energy/) |
| [Satuan ukuran — kategori 'temperature' (5)](id-satuan-ukuran-temperature.json) | 5 | 3 KB | [CSV](id-satuan-ukuran-temperature_ID.csv) | [Excel](id-satuan-ukuran-temperature_ID.xlsx) | [View](https://listbase.org/id/environment/id-satuan-ukuran-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/environment/id-pembangkit-listrik.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/environment/)
