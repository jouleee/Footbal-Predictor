# Footbal-Predictor
# Machine Learning & AI - Prediksi Pertandingan Bola

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model Machine Learning yang dapat mengelompokkan pertandingan sepak bola berdasarkan berbagai fitur statistik pertandingan sebelumnya menggunakan teknik clustering. Model ini menggunakan metode Gaussian Mixture Model (GMM) dan K-Means untuk menemukan pola dalam data tanpa label.

## Fitur Proyek
- **Preprocessing Data:** Membersihkan dan menyiapkan data pertandingan.
- **Feature Engineering:** Ekstraksi fitur penting untuk meningkatkan hasil clustering.
- **Clustering:** Implementasi metode K-Means dan Gaussian Mixture Model (GMM) untuk mengelompokkan pertandingan.
- **Evaluasi Model:** Menggunakan metrik seperti inertia, silhouette score, dan visualisasi clustering.
- **Visualisasi Hasil:** Grafik distribusi cluster dan analisis pola pertandingan.

## Struktur Direktori
```
├── data                # Dataset mentah dan hasil preprocessing
├── notebooks           # Notebook Jupyter untuk eksplorasi dan model
├── models              # Model yang telah disimpan
├── src                 # Kode sumber untuk preprocessing dan model
├── requirements.txt    # Daftar dependensi
├── README.md           # Dokumentasi proyek
```

## Instalasi
Pastikan Anda memiliki Python 3.x terinstal. Kemudian, jalankan perintah berikut untuk menginstal dependensi:
```bash
pip install -r requirements.txt
```

## Cara Menggunakan
1. **Persiapan Data:** Simpan dataset di dalam folder `data/`.
2. **Jalankan Notebook:** Buka dan eksekusi notebook di folder `notebooks/`.
3. **Lakukan Clustering:** Gunakan script di `src/` untuk menjalankan K-Means dan GMM.
4. **Evaluasi & Visualisasi:** Analisis hasil clustering menggunakan berbagai metrik evaluasi.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Kontribusi
Kontribusi terbuka untuk pengembangan proyek ini! Silakan fork repo ini dan ajukan pull request dengan perubahan yang ingin Anda buat.

## Lisensi
Proyek ini dilisensikan di bawah lisensi MIT - lihat file LICENSE untuk detail lebih lanjut.


