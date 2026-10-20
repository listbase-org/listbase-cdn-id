# ListBase CDN — Bahasa Indonesia (id)

Open dataset collection for **Bahasa Indonesia** (Indonesian).
510 datasets across 16 categories with 636,647 total records.

> Browse and download at [https://listbase.org/id/](https://listbase.org/id/)

## Categories

| Category | Datasets |
|----------|----------|
| [Budaya & Agama (Culture & Religion)](culture/) | 3 |
| [Hiburan (Entertainment)](entertainment/) | 1 |
| [Lingkungan (Environment)](environment/) | 3 |
| [Keuangan & Perdagangan (Finance & Trade)](finance/) | 10 |
| [Geografi (Geography)](geography/) | 134 |
| [Sejarah (History)](history/) | 1 |
| [Bahasa (Language)](language/) | 6 |
| [Matematika (Mathematics)](math/) | 3 |
| [Musik (Music)](music/) | 2 |
| [Politik (Politics)](politics/) | 2 |
| [Referensi (Reference)](reference/) | 252 |
| [Sains (Science)](science/) | 9 |
| [Teknologi (Technology)](tech/) | 24 |
| [Waktu & Kalender (Time & Calendar)](time/) | 5 |
| [Transportasi (Transport)](transport/) | 30 |
| [Satuan & Pengukuran (Units & Measurements)](units/) | 25 |

## Usage

### Browse on the web
Visit [listbase.org/id/](https://listbase.org/id/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.id.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.id.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.id.listbase.org/geography/th-central-provinces_ID.xlsx
curl -O https://cdn.id.listbase.org/geography/th-central-provinces_ID.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.id.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.id.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_ID.csv   # CSV download
│   └── {dataset}_ID.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
