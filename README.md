# Segmentasi Pelanggan dengan Clustering pada Data Mall Customer

Proyek ini berfokus pada segmentasi pelanggan menggunakan data *Mall Customer* yang diperoleh dari Kaggle. Segmentasi pelanggan adalah proses mengelompokkan pelanggan berdasarkan karakteristik dan perilaku mereka. Dalam proyek ini, kita menerapkan teknik clustering untuk membagi pelanggan berdasarkan data demografi dan perilaku belanja.

## Deskripsi Proyek
Segmentasi pelanggan membantu bisnis untuk menyesuaikan strategi pemasaran berdasarkan kelompok pelanggan yang berbeda. Dengan menganalisis karakteristik dari setiap kelompok, bisnis dapat memahami kebutuhan pelanggan dengan lebih baik dan menawarkan promosi yang lebih sesuai. Proyek ini menggunakan pembelajaran tanpa pengawasan, khususnya clustering, untuk mengelompokkan pelanggan berdasarkan usia, jenis kelamin, pendapatan tahunan, dan skor pengeluaran.

## Deskripsi Data
Dataset *Mall Customer* mencakup fitur-fitur berikut:
- **Umur** - Kelompok umur pelanggan
- **Jenis Kelamin** - Jenis kelamin pelanggan (Pria/Wanita)
- **Pendapatan Tahunan** - Estimasi pendapatan tahunan pelanggan
- **Skor Pengeluaran** - Skor yang mencerminkan kebiasaan belanja pelanggan

Data ini merupakan data sekunder dari Kaggle, artinya sudah dikumpulkan dan dipublikasikan oleh pihak lain.

## Tujuan Proyek
1. Mengelompokkan pelanggan ke dalam beberapa segmen menggunakan teknik clustering.
2. Mengidentifikasi karakteristik dari setiap segmen untuk mendukung strategi pemasaran yang lebih tepat sasaran.
3. Memvisualisasikan hasil clustering agar pemangku kepentingan dapat memahami karakteristik setiap segmen pelanggan.

## Metodologi
### Langkah-langkah:
1. **Eksplorasi Data**: Menganalisis distribusi data dan pola yang ada.
2. **Pra-pemrosesan Data**: Membersihkan, menormalisasi, dan mentransformasi data sesuai kebutuhan.
3. **Clustering**: Menggunakan algoritma K-Means untuk membagi data menjadi beberapa kluster dan menentukan jumlah kluster optimal.
4. **Visualisasi**: Memvisualisasikan hasil clustering untuk memahami segmen pelanggan secara efektif.

### Alat & Teknik
- **Algoritma Clustering**: K-Means
- **Visualisasi**: Matplotlib, Seaborn
- **Bahasa Pemrograman**: Python

## Persyaratan
- Python 3.x
- Jupyter Notebook
- Library: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## Hasil
Algoritma K-Means akan membagi pelanggan menjadi beberapa kluster yang memiliki karakteristik serupa. Visualisasi hasil clustering ini membantu kita memahami kelompok pelanggan berdasarkan usia, pendapatan, dan skor pengeluaran mereka.

## Kesimpulan
Proyek ini memberikan wawasan mengenai segmentasi pelanggan yang dapat membantu bisnis dalam menciptakan strategi pemasaran yang lebih efektif dan efisien berdasarkan kebutuhan dari setiap segmen pelanggan.
