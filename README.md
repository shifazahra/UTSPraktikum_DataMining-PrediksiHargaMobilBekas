# 🚗 Prediksi Harga Mobil Bekas Menggunakan Linear Regression

Proyek ini dibuat untuk memprediksi harga mobil bekas berdasarkan berbagai fitur seperti tahun, nama, jenis bahan bakar, dan spesifikasi mesin. Model yang digunakan adalah **Linear Regression**, salah satu algoritma dasar dalam data mining untuk analisis hubungan antar variabel.

---

## 📁 Struktur Proyek
📦 used-car-price-prediction
├── used_cars_price_fiks.csv # Dataset utama
├── PPT Proyek_Prediksi harga mobil bekas.pdf # File presentasi proyek
├── notebook.ipynb # Notebook berisi kode dan analisis
└── README.md # Deskripsi proyek

---

## 📊 Dataset
Dataset yang digunakan berasal dari sumber publik di GitHub:  
🔗 [used_cars_price_fiks.csv](https://raw.githubusercontent.com/FarrelllAdityaaa/dataset-uts-datamining/refs/heads/main/used_cars_price_fiks.csv)

Dataset ini berisi informasi tentang berbagai mobil bekas dengan kolom seperti:
- `Name` - nama mobil
- `Location` - lokasi mobil
- `Year` - tahun pembuatan
- `Kilometers_Driven` - jarak tempuh
- `Fuel_Type` - jenis bahan bakar
- `Transmission` - tipe transmisi
- `Owner_Type` - status kepemilikan
- `Mileage` - konsumsi bahan bakar
- `Engine` - kapasitas mesin
- `Power` - tenaga mesin
- `Seats` - jumlah kursi dalam mobil
- `Price` - harga mobil

---

## ⚙️ Tahapan Proyek
1. **Import dataset & eksplorasi data**
2. **Pre-Processing** (Profiling data, EDA, Data Cleaning, Data Trasnformations, Data Final)
3. **Split data** menjadi train & test
4. **Penerapan Linear Regression**
5. **Evaluasi model** menggunakan:
   - R² = 0.75 → Model mampu menjelaskan 75% variasi harga mobil  
   - MAE = 2.97 → Rata-rata selisih prediksi dengan harga asli sekitar 3 satuan
   - MSE = 26.27 → Ini angka error yang dihitung dengan kuadrat, jadi lebih besar nilainya 
   - RMSE = 5.12 → Model salah prediksi sekitar 5 satuan harga secara rata-rata

---

## 📈 Hasil dan Kesimpulan
Model Linear Regression mampu memberikan hasil yang cukup baik, terutama pada mobil dengan harga rendah hingga menengah. Namun, untuk mobil dengan harga tinggi, akurasinya menurun.  
Secara keseluruhan, model ini cocok untuk estimasi awal harga mobil bekas berdasarkan data spesifikasi dan kondisi kendaraan.

---

## 👩‍💻 Oleh:
**Shifa Fanisatuz Zahra**  
Program Studi Informatika – Universitas Singaperbangsa Karawang (UNSIKA)

---

## 🌐 Tautan Pendukung
- 📄 [Presentasi Proyek (PDF)](./PPT_Proyek_Prediksi-harga-mobil-bekas.pdf)  
- 📊 [Dataset CSV](./used_cars_price_fiks.csv)
