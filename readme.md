# 🧮 Calculus & Numerical Analysis Final Project

Repository ini berisi kumpulan implementasi berbagai algoritma sebagai Tugas Akhir mata kuliah Kalkulus. Proyek ini berfokus pada simulasi, prediksi, dan pengelompokan data menggunakan Python, dengan validasi perhitungan manual menggunakan Microsoft Excel.

Setiap modul dalam proyek ini didasarkan pada studi kasus nyata yang diambil dari jurnal penelitian terlampir.

## 📖 Deskripsi Proyek

Tujuan utama dari repository ini adalah untuk membandingkan hasil komputasi algoritma (menggunakan Python) dengan perhitungan manual (Excel) untuk memastikan akurasi dan pemahaman mendalam mengenai metode yang digunakan.

### ✨ Fitur Utama
* **Dual Implementation:** Setiap algoritma diimplementasikan dalam dua bentuk:
    * 🐍 **Python (Jupyter Notebook):** Untuk komputasi otomatis, visualisasi grafik, dan penanganan data besar.
    * 📗 **Microsoft Excel:** Untuk pembuktian rumus dan perhitungan manual langkah-demi-langkah.
* **Real-world Case Studies:** Implementasi didasarkan pada jurnal ilmiah terpercaya.
* **Visualisasi Data:** Menggunakan grafik untuk mempermudah analisis hasil (terutama pada Euler dan Regresi).

---

## 🛠️ Tech Stack & Dependencies

Proyek ini dibangun menggunakan teknologi berikut:

* **Bahasa Pemrograman:** Python 3.x
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Library Python:**
    * `numpy` & `pandas` (Manipulasi Data)
    * `matplotlib` & `seaborn` (Visualisasi)
    * `scikit-learn` (Untuk algoritma Machine Learning seperti K-Means/Regresi)
    * `scikit-learn-extra` (Khusus untuk K-Medoids, jika digunakan)
* **Software Lain:** Microsoft Excel (format `.xlsx` / `.csv`)

---

## 📂 Daftar Modul & Implementasi

Berikut adalah rincian setiap metode yang diimplementasikan dalam folder ini beserta referensi jurnalnya:

### 1. Metode Euler (`/euler`)
* **Deskripsi:** Simulasi penyelesaian persamaan diferensial biasa untuk memodelkan **Gerak Pegas (Harmonic Motion)**. Metode ini menghitung posisi dan kecepatan benda pada setiap titik waktu $h$ yang ditentukan.
* **Referensi:** *Implementasi Metode Euler Pada Gerak Pegas Dengan Menggunakan Scilab*.
* **File:** `euler.ipynb`, `euler.xlsx`.

### 2. K-Means Clustering (`/kmeans`)
* **Deskripsi:** Algoritma *Unsupervised Learning* untuk mengelompokkan data (Clustering). Studi kasus berfokus pada pengelompokan siswa berdasarkan nilai akademik untuk menentukan kelas unggulan atau reguler.
* **Referensi:** *Penerapan Data Mining Untuk Pengelompokan Siswa Berdasarkan Nilai Akademik dengan Algoritma K-Means*.
* **File:** `kmeans.ipynb`, `kmeans manual.xlsx`.

### 3. K-Medoids Clustering (`/kmedoids`)
* **Deskripsi:** Variasi dari K-Means yang menggunakan objek data aktual (medoid) sebagai pusat klaster, sehingga lebih tahan terhadap *outlier*. Studi kasus diterapkan pada klastering data perkebunan (kecambah kelapa sawit).
* **Referensi:** *Pemanfaatan Algoritma K-Medoids untuk Klustering Kecambah Kelapa Sawit*.
* **File:** `journal kmedoids.ipynb`, `kmedoids manual.xlsx`.

### 4. Simulasi Monte Carlo (`/monte carlo`)
* **Deskripsi:** Metode probabilistik untuk meramalkan (*forecasting*) kemungkinan hasil dari suatu proses yang tidak pasti. Digunakan untuk memprediksi pembelian stok barang (aksesoris laptop) di masa depan.
* **Referensi:** *Penerapan Metode Monte Carlo Untuk Peramalan Pembelian Aksesoris Laptop*.
* **File:** `monte carlo.ipynb`, `Monte Carlo.xlsx`.

### 5. Regresi Linear Sederhana (`/regresi linear`)
* **Deskripsi:** Metode statistik untuk memodelkan hubungan antara dua variabel (independen dan dependen) guna melakukan prediksi harga (misal: harga beras) berdasarkan data historis waktu.
* **Referensi:** *Penerapan Metode Regresi Linear Sederhana Untuk Prediksi Harga Beras*.
* **File:** `regresi linier.ipynb`, `regresi linear manual.xlsx`.

---

## 🚀 Cara Menjalankan

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/username-anda/nama-repo.git](https://github.com/username-anda/nama-repo.git)
    ```
2.  **Install Library:**
    Pastikan Python sudah terinstall, lalu jalankan:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  **Buka Jupyter Notebook:**
    Masuk ke folder proyek dan jalankan:
    ```bash
    jupyter notebook
    ```
4.  **Eksplorasi:** Buka file `.ipynb` di setiap folder untuk melihat kode dan visualisasi, atau buka file `.xlsx` untuk melihat perhitungan manualnya.

---

## 📚 Referensi Jurnal

Proyek ini merujuk pada publikasi ilmiah berikut sebagai landasan teori dan studi kasus:

1.  **Euler:** Azis, R. S., & Ramli, I. (2020). *Implementasi Metode Euler Pada Gerak Pegas*.
2.  **K-Means:** Hasugian, P. S., & Sagala, J. R. (2022). *Penerapan Data Mining Untuk Pengelompokan Siswa... dengan Algoritma K-Means*.
3.  **K-Medoids:** Nuraini, S., et al. (2022). *Pemanfaatan Algoritma K-Medoids untuk Klustering Kecambah Kelapa Sawit*.
4.  **Monte Carlo:** Mulana, M. I., & Haryanto, E. V. (2022). *Penerapan Metode Monte Carlo Untuk Peramalan Pembelian...*.
5.  **Regresi Linear:** Hasibuan, L. H., & Musthofa, S. (2022). *Penerapan Metode Regresi Linear Sederhana Untuk Prediksi Harga Beras...*.

---

**👨‍💻 Author**
* **Dibuat oleh:** rfrz
* *Tugas Akhir Mata Kuliah Kalkulus 2.*
