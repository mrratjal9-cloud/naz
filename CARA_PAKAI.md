# Cara pakai file infografis

File diagram tersedia dalam 3 format:

| File | Format | Untuk apa |
|---|---|---|
| `alur_proses_ekstraksi_flavonoid.svg` | SVG (vector) | Master file, paling fleksibel. Bisa dibuka di browser, Inkscape, Illustrator, Visio modern (2016+) |
| `alur_proses_ekstraksi_flavonoid.vsdx` | Microsoft Visio | Dibuka langsung di Visio sebagai gambar. Bisa di-edit posisi & ukurannya |
| `alur_proses_ekstraksi_flavonoid.pdf` | PDF (vector) | Untuk dicetak atau dilampirkan ke laporan |

## Cara edit di Microsoft Visio

### Cara 1 — pakai file `.vsdx` (paling cepat)

1. Buka `alur_proses_ekstraksi_flavonoid.vsdx` di Visio
2. Klik gambar di kanvas → klik kanan → **Convert to Shape** (Konversi ke Bentuk)
3. Setelah dikonversi, kotak-kotak dan teks bisa di-edit individual

### Cara 2 — import SVG langsung (rekomendasi untuk Visio 2016+)

Visio modern bisa baca SVG dengan kualitas vector yang lebih bagus:

1. Buka Visio, buat dokumen baru (ukuran landscape, A3 atau lebih besar)
2. **Insert** → **Pictures** → pilih file `alur_proses_ekstraksi_flavonoid.svg`
3. Klik kanan gambar → **Convert to Shape** untuk bisa edit per elemen

### Cara 3 — kalau Convert to Shape tidak tersedia

1. Buka Visio dengan halaman kosong landscape
2. Drag file SVG langsung ke kanvas
3. Klik kanan → **Group** → **Ungroup** (Pisahkan)
4. Sekarang setiap kotak/teks bisa di-edit terpisah

## Catatan penting

- File `.vsdx` ini berisi PNG resolusi tinggi (3000px) yang ter-embed di dalam template Visio. Jadi tetap tajam saat di-zoom, tapi setelah di-Convert to Shape, kualitasnya tergantung versi Visio
- Untuk hasil edit terbaik, pakai **Cara 2** (import SVG langsung di Visio 2016+) karena Visio akan parse vector-nya dengan kualitas penuh
- Kalau perlu modifikasi besar (rearrange layout), saran saya edit di file `.svg`-nya pakai Inkscape (gratis) atau Adobe Illustrator
