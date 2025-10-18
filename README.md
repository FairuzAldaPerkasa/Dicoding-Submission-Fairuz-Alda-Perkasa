<div align="center">
  <h1><b>Proyek Analisis Data: E-Commerce Public Dataset</b></h1>
  <p>
    <b>Sebuah dasbor analitik interaktif yang dibangun untuk menganalisis performa E-Commerce di Brazil menggunakan Olist Dataset.</b>
  </p>
  <p>
    <sup>Proyek ini merupakan submisi untuk kelas <b>Belajar Analisis Data dengan Python</b> di <a href="https://www.dicoding.com/">Dicoding</a>.</sup>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
    <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  </p>
</div>

Dasbor ini menyajikan visualisasi data dari dataset E-Commerce publik Brasil yang dipublikasikan di Kaggle. Tujuannya adalah untuk menjawab pertanyaan bisnis kunci melalui eksplorasi data, analisis, dan visualisasi yang mudah dipahami.

---

## ❓ Pertanyaan Bisnis yang Dijawab

Proyek analisis data ini bertujuan untuk menjawab dua pertanyaan bisnis utama:
1.  **Bagaimana demografi pelanggan kita?**
    - Analisis ini menggali dari negara bagian (state) mana saja pelanggan berasal untuk memahami distribusi geografis mereka.
2.  **Bagaimana performa penjualan dan pendapatan perusahaan dalam beberapa bulan terakhir?**
    - Analisis ini melacak tren penjualan bulanan untuk mengidentifikasi pertumbuhan, penurunan, atau pola musiman dalam pendapatan.

## ✨ Fitur Utama Dasbor

-   **📈 Visualisasi Tren Penjualan Bulanan:** Grafik garis interaktif yang menampilkan jumlah pesanan bulanan dari tahun 2017 hingga 2018.
-   **🌍 Peta Demografi Pelanggan:** Visualisasi data geografis yang menunjukkan konsentrasi pelanggan di berbagai negara bagian di Brazil.
-   **📊 Analisis RFM (Recency, Frequency, Monetary):**
    - Visualisasi skor RFM terbaik berdasarkan *Recency* (kapan terakhir membeli), *Frequency* (seberapa sering membeli), dan *Monetary* (total uang yang dikeluarkan).
-   **🔢 Statistik Utama:** Menampilkan metrik kunci seperti total pesanan, total pengeluaran, total pelanggan, dan total produk terjual.
-   **📅 Filter Berdasarkan Tanggal:** Pengguna dapat memilih rentang tanggal untuk menganalisis data dalam periode waktu tertentu.

## 🛠️ Teknologi yang Digunakan

-   **Bahasa & Pustaka:**
    -   **Python 3.9+**
    -   **Streamlit:** Untuk membangun dasbor web interaktif.
    -   **Pandas:** Untuk manipulasi dan pembersihan data.
    -   **Matplotlib & Seaborn:** Untuk pembuatan grafik dan visualisasi data.
    -   **Jupyter Notebook:** Untuk proses eksplorasi dan analisis data awal (EDA).
-   **Dataset:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 📂 Struktur Proyek

Repositori ini terdiri dari beberapa file dan direktori utama:

```

/dicoding-submission-fairuz-alda-perkasa
├── Dataset/                \# Berisi semua file CSV dari Olist Dataset.
│   ├── olist\_customers\_dataset.csv
│   ├── olist\_orders\_dataset.csv
│   ├── ...
├── dashboard/
│   ├── Project\_Data\_Clean.csv \# Data yang sudah dibersihkan untuk dasbor.
│   └── dashboard.py        \# Skrip utama untuk menjalankan aplikasi Streamlit.
├── notebook.ipynb          \# File Jupyter Notebook berisi semua proses EDA dan analisis.
├── requirements.txt        \# Daftar pustaka Python yang dibutuhkan.
└── README.md               \# File ini.

````

## ⚙️ Panduan Instalasi & Penggunaan

Ikuti langkah-langkah berikut untuk menjalankan dasbor ini di lingkungan lokal Anda.

1.  **Prasyarat:**
    -   Pastikan **Python 3.9** atau versi lebih baru sudah terpasang di sistem Anda.

2.  **Clone Repository:**
    ```bash
    git clone [https://github.com/fairuzaldaperkasa/dicoding-submission-fairuz-alda-perkasa.git](https://github.com/fairuzaldaperkasa/dicoding-submission-fairuz-alda-perkasa.git)
    cd dicoding-submission-fairuz-alda-perkasa
    ```

3.  **Buat Lingkungan Virtual (Direkomendasikan):**
    ```bash
    python -m venv venv
    # Aktivasi di Windows
    venv\Scripts\activate
    # Aktivasi di macOS/Linux
    source venv/bin/activate
    ```

4.  **Instal Dependensi:**
    -   Pastikan Anda berada di direktori utama proyek, lalu jalankan perintah berikut untuk menginstal semua pustaka yang diperlukan:
    ```bash
    pip install -r requirements.txt
    ```

5.  **Jalankan Dasbor Streamlit:**
    -   Navigasi ke folder `dashboard`, lalu jalankan aplikasi Streamlit:
    ```bash
    cd dashboard
    streamlit run dashboard.py
    ```
    -   Setelah perintah di atas dijalankan, dasbor akan otomatis terbuka di browser Anda pada alamat seperti `http://localhost:8501`.

## 🤝 Kontribusi

Proyek ini dibuat sebagai bagian dari submisi kursus Dicoding. Namun, jika Anda memiliki ide untuk visualisasi baru, perbaikan kode, atau saran lainnya, jangan ragu untuk:

1.  **Fork** repository ini.
2.  Buat *branch* baru (`git checkout -b fitur/analisis-produk-terlaris`).
3.  Lakukan perubahan dan **commit** (`git commit -m 'Menambahkan analisis produk terlaris'`).
4.  **Push** ke *branch* Anda (`git push origin fitur/analisis-produk-terlaris`).
5.  Buka **Pull Request**.

---
<div align="center">
  Dibuat oleh Fairuz Alda Perkasa
</div>
````
