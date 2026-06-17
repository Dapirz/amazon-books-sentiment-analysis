# Analisis Sentimen Amazon Books - DistilBERT + Apache Spark

## Anggota Kelompok
- Daffa Irsandy Putra (103012300338)
- Yudistira Ramadhan S (103012300184)

## Cara Menjalankan

### 1. Persiapan Dataset
- Download dataset dari Kaggle:
  https://www.kaggle.com/datasets/cynthiarempel/amazon-us-customer-reviews-dataset
- File yang digunakan: `amazon_reviews_us_Books_v1_02.tsv`
- Upload file ke Google Drive

### 2. Buka Notebook
- Buka file notebook di Google Colab:
  [Klik di sini untuk buka Colab](https://colab.research.google.com/drive/1RMQ1eWimUopciZRfK1jm274uns6V10vM?usp=sharing)

### 3. Aktifkan GPU
- Runtime → Change runtime type → GPU → Save

### 4. Sesuaikan Path Dataset
- Di bagian "Persiapan Khusus Google Colab", ubah RAW_PATH:
  RAW_PATH = "/content/drive/MyDrive/FOLDER_LU/amazon_reviews_us_Books_v1_02.tsv"

### 5. Run All
- Runtime → Run all
- Estimasi waktu: ~30 menit

## Hasil yang Diharapkan
- Accuracy: 0.9004
- F1-Score: 0.9045
