# Sains (Science)

9 datasets — 405 records

> Browse at [listbase.org/id/science/](https://listbase.org/id/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Dataset Tabel Periodik Elemen Kimia Komprehensif](science-periodic-table.json) | 118 | 38 KB | [CSV](science-periodic-table_ID.csv) | [Excel](science-periodic-table_ID.xlsx) | [View](https://listbase.org/id/science/science-periodic-table/) |
| [Dataset Tabel Kodon RNA Lengkap](science-codon-table.json) | 64 | 13 KB | [CSV](science-codon-table_ID.csv) | [Excel](science-codon-table_ID.xlsx) | [View](https://listbase.org/id/science/science-codon-table/) |
| [Dataset Tabel Elektronegativitas (Skala Pauling)](science-electronegativity.json) | 62 | 17 KB | [CSV](science-electronegativity_ID.csv) | [Excel](science-electronegativity_ID.xlsx) | [View](https://listbase.org/id/science/science-electronegativity/) |
| [Dataset Sistem Satuan Internasional (Satuan SI)](science-si-units.json) | 53 | 12 KB | [CSV](science-si-units_ID.csv) | [Excel](science-si-units_ID.xlsx) | [View](https://listbase.org/id/science/science-si-units/) |
| [Dataset Referensi Skala pH & Properti Kimia](science-ph-scale.json) | 33 | 8 KB | [CSV](science-ph-scale_ID.csv) | [Excel](science-ph-scale_ID.xlsx) | [View](https://listbase.org/id/science/science-ph-scale/) |
| [Dataset Tabel Aturan Kelarutan Komprehensif](science-solubility-rules.json) | 31 | 11 KB | [CSV](science-solubility-rules_ID.csv) | [Excel](science-solubility-rules_ID.xlsx) | [View](https://listbase.org/id/science/science-solubility-rules/) |
| [Kumpulan Data Properti Asam Amino Komprehensif](science-amino-acids.json) | 22 | 10 KB | [CSV](science-amino-acids_ID.csv) | [Excel](science-amino-acids_ID.xlsx) | [View](https://listbase.org/id/science/science-amino-acids/) |
| [Dataset Bagan Kompatibilitas Golongan Darah Komprehensif](science-blood-types.json) | 11 | 6 KB | [CSV](science-blood-types_ID.csv) | [Excel](science-blood-types_ID.xlsx) | [View](https://listbase.org/id/science/science-blood-types/) |
| [Kumpulan Data Planet & Benda Langit Tata Surya](science-planet-data.json) | 11 | 10 KB | [CSV](science-planet-data_ID.csv) | [Excel](science-planet-data_ID.xlsx) | [View](https://listbase.org/id/science/science-planet-data/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/science/science-periodic-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/science/)
