
<img width="718" height="473" alt="image" src="https://github.com/user-attachments/assets/c774941e-d083-43d7-8e54-f5777430c71d" />


# Deep Dive into Pivot Table  

Pivot Table umumnya adalah laporan berbentuk tabel yang dalam waktu singkat bisa menampilkan ringkasan dari jumlah data besar kedalam bentuk atau orientasi berbeda serta mampu melakukan kalkulasi pada setiap item yang dibutuhkan.  

Berkaitan dengan menampilkan data berdasarkan kriteria tertentu, microsoft Excel sebenarnya sudah menyediakan fasilitas seperti Filter untuk dapat melakukan filtering pada table. Tetapi, pada kasus tertentu fitur ini terkadang belum terlalu efektif untuk menampilkan informasi secara cepat. Sehingga, keterbatasan itu bisa ditanggulangi dengan menggunakan kemampuan Pivot Table.

## Istilah - Istilah pada Pivot Table

Sebelum memasuki tahapan bagaimana caranya membuat pivot table, ada baiknya kita memahami istilah – istilah yang terdapat pada pivot table, seperti:

    - Field, Field adalah nama – nama kolom pada data yang kita miliki.
    - Rows, Rows digunakan untuk menampilkan data secara vertical
    - Columns, Columns sendiri digunakan untuk menampilkan data secara horizontal.
    - Value, Value adalah nilai dari data.
    - Filter, Filter digunakan untuk melakukan filtering terhadap data sesui kebutuhan.  

## Tahapan Belajar Pivot Table

Saat mempelajari teknik penggunaan pivot table, ada beberapa tahapan yang harus dipahami dari paling dasar sampai ke tahap mahir, misalnya:

    Pemahaman teknik dasar penggunaan Pivot Table
    Teknik Multy Value Field
    Konsep Calculated Field
    Teknik Grouping Data
    Penggunaan Pivot Chart
    Melakukan Filtering data dengan Sliser
    Menggunakan Database Dinamis sebagai sumber data dari laporan pivot table

Pada tutorial ini akan fokus membahas point yang pertama, yaitu: Pemahaman teknik dasar penggunaan Pivot Table. Sebagai bahan latihan, silakan download File database penjualan. Kemudian proses menjelaskan materi teknik dasar pivot table menggunakan pendekatan studi kasus.

    Jika diperhatikan pada database yang sudah didownload terdiri dari 213 transaksi penjualan. Transaksi tersebut tercatat berdasarkan kolom ID Order (Order ID),        Nama Produk (Product), Kategori Produk (Category), Jumlah transaksi (Amount), Tanggal Transaksi (Date) dan Negara Terjadinya transaksi (Country).

Jika anda diminta untuk menampilkan informasi penjualan seperti pernyataan di bawah ini, maka penyelesaiannya bisa dengan mengikuti langkah-langkah penggunaan pivot table.

    Tampilkan total penjualan masing-masing produk
    Urutkan tampilan total penjualan dari besar ke kecil
    Ganti perhitungan total penjualan menjadi rata-rata
    Tampilkan informasi penjualan produk pada negara tertentu
    Tampilkan Penjualan Produk sesuai kriteria kategori yang dipilih

