# FINAL PROJECT 4 - Clustering

Dataset yang digunakan untuk analisis adalah CCData, yang tersedia di https://www.kaggle.com/datasets/arjunbhasin2013/ccdata. Dataset ini mengumpulkan informasi tentang penggunaan kartu kredit oleh sebanyak 9000 pemegang kartu kredit aktif dalam kurun waktu 6 bulan terakhir.

Hal yang akan dianalisis dalam dataset ini adalah perilaku penggunaan kartu kredit oleh pelanggan. Data-data seperti saldo kartu kredit, frekuensi pembelian, jumlah pembelian, tarik tunai, batas kredit, dan pola pembayaran akan dipelajari untuk mendapatkan wawasan tentang kebiasaan penggunaan kartu kredit dan pola perilaku pelanggan.


Berikut adalah penjelasan singkat tentang kolom-kolom yang ada dalam dataset CCData:

* CUST_ID: ID unik untuk setiap pemegang kartu kredit.

* BALANCE: Saldo yang tersisa pada kartu kredit.

* BALANCE_FREQUENCY: Frekuensi pembaruan saldo, diukur dari 0 hingga 1. Nilai 1 menunjukkan pembaruan saldo yang sering, sementara nilai 0 menunjukkan pembaruan saldo yang jarang.

* PURCHASES: Jumlah total pembelian yang dilakukan dengan kartu kredit.

* ONEOFF_PURCHASES: Jumlah total pembelian satu kali (one-off) yang dilakukan dengan kartu kredit.

* INSTALLMENTS_PURCHASES: Jumlah total pembelian dengan angsuran yang dilakukan dengan kartu kredit.

* CASH_ADVANCE: Jumlah total penarikan uang tunai dengan kartu kredit.

* PURCHASES_FREQUENCY: Frekuensi pembelian, diukur dari 0 hingga 1. Nilai 1 menunjukkan frekuensi pembelian yang tinggi, sementara nilai 0 menunjukkan frekuensi pembelian yang rendah.

* ONEOFF_PURCHASES_FREQUENCY: Frekuensi pembelian satu kali (one-off), diukur dari 0 hingga 1. Nilai 1 menunjukkan frekuensi pembelian satu kali yang tinggi, sementara nilai 0 menunjukkan frekuensi pembelian satu kali yang rendah.

* PURCHASES_INSTALLMENTS_FREQUENCY: Frekuensi pembelian dengan angsuran, diukur dari 0 hingga 1. Nilai 1 menunjukkan frekuensi pembelian dengan angsuran yang tinggi, sementara nilai 0 menunjukkan frekuensi pembelian dengan angsuran yang rendah.

* CASH_ADVANCE_FREQUENCY: Frekuensi penarikan uang * tunai, diukur dari 0 hingga 1. Nilai 1 menunjukkan frekuensi penarikan uang tunai yang tinggi, sementara nilai 0 menunjukkan frekuensi penarikan uang tunai yang rendah.

* CASH_ADVANCE_TRX: Jumlah transaksi penarikan uang tunai.

* PURCHASES_TRX: Jumlah transaksi pembelian.

* CREDIT_LIMIT: Batas kredit yang ditetapkan pada kartu kredit.

* PAYMENTS: Jumlah total pembayaran yang dilakukan oleh pemegang kartu kredit.

* MINIMUM_PAYMENTS: Jumlah pembayaran minimum yang harus dibayarkan setiap bulan.

* PRC_FULL_PAYMENT: Persentase pembayaran penuh yang dilakukan oleh pemegang kartu kredit.

* TENURE: Jangka waktu pemegang kartu kredit (dalam bulan).