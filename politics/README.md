# Politik (Politics)

2 datasets — 1,073 records

> Browse at [listbase.org/id/politics/](https://listbase.org/id/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Id Dinas Kesehatan](id-dinas-kesehatan.json) | 548 | 70 KB | [CSV](id-dinas-kesehatan_ID.csv) | [Excel](id-dinas-kesehatan_ID.xlsx) | [View](https://listbase.org/id/politics/id-dinas-kesehatan/) |
| [Lembaga Pemasyarakatan (LAPAS) di Indonesia (Prisons in Indonesia)](id-lembaga-pemasyarakatan.json) | 525 | 48 KB | [CSV](id-lembaga-pemasyarakatan_ID.csv) | [Excel](id-lembaga-pemasyarakatan_ID.xlsx) | [View](https://listbase.org/id/politics/id-lembaga-pemasyarakatan/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/politics/id-dinas-kesehatan.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/politics/)
