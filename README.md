# Eksperimen_DataMining_IPM2024

# 📊 Dataset IPM 2024 – Prediksi Pembangunan Berdasarkan Indikator Sosial

## 📝 Deskripsi
Dataset ini berisi data Indeks Pembangunan Manusia (IPM) tahun 2024 untuk 538 daerah di Indonesia. Data ini mencakup indikator-indikator utama seperti harapan hidup, pendidikan, dan daya beli masyarakat, serta hasil prediksi dari model Artificial Neural Network (ANN) terkait kebutuhan pembangunan.

## 🗂️ Struktur Kolom

| Kolom             | Tipe     | Deskripsi                                                                    |
|------------------|---------- |----------------------------------------------------------------------------- |
| `nama_daerah`     | `object` | Nama provinsi atau kabupaten/kota di Indonesia                               |
| `AHHL`            | `float`  | Angka Harapan Hidup saat Lahir (dalam tahun)                                 |
| `AHHP`            | `float`  | Angka Harapan Lama Sekolah Penduduk Umur 7 Tahun (dalam tahun)               |
| `HLS`             | `float`  | Rata-rata Lama Sekolah Penduduk Umur ≥25 Tahun (dalam tahun)                 |
| `IPM`             | `float`  | Indeks Pembangunan Manusia (0–100)                                           |
| `PPM`             | `float`  | Pengeluaran per Kapita yang Disesuaikan (dalam juta rupiah/tahun)            |
| `Predicted_ANN`   | `object` | Hasil prediksi model ANN: `Perlu Pembangunan` atau `Tidak Perlu Pembangunan` |

## 🎯 Tujuan Dataset
Dataset ini digunakan untuk:
- Menganalisis hubungan antara indikator sosial dan IPM
- Memprediksi apakah suatu daerah memerlukan pembangunan tambahan
- Melatih dan menguji model Machine Learning (terutama ANN) dalam klasifikasi sosial-ekonomi

## 📌 Sumber Data
- Data asli: Badan Pusat Statistik (BPS) Indonesia
- Label prediksi (`Predicted_ANN`) dihasilkan dari model Artificial Neural Network (ANN) yang dilatih menggunakan indikator-indikator di atas

## 💡 Contoh Penggunaan
- Menentukan prioritas pembangunan daerah berdasarkan output ANN
- Visualisasi distribusi IPM dan faktor-faktornya
- Evaluasi kinerja model ANN dalam klasifikasi kesejahteraan daerah
