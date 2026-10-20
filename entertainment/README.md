# Hiburan (Entertainment)

1 datasets — 1,502 records

> Browse at [listbase.org/id/entertainment/](https://listbase.org/id/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Penerbit Buku Indonesia (Book Publishers in Indonesia)](id-penerbit.json) | 1,502 | 260 KB | [CSV](id-penerbit_ID.csv) | [Excel](id-penerbit_ID.xlsx) | [View](https://listbase.org/id/entertainment/id-penerbit/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/entertainment/id-penerbit.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/entertainment/)
