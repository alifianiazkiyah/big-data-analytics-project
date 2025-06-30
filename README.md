# Business Performance Analytics Kimia Farma 2020-2023

🚀 Proyek ini bertujuan untuk menganalisis performa bisnis Kimia Farma berdasarkan data transaksi penjualan, cabang, produk, dan kepuasan pelanggan. Proses analitik dilakukan menggunakan SQL (BigQuery) untuk membentuk data analisa yang siap digunakan dalam visualisasi dan pengambilan keputusan strategis.

#### ✏️ Dataset
| Kolom | Keterangan |
| ------ | ------ |
| transaction_id | Kode unik transaksi |
| date | Tanggal transaksi |
| branch_id | ID cabang |
| branch_name | Nama cabang |
| kota | Kota lokasi cabang |
| provinsi | Provinsi lokasi cabang |
| rating_cabang | Penilaian pelanggan terhadap cabang |
| customer_name | Nama pelanggan |
| product_id | ID produk |
| product_name | Nama produk |
| actual_price | Harga asli produk |
| discount_percentage | Persentase diskon |
| nett_sales | Harga setelah diskon |
| persentase_gross_laba | Margin laba sesuai rentang harga produk |
| nett_profit | Laba bersih per transaksi |
| rating_transaksi | Penilaian pelanggan terhadap transaksi |

Catatan
Perhitungan margin laba dilakukan dengan logika CASE sesuai rentang harga:
- Harga ≤ Rp 50.000 → 10%
- Harga > Rp 50.000 – 100.000 → 15%
- Harga > Rp 100.000 – 300.000 → 20%
- Harga > Rp 300.000 – 500.000 → 25%
- Harga > Rp 500.000 → 30%

#### 📓 SQL Query
[syntax_bigquery.sql](https://github.com/alifianiazkiyah/big-data-analytics-project/blob/main/sytax_bigquery)

#### 📊 Visualisasi Data
[visualisasi_data](https://lookerstudio.google.com/reporting/58484822-6eca-471a-a237-4f453f204482)

#### Insight

#### Penutup
Melalui project ini, data transaksi Kimia Farma berhasil diolah dan dianalisis secara sistematis mulai dari penggabungan tabel, perhitungan laba bersih, hingga visualisasi kinerja bisnis dalam bentuk dashboard. Hasil analisis ini memberikan gambaran performa cabang dan produk, serta tingkat kepuasan pelanggan sebagai dasar pengambilan keputusan strategis.

---

Proyek ini merupakan bagian dari program pembelajaran di **Rakamin Academy** x **Kimia Farma** dalam pengembangan keterampilan analisis data berbasis kasus nyata industri.

Author:
Alifiani Azkiyah | Administrasi & Data Enthusiast
