# 🚀 **Gojek App Review Analysis with NLP**

Analisis review pengguna aplikasi Gojek menggunakan teknik **Natural Language Processing (NLP)** untuk memahami persepsi dan sentimen pelanggan terhadap aplikasi Gojek. Proyek ini merupakan bagian dari pembelajaran portofolio data science.

## 🧠 **Tujuan Proyek**

* Mengumpulkan dan memproses review aplikasi Gojek dari Google Play Store.
* Membersihkan dan mempersiapkan data teks untuk analisis.
* Melakukan visualisasi dan analisis terhadap ulasan pengguna.

## 🛠️ **Tools & Library**

* Python
* Pandas
* Numpy
* Matplotlib & Seaborn (untuk viusualisasi)
* Sastrawi (untuk stemming Bahasa Indonesia)
* Wordcloud
* Google BigQuery

## 🔍 **Tahapan Analisis**

1. **Load Data**  
   * Melakukan scraping data dari Google PlayStore
   * Mengimpor dataset review Gojek dari file CSV

2. **Cleaning Data**
   * Mengecek nilai null
   * Menghapus kolom yang berisi nilai null dan tidak dibutuhkan

3. **Text Preprocessing**  
   * Cleaning Data: case folding, penghapusan URL, dan karakter-karakter lainnya  
   * Normalisasi kata tidak baku 
   * Stopwords removal  
   * Stemming

4. **Text Exploration**
   * Melihat frekuensi kata yang paling sering muncul
   * Melihat frekuensi kata berdasarkan score yang dikelompokkan menjadi 3 kategori sentimen
   * Melihat bobot sentimen
   * Melihat review yang berkualitas vs review yang biasa saja per sentimen

5. **Visualisasi**  
   * Wordcloud  
   * Chart

6. **Google BigQuery**
   * Mengupload data ke Google BigQuery

## 📁 **Struktur File**

* `Portofolio Module 2 - Ayes.ipynb` : Notebook utama yang berisi seluruh proses analisis.
* `gojek_app_review.csv` : Dataset berisi review pengguna aplikasi Gojek.

## 📎 **Link Terkait**
* Google BigQuery dapat dilihat [disini.](https://console.cloud.google.com/bigquery?invt=Abut5g&project=portofolio-module-2&supportedpurview=project&ws=!1m5!1m4!4m3!1sportofolio-module-2!2sehehe!3sgojek_review_app)
* File `gojek_app_review.csv` dapat didownload [disini.](https://drive.google.com/file/d/1xtf8MtCXK-CpZqqVpTrEmB_xvGI0H0LF/view?usp=sharing)

## **Lisensi**
Portofolio ini merupakan projek Bootcamp JCDS 2804 Purwadhika.
