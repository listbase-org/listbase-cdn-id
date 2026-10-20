# Keuangan & Perdagangan (Finance & Trade)

10 datasets — 5,685 records

> Browse at [listbase.org/id/finance/](https://listbase.org/id/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Penyelenggara KUPVA / Valuta Asing Berizin Indonesia (Licensed Money Changers)](id-penyelenggara-kupva.json) | 4,228 | 2080 KB | [CSV](id-penyelenggara-kupva_ID.csv) | [Excel](id-penyelenggara-kupva_ID.xlsx) | [View](https://listbase.org/id/finance/id-penyelenggara-kupva/) |
| [Emiten Bursa Efek Indonesia (Listed Companies on IDX)](id-emiten-bei.json) | 720 | 138 KB | [CSV](id-emiten-bei_ID.csv) | [Excel](id-emiten-bei_ID.xlsx) | [View](https://listbase.org/id/finance/id-emiten-bei/) |
| [Id Bank](id-bank.json) | 147 | 29 KB | [CSV](id-bank_ID.csv) | [Excel](id-bank_ID.xlsx) | [View](https://listbase.org/id/finance/id-bank/) |
| [Daftar Bank di Indonesia — kode bank](id-banks.json) | 141 | 17 KB | [CSV](id-banks_ID.csv) | [Excel](id-banks_ID.xlsx) | [View](https://listbase.org/id/finance/id-banks/) |
| [Dataset Registri Awalan Barcode & Kode Negara GS1](finance-gs1-codes.json) | 126 | 19 KB | [CSV](finance-gs1-codes_ID.csv) | [Excel](finance-gs1-codes_ID.xlsx) | [View](https://listbase.org/id/finance/finance-gs1-codes/) |
| [Fintech P2P Lending Terdaftar/Berizin OJK (Registered P2P Lending Platforms)](id-fintech-p2p-lending.json) | 125 | 44 KB | [CSV](id-fintech-p2p-lending_ID.csv) | [Excel](id-fintech-p2p-lending_ID.xlsx) | [View](https://listbase.org/id/finance/id-fintech-p2p-lending/) |
| [Dataset Bab Kode HS (Harmonized System)](finance-hs-codes.json) | 98 | 21 KB | [CSV](finance-hs-codes_ID.csv) | [Excel](finance-hs-codes_ID.xlsx) | [View](https://listbase.org/id/finance/finance-hs-codes/) |
| [Dataset Komprehensif Tarif PPN/GST Berdasarkan Negara](finance-vat-rates.json) | 75 | 18 KB | [CSV](finance-vat-rates_ID.csv) | [Excel](finance-vat-rates_ID.xlsx) | [View](https://listbase.org/id/finance/finance-vat-rates/) |
| [Dataset Kode & Spesifikasi Kontainer Pengiriman ISO 6346](finance-container-codes.json) | 14 | 8 KB | [CSV](finance-container-codes_ID.csv) | [Excel](finance-container-codes_ID.xlsx) | [View](https://listbase.org/id/finance/finance-container-codes/) |
| [Dataset Aturan & Definisi Incoterms 2020](finance-incoterms.json) | 11 | 7 KB | [CSV](finance-incoterms_ID.csv) | [Excel](finance-incoterms_ID.xlsx) | [View](https://listbase.org/id/finance/finance-incoterms/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/finance/id-penyelenggara-kupva.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/finance/)
