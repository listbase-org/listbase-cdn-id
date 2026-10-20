# Bahasa (Language)

6 datasets — 788 records

> Browse at [listbase.org/id/language/](https://listbase.org/id/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Tabel Suku Kata Pinyin China Komprehensif & Panduan Pelafalan](lang-pinyin-table.json) | 408 | 99 KB | [CSV](lang-pinyin-table_ID.csv) | [Excel](lang-pinyin-table_ID.xlsx) | [View](https://listbase.org/id/language/lang-pinyin-table/) |
| [Sistem penulisan dunia (ISO 15924 / CLDR bahasa Indonesia)](id-sistem-penulisan.json) | 195 | 16 KB | [CSV](id-sistem-penulisan_ID.csv) | [Excel](id-sistem-penulisan_ID.xlsx) | [View](https://listbase.org/id/language/id-sistem-penulisan/) |
| [Dataset Tabel Klasifikasi Kata Ganti Bahasa Inggris](lang-english-pronouns.json) | 69 | 20 KB | [CSV](lang-english-pronouns_ID.csv) | [Excel](lang-english-pronouns_ID.xlsx) | [View](https://listbase.org/id/language/lang-english-pronouns/) |
| [Kumpulan Data Tabel Hiragana Jepang & Pemetaan Romaji](lang-hiragana-table.json) | 46 | 11 KB | [CSV](lang-hiragana-table_ID.csv) | [Excel](lang-hiragana-table_ID.xlsx) | [View](https://listbase.org/id/language/lang-hiragana-table/) |
| [Dataset Tabel Karakter Katakana Jepang Lengkap](lang-katakana-table.json) | 46 | 11 KB | [CSV](lang-katakana-table_ID.csv) | [Excel](lang-katakana-table_ID.xlsx) | [View](https://listbase.org/id/language/lang-katakana-table/) |
| [Dataset Karakter Alfabet Yunani Lengkap](lang-greek-alphabet.json) | 24 | 9 KB | [CSV](lang-greek-alphabet_ID.csv) | [Excel](lang-greek-alphabet_ID.xlsx) | [View](https://listbase.org/id/language/lang-greek-alphabet/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.id.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.id.listbase.org/language/lang-pinyin-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/id/language/)
