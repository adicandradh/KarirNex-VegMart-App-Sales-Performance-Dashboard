# KarirNex VegMart App Sales Performance Dashboard (Excel)
## 📌 Project Type
Tugas 4 (KarirNex Intensive Bootcamp 2 Weeks - Microsoft Excel)
## 📊 Overview
Project ini merupakan dashboard interaktif berbasis Microsoft Excel yang dikembangkan untuk menganalisis performa penjualan pada aplikasi VegMart.

Fokus utama dari project ini adalah bagaimana data transaksi penjualan dapat diolah menjadi informasi yang terstruktur, konsisten, dan mudah dianalisis. Proses ini mencakup data cleaning, basic data transformation, serta penyusunan metrik bisnis untuk memahami performa penjualan secara menyeluruh.
## 🎯 Objectives
- Menyajikan ringkasan performa penjualan melalui KPI dan visualisasi
- Menganalisis distribusi penjualan berdasarkan platform, kota, dan produk
- Mengevaluasi tren penjualan dari waktu ke waktu
- Mengidentifikasi preferensi pelanggan berdasarkan metode pembayaran dan rating produk
- Menganalisis distribusi order berdasarkan jenis kelamin pelanggan
## 🧠 Data Processing
- Data cleaning untuk memastikan konsistensi format data
- Pembuatan calculated fields
- Ekstraksi informasi waktu dari tanggal transaksi
- Pengelompokkan data ke dalam kategori transaksi
## ⚙️ Business Logic
- Subtotal dihitung berdasarkan perkalian antara harga satuan dan jumlah pembelian (unit price*quantity)
- Discount amount dihitung sebagai persentase diskon terhadap subtotal (subtotal - discount %)
- Grand total merupakan total akhir yang dibayarkan pelanggan, termasuk biaya pengiriman (total sales + shipping fee)
- Kategori transaksi ditentukan berdasarkan nilai total sales menggunakan rumus IFS
## 🛠️ Tools & Skill
- Microsoft Excel
- Data cleaning
- Basic data transformation
- Lookup functions (XLOOKUP)
- Pivot table & pivot chart
- Data visualization & dashboard design
## 🖼️ Preview
<img width="1872" height="892" alt="Sales Performance Dashboard" src="https://github.com/user-attachments/assets/1f2b59d3-abef-48ca-999e-5d2de8ef5587" />

## 📊 Dashboard Highlights
- KPI summary (total sales, total quantity, total orders, discoutn amount, average rating
- Analisis penjualan berrdasarkan platform dan kota
- Tren penjualan bulanan
- Top produk berdasarkan total penjualan dan rating
- Distribusi metode pembayaran dan jenis kelamin pelanggan
- Slicer interaktif (bulan, kota, nama produk, platform, metode pembayaran, dan jenis kelamin) untuk eksplorasi data
## 📈 Key Insights
- Total penjualan mencapai Rp56,4 juta dengan total 2.000 pesanan dan total quantity 2.523,40 kg, menunjukkan volume transaksi yang cukup tinggi selama periode analisis. Namun, rata-rata rating pelanggan sebesar 2,98/5,00 mengindikasikan bahwa penilaian terhadap produk masih berada pada tingkat yang relatif rendah.
- Dari sisi platform, distribusi penjualan relatif merata antar platform, tanpa dominasi yang terlalu signifikan dari satu platform tertentu.
- Berdasarkan wilayah, kota seperti Jakarta dan Pangkalpinang menjadi kontributor utama terhadap total penjualan, menunjukkan adanya konsentrasi permintaan di beberapa wilayah tertentu dibandingkan kota lainnya.
- Tren penjualan bulanan menunjukkan pola fluktuattif namun cenderung meningkat pada akhir periode.
- Dari sisi produk, bawang merah dan cabai rawit merah menjadi produk dengan kontribusi penjualan tertinggi, yang mengindikasikan tingginya permintaan pada kategori produk tersebut.
- Produk dengan rating tertinggi seperti Tomat Merah dan Kangkung menunjukkan penilaian yang sedikit lebih baik dibandingkan produk lainnya, meskipun tidak selalu menjadi penyumbang penjualan tertinggi.
- Distribusi metode pembayaran menunjukkan proporsi yang relatif seimbang antar metode, tanpa perbedaan yang terlalu signifikan antar metode.
- Dari sisi jenis kelamim, mayoritas pesanan berasal dari pelanggan perempuan, yang menunjukkan kontribusi transaksi yang lebih besar dibandingkan pelanggan laki-laki.
