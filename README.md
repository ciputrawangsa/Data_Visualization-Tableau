# Visualisasi Data Penjualan📊 - ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

Repositori ini berisi proyek visualisasi data menggunakan **Tableau**. Proyek ini bertujuan untuk mengeksplorasi konsep penting dalam visualisasi data, dengan fokus pada pembuatan representasi visual yang jelas dan berdampak dari data yang tersedia. Repositori ini mencakup file Jupyter Notebook yang menjelaskan proses secara menyeluruh, mulai dari eksplorasi data hingga menghasilkan visualisasi yang informatif. 

## Daftar Isi 🗒️
1. [Link Terkait Project](#link-terkait-project-)
2. [Project Overview](#project-overview-)
3. [Latar Belakang Masalah](#latar-belakang-masalah-)
4. [Problem-Statement](#problem-statement-)
5. [Penjabaran-Masalah](#penjabaran-masalah-)
6. [Metode yang Digunakan](#metode-yang-digunakan-)
7. [Kesimpulan Analisa](#kesimpulan-analisa-)
8. [Rekomendasi](#rekomendasi-)
9. [File yang Tersedia](#file-yang-tersedia-)
10. [Cara Menggunakan Project Ini](#cara-menggunakan-project-ini-)
11. [Dependencies](#dependencies-)
12. [Libraries](#libraries-)
13. [Author](#author-)

## Link Terkait Project ⛓️‍💥

 - [Dataset](https://www.kaggle.com/datasets/kartikeybartwal/ecommerce-product-recommendation-collaborative/data)
 - [Visualisasi Tableau](https://public.tableau.com/views/DataVisualization_17249250434480/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Overview 📝

Dalam proyek ini, kami menggunakan **Tableau** untuk menganalisis dan memvisualisasikan data, dengan tujuan menemukan wawasan serta menyampaikan temuan secara efektif. Beberapa langkah utama yang dicakup dalam proyek ini adalah:

1. **Import Libraries dan Eksplorasi Data**:
    - Memuat dataset dan melakukan eksplorasi awal untuk memahami struktur dan karakteristik data.

2. **Visualisasi**:
    - Membuat berbagai jenis visualisasi seperti diagram batang, peta geografis, dan bagan lainnya untuk menganalisis pola dan tren data.

3. **Analisis**:
    - Menginterpretasikan hasil visualisasi untuk mengidentifikasi insight yang dapat diterapkan pada pengambilan keputusan bisnis atau strategi lain.

## Latar Belakang Masalah 🧐

Pendapatan beberapa bulan terakhir di toko tidak ada kenaikan atau penurunan yang signifikan. Sehingga harus mencari cara untuk meningkatkan pendapatan. Meskipun toko dapat mempertahankan pendapatan pada level yang sama, ketidakmampuan untuk meningkatkan pendapatan dapat mengindikasikan adanya masalah dalam strategi bisnis dan pemasaran. Menemukan strategi yang tepat adalah cara yang bisa dilakukan toko mengatasi stagnansi pendapatan dan mencapai pertumbuhan yang berkelanjutan. 

## Problem Statement √

**Specific:** Pendapatan toko bergerak stagnan, sehingga harus ditingkatkan

**Measurable:** Nilai GMV dari penjualan toko meningkat sebesar 30%

**Achievable:** Pendapatan GMV bisa ditingkatkan dengan meningkatkan nilai rata-rata belanja tiap customer di website

**Relevant:** Meningkatkan rata-rata nilai belanja tiap customer bisa meningkatkan nilai GMV dan berpengaruh dengan peningkatan pendapatan toko

**Timebond:** Target untuk meningkatkan nilai GMV sebesar 30% ditetapkan dengan target waktu selama 1 bulan

**Problem statement:**
Meningkatkan pendapatan toko dengan meningkatkan nilai GMV sebesar 30% selama 1 bulan kedepan. Cara yang bisa dilakukan untuk meningkatkan nilai GMV adalah meningkatkan rata-rata nilai belanja customer.

## Penjabaran Masalah 📋

Berikut adalah penjabaran masalah yang akan dianalisa:
1. Bagaimana proporsi kategori produk pilihan user terhadap total revenue?
2. Lokasi mana yang memberikan revenue terbanyak?
3. Bagaimana proporsi gender terhadap total revenue?
4. Bagaimana proporsi kategori usia user berdasarkan total revenue?
5. Berapa jumlah user yang subscribe newsletter dan tidak subscribe? 
6. Apakah ada korelasi antara income user dengan average order value yang dibelanjakan oleh user?
7. Apakah ada korelasi antara total revenue dengan average order value yang dibelanjakan oleh user?
8. Apakah ada korelasi antara interest user dengan kategori produk?
9. Apakah ada korelasi antara kategori umur dengan kategori produk?
10. Apakah ada perbedaan frekuensi belanja antara user yang subscribe newsletter dan tidak subscribe?
11. Apakah ada perbedaan antara lamanya user terakhir login dari user yang subscribe newsletter dan tidak subscribe?
12. Apakah ada perbedaan nilai belanja rata-rata dari user yang subscribe newsletter dan tidak subscribe newlestter?

## Metode yang Digunakan 🛠️

- Statistik Inferensial
- Statistik Deskriptif
- Visualisasi Data

## Kesimpulan Analisa 🧠

Dari hasil analisa informasi yang bisa didapatkan:

1. Kategori produk Apparel menjadi penghasil revenue terbanyak, kategori Books menjadi penghasil revenue terendah, kategori Home & Kitchen dan kategori produk Electronics menjadi penghasil revenue yang hampir sama
2. User yang berasal dari lokasi Suburban dan Urban menjadi penghasil revenue terbanyak sebesar, terkecilnya user dari lokasi Rual
3. Tidak ada perbedaan total revenue yang signifikan dari pria maupun wanita yang bertransaksi
4. Revenue terbanyak didapatkan dari kategori usia yang bisa dikategorikan usia yang sudah stabil secara finansial
5. Tidak ada perbedaan yang signifikan antara jumlah user yang subscribe newsletter dan yang tidak subscribe newsletter
6. Tidak ada korelasi/hubungan yang signifikan antara average order value user dengan income
7. Ada korelasi/hubungan yang lemah antara average order value user dengan total revenue
8. Tidak ada korelasi/hubungan yang signifikan antara kategori produk dengan interest dan kategori usia
9. Frekuensi belanja user yang subscribe newsletter sama dengan frekuensi belanja user yang tidak subscribe newsletter
10. Lama user terakhir login dari user yang subscribe newsletter sama dengan lama user terakhir login dari user yang tidak subscribe newsletter
11. Nilai rata-rata belanja dari user yang subscribe newsletter sama dengan nilai rata-rata belanja dari user yang tidak subscribe newsletter

Kesimpulannya:

Total revenue yang terbentuk distribusinya hampir merata baik dari gender user, kategori produk pilihan user, lokasi user, status newsletter user, dan status newletter user tidak mempengaruhi behaviour user dalam belanja. Temuan-temuan tersebut masih bisa dimanfaatkan dalam strategi pemasaran dan meningkatkan nilai rata-rata belanja user.

## Rekomendasi 📌

Untuk meningkatkan average order value atau nilai rata-rata belanja user, bisa menggunakan sistem promosi  seperti:

1. Skema bundling promo dari kategori Apparel dengan produk lain
2. Pembelian produk Books akan mendapatkan diskon tambahan 15% untuk pembelian kategori produk lainnya agar bisa meningkatkan penjualan kategori Books.
3. Free shipping untuk user yang berada di lokasi Urban
4. Diskon shipping 10% untuk user yang berada di lokasi Suburban
5. Diskon shipping 30% untuk user yang berada di lokasi Rural
6. Mengkustomisasi produk rekomendasi ketika user login ke akunnya sesuai dengan interest user
7. Mempertahankan katalog produk yang sudah ada, dan jika memungkinkan produk yang unisex khususnya Apparel bisa ditambah
8. Bisa membuat program seasonal diskon, karena bulan September adalah tahun ajaran baru bisa membuat diskon tambahan 10% untuk pembelian kategori produk Books
9. Bisa membuat sistem membership dengan sistem tiering yang memiliki benefit di setiap tiernya
10. Karena status newsletter subscription user tidak memiliki perbedaan dengan frekuensi belanja, lama terakhir user login, dan average order value user, maka kita tetap bisa menjalankan campain email marketing dan optimisasi website serta pengumuman diskon melalui media tersebut.

## File yang Tersedia 📂

- `ciputra_wangsa-datviz.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, visualisasi menggunakan matplotlib dan plotly, insight dari visualisasi, lalu hasil visualisasi yang sama juga dimuat kedalam Tableau.
- `user_personalized_features.csv`: file data mentah dataset
- `cleaned_data.csv`: file dataset yang sudah dilakukan cleaning
  
## Cara Menggunakan Proyek Ini 💻

1. Clone repositori ini ke dalam lokal Anda:
    ```bash
    git clone https://github.com/ciputrawangsa/Data_Visualization-Tableau.git
    ```

2. Jalankan Jupyter Notebook untuk mengikuti alur analisis data:
    ```bash
    jupyter notebook ciputra_wangsa-datviz.ipynb
    ```

3. Tableau digunakan sebagai alat utama untuk membuat visualisasi, bisa dilihat melalui website atau aplikasi.

## Dependencies ⚙️

- ![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 3.12.4
- ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
- ![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)

## Libraries 📚
- Pandas
- Scipy
- Plotly

## Author ✍️
**Ciputra Wangsa**

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ciputra-wangsa/)
