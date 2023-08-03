# Deskripsi Proyek:
Proyek ini menganalisis tentang jumlah barang yang berhasil dipesan setiap bulan dan setiap waktunya. Setelah data dianalisis, akan dibuat model untuk memprediksi jumlah barang yang akan dibeli pada setiap bulan dan setiap 1 jam berikutnya.

# Dataset:
* invoiceNo: Invoice number Angka 6 digit yang secara unik menandakan setiap transaksi. Jika kode dimulai dengan huruf C, itu menandakan pembatalan
* StockCode: Product (item) code. Nominal. Angka 5 digit yang secara unik menandakan setiap produk.
* Description: Product (item) name.  
* Quantity: Jumlah barang yang dibeli pertransaksi.
* InvoiceDate: hari dan jam kapan transaksi dilakukan. 
* UnitPrice: Unit price. Numeric. harga produk dalam sterling.
* CustomerID: Customer number. Nominal. Angka 5 digit yang menandakan setiap customer. 
* Country: Country name. Nominal. Nama negara di mana kostumer tinggal.

# Library:
* _pandas_
* _numpy_
* _statsmodel_
* _sklearn_
* _lightgbm_
