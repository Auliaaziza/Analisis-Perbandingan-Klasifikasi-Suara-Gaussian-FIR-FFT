# Analisis-Perbandingan-Klasifikasi-Suara-Gaussian-FIR-FFT
**Analisis akurasi klasifikasi suara laki-laki dan perempuan menggunakan SVM dengan pemrosesan FFT, filter FIR, dan Gaussian noise.**

Repositori ini berisi implementasi dan evaluasi sistem klasifikasi suara laki-laki dan perempuan berbasis **Support Vector Machine (SVM)**. Sistem ini memanfaatkan Pengolahan Sinyal Digital berupa **Fast Fourier Transform (FFT)**, **filter FIR**, serta variasi **window function** untuk menganalisis pengaruhnya terhadap performa klasifikasi, baik pada kondisi sinyal bersih maupun sinyal yang terkontaminasi **Gaussian noise (SNR 20 dB)**.

Proyek ini disusun sebagai bagian dari tugas akkhir mata kuliah Pengolahan Sinyal Digital

## 📌 Sumber Dataset

Dataset yang digunakan dalam penelitian ini berasal dari platform **Mendeley** dan **tidak disertakan secara langsung** dalam repository GitHub karena keterbatasan lisensi dan hak cipta.

Dataset asli dapat diakses melalui tautan resmi berikut:

🔗 **[https://data.mendeley.com/datasets/4gzzc9k49n/3]** & **[https://data.mendeley.com/datasets/3zz6txz35t/6]**

## 📊 Penggunaan Subset Dataset

Pada penelitian ini, **tidak seluruh data dari dataset Mendeley digunakan**.  
Project hanya memanfaatkan **subset data**, dengan rincian sebagai berikut:

- **30 file audio suara laki-laki (male)**
- **30 file audio suara perempuan (female)**

Sehingga total data yang digunakan adalah **60 file audio**.

Pemilihan subset ini dilakukan dengan pertimbangan:

1. Menjaga **keseimbangan jumlah data antar kelas**
2. Menyesuaikan dengan **keterbatasan waktu dan sumber daya komputasi**
3. Fokus pada **analisis pengaruh window function dan noise**, bukan pada skala dataset besar

## 📁 Struktur Data yang Digunakan

Setelah dataset diunduh dan dipilih subsetnya, struktur folder data yang digunakan adalah:
data/
├── male/
│ ├── *.wav (30 file)
├── female/
│ ├── *.wav (30 file)
