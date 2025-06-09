# 📊 Marketing Campaign Optimization — iFood (Project Dummy)

Halo! Ini adalah proyek portofolio saya sebagai seorang data analyst, yang berfokus pada bagaimana data dapat dimanfaatkan untuk mengoptimalkan hasil kampanye marketing di sebuah perusahaan retail makanan bernama **iFood** (nama fiktif).

---

## 🧠 Latar Belakang

iFood merupakan perusahaan ritel makanan yang menjual lima kategori utama produk: *wines*, *rare meats*, *exotic fruits*, *special fish*, dan *sweet products*. Setiap kategori memiliki dua kelas: *gold* dan *regular*. Penjualannya dilakukan melalui tiga kanal utama: *physical stores*, *catalogs*, dan *company's website*.

Selama tiga tahun terakhir, iFood mengalami pertumbuhan pendapatan yang sehat. Namun, proyeksi tiga tahun ke depan menunjukkan tren yang kurang menggembirakan. Salah satu strategi yang diambil adalah meningkatkan performa kampanye marketing, terutama dengan pendekatan berbasis data (*data-driven decision making*).

---

## 🎯 Tujuan Proyek

Tujuan utama proyek ini adalah untuk **mengembangkan model prediktif** yang dapat mengidentifikasi pelanggan dengan probabilitas tinggi untuk merespons kampanye produk baru yang akan diluncurkan bulan depan. Dengan informasi tersebut, tim marketing dapat menyusun strategi kampanye yang lebih tepat sasaran, efisien, dan berpotensi menghasilkan profit yang lebih tinggi.

---

## 🛠️ Pendekatan dan Metodologi

### 1. Data Collection
Saya menggunakan data pelanggan yang sudah tersedia di perusahaan. Sebanyak **2.240 pelanggan** dipilih secara acak dan diberikan penawaran kampanye produk baru. Hasil dari kampanye ini akan digunakan untuk melatih model prediktif.

### 2. Exploratory Data Analysis (EDA)
Saya melakukan EDA untuk memahami kualitas dan struktur data. Beberapa hal yang dianalisis mencakup:
- Pengecekan tipe data yang tidak sesuai
- Variasi input (contoh: `$1.5` vs `1.5`)
- Identifikasi missing values, duplikasi, dan outlier
- Distribusi nilai-nilai penting dan kelogisannya

### 3. Feature Engineering dan Selection
Beberapa fitur pelanggan diolah ulang agar lebih representatif. Pemilihan fitur penting dilakukan menggunakan analisis statistik dan teknik interpretasi model.

### 4. Modeling dan Evaluasi
Saya membangun model klasifikasi untuk memprediksi siapa saja yang kemungkinan besar akan merespons kampanye. Model dievaluasi menggunakan metrik seperti akurasi, precision, recall, dan f1-score.

### 5. Interpretasi dan Rekomendasi Bisnis
Saya mengidentifikasi pola-pola penting dari hasil model dan menyusunnya menjadi insight yang dapat ditindaklanjuti oleh tim marketing.

---

## 💡 Temuan Awal

Sebagai bagian dari analisis, saya menemukan bahwa beberapa faktor seperti **jumlah pengeluaran sebelumnya**, **recency (waktu sejak transaksi terakhir)**, serta **riwayat campaign sebelumnya**, memiliki kontribusi signifikan terhadap kemungkinan keberhasilan kampanye. Insight lengkap dan interpretasi model disediakan pada notebook terkait.

---

## 📌 Catatan Tambahan
Proyek ini merupakan proyek dummy yang saya buat untuk menunjukkan kemampuan analisis data dan pemodelan prediktif dalam konteks nyata.

Nama perusahaan, produk, dan data bersifat fiktif dan digunakan hanya untuk kepentingan pembelajaran.

## Terima Kasih!
Terima kasih telah mengunjungi proyek ini. Silakan jelajahi isi repositori ini untuk eksplorasi lebih lanjut. Jika kamu memiliki masukan atau pertanyaan, feel free untuk membuka issue atau menghubungi saya melalui GitHub!
