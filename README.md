Tugas III – Data Preprocessing

Repository ini berisi pengerjaan Tugas III mengenai Preprocessing Dataset Buku, mulai dari dataset awal, kode Python, hingga hasil akhirnya.

Isi Repository

books_dataset.csv — Dataset awal

books_dataset_processed.csv — Dataset setelah preprocessing

feature_engineering.ipynb — Kode preprocessing lengkap

laporan_feature_engineering.docx — Laporan tugas dalam bentuk Word

Tahapan Preprocessing yang Dilakukan
1. Pengecekan Data

  Melihat struktur data (df.info())
  
  Menampilkan data awal (df.head())
  
  Mengecek missing value

2. Cleaning Data

  Mengubah kolom price menjadi tipe numerik
  
  Memastikan data siap digunakan

3. Feature Engineering

  Fitur baru yang dibuat:
  
  title_length → jumlah karakter judul
  
  word_count → jumlah kata
  
  availability_encoded → encoding kolom availability
  
  price_scaled → normalisasi harga
  
  Fitur tambahan berdasarkan kata kunci:
  
  contains_history
  
  contains_love
  
  contains_science

4. Output Akhir

  Dataset bersih disimpan menjadi books_dataset_processed.csv
  
  Semua hasil ditampilkan di notebook dan dijelaskan di laporan
