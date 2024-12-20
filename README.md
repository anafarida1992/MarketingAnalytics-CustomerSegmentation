**Customer Segmentation for Marketing Campaign Retail Company (Data Insight and Modeling with Python)**\
\
**A. Background:**\
•	Sebuah perusahaan retail menjual produk regular dan gold berupa wines, fruits, meat, fish dan sweet products.\
•	Perusahaan ini memiliki 3 sales channels yaitu catalogs, physical stores dan company site.\
•	Perusahaan ini akan melakukan direct marketing campaign kepada registered customer untuk produk baru yang akan dirilis bulan depan.

**B. Goal:**\
•	Membuat predictive model dengan cara memahami karakteristik socio-demographic firmographic customer yang berpotensi untuk membeli produk baru tersebut. (customer segmentation to create targeted advertising campaigns).\
•	Untuk meningkatkan pendapatan (revenue) dan keuntungan (profit) dari penjualan (sales) produk serta mengurangi biaya (cost) marketing.\
\
**C. Insights:**\
Karakteristik customer yang cenderung menerima / merespon positif campaign:\
•	Berusia 30 hingga 45.\
•	Berpendidikan Graduation (S1) dan PhD (S3).\
•	Berpenghasilan $40,000 - $80,000.\
•	Berstatus Single dan Married.\
•	Tidak memiliki anak (0) / sedikit anak (1 anak).\
•	Tahun Membership (2012).\
•	Last transaction / tanggal pembelian terakhir (kurang dari 30 hari).\
•	Transaksi Pembelian $1,000-$2,000.\
•	Jumlah transaksi pembelian 10-25 kali.\
•	Negara asal SP (Spain) dan ME(Mexico).\
•	Membeli Wines dan MeatProducts.\
•	Membeli lewat Catalog dan Web.\
\
**D. Predictive Model:**\
•	Modelling menggunakan Logistic Regression (probabilitas akurasi 0.746 atau 74.6%) dan Random Forest (probabilitas akurasi 0.882 atau 88.2%).\
•	Performance Stability Check dengan menggunakan Model Random Forest karena probabilitas akurasi lebih tinggi dibandingkan Logistic Regression.\
•	Model Random Forest diterapkan pada data lain, dihasilkan probabilitas akurasi 0.878 atau 87.8%.\
•	Perbedaan probabilitas akurasi yang tidak jauh mengindikasikan bahwa performance model cukup stabil untuk dapat diaplikasikan dalam memprediksi probabilitas respon ratusan ribu registered customer lainnya.
