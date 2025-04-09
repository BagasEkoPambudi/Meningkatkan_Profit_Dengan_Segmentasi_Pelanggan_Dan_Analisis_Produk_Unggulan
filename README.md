# Meningkatkan_Profit_Dengan_Segmentasi_Pelanggan_Dan_Analisis_Produk_Unggulan
File Pendukung
* Dataset : https://drive.google.com/drive/folders/1YfcqdCJSwmqaYeSy2uS0H7eUt4cRxxuf?usp=sharing
* Dashboard : https://public.tableau.com/shared/HWMD6X96R?:display_count=n&:origin=viz_share_link

# Latar belakang
Dalam dunia ritel modern, terutama pada sektor supermarket, persaingan semakin ketat dan kebutuhan untuk memahami perilaku pelanggan menjadi sangat penting. Tidak cukup hanya menarik pelanggan baru namun mempertahankan dan memaksimalkan potensi pelanggan yang sudah ada justru menjadi kunci dalam meningkatkan profitabilitas bisnis.

Salah satu pendekatan yang dapat digunakan untuk memahami perilaku pelanggan adalah segmentasi berbasis data. Dengan melakukan segmentasi, perusahaan dapat mengelompokkan pelanggan ke dalam beberapa kategori berdasarkan karakteristik tertentu, sehingga strategi pemasaran yang dijalankan dapat lebih terarah dan efektif. Dalam hal ini, metode LRFM (Length, Recency, Frequency, Monetary) merupakan salah satu pendekatan segmentasi yang sangat relevan karena mampu menggambarkan nilai dan kebiasaan belanja pelanggan secara menyeluruh.

* Length  menunjukkan berapa lama pelanggan telah bertransaksi dengan perusahaan.

* Recency menunjukkan kapan terakhir kali pelanggan melakukan pembelian.

* Frequency menunjukkan seberapa sering pelanggan berbelanja.

* Monetary menunjukkan seberapa besar uang yang dikeluarkan oleh pelanggan.

Dengan mengelompokkan pelanggan berdasarkan keempat aspek ini, perusahaan dapat mengidentifikasi segmen pelanggan yang memiliki nilai tinggi, pelanggan potensial, maupun pelanggan yang berisiko churn. Dari sini, strategi personalisasi pemasaran dan promosi bisa disesuaikan untuk masing-masing segmen.

Di sisi lain, supermarket juga memiliki sejumlah produk unggulan yang menjadi kontributor penting terhadap penjualan. Dengan mengaitkan segmentasi pelanggan menggunakan LRFM dan perilaku pembelian terhadap produk unggulan, perusahaan dapat lebih tepat sasaran dalam menetapkan strategi promosi, bundling, atau loyalitas.

# Hasil Analisa
### Segmentasi Pelanggan dengan Pendekatan LRFM
1. Pelanggan berhasil dikelompokkan ke dalam 4 segmen: 
* Loyal High-Value
* Potential Loyalist
* Mid Value
* Low Value
2. Dengan pendekatan ini, ditemukan bahwa:
* Segmen Loyal High-Value dan Potential Loyalist memiliki pengeluaran rata-rata paling tinggi, khususnya pada produk-produk premium seperti Wine dan Meat.
* Segmentasi berbasis LRFM terbukti memberikan dampak terhadap pemahaman perilaku pembelian pelanggan, yang dapat dimanfaatkan untuk strategi peningkatan profit, seperti bundling, promosi spesifik segmen, atau retensi pelanggan bernilai tinggi.
3. Dari hasil uji Kruskal-Wallis terhadap pengeluaran produk seperti Spend_Wine, didapatkan bahwa nilai hasil dari
uji statistik : 1606.56, p-value: 0.0000 .
Artinya, terdapat perbedaan signifikan dalam pengeluaran produk antar segmen pelanggan.
Maka, segmentasi LRFM memang memengaruhi penjualan produk unggulan.

### Berdasarkan Analisis Produk Unggulan per Segmen
1. Segmen Loyal High-Value memiliki rata-rata pengeluaran tertinggi untuk produk:
* Spend_Wine
* Spend_Gold 
* Spend_Meat
2. Segmen Mid Value dan Potential Loyalist memiliki kontribusi tinggi terhadap produk:
* Spend_Fruits 
* Spend_Meat
3. Segmen Low Value memiliki kontribusi pengeluaran yang rendah di semua produk.
