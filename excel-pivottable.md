
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

    1. Pemahaman teknik dasar penggunaan Pivot Table
    2. Teknik Multy Value Field
    3. Konsep Calculated Field
    4. Teknik Grouping Data
    5. Penggunaan Pivot Chart
    6. Melakukan Filtering data dengan Sliser
    7. Menggunakan Database Dinamis sebagai sumber data dari laporan pivot table

Pada tutorial ini akan fokus membahas point yang pertama, yaitu: Pemahaman teknik dasar penggunaan Pivot Table. Sebagai bahan latihan, silakan download File database penjualan. Kemudian proses menjelaskan materi teknik dasar pivot table menggunakan pendekatan studi kasus.

    Jika diperhatikan pada database yang sudah didownload terdiri dari 213 transaksi penjualan. Transaksi tersebut tercatat berdasarkan kolom ID Order (Order ID),        Nama Produk (Product), Kategori Produk (Category), Jumlah transaksi (Amount), Tanggal Transaksi (Date) dan Negara Terjadinya transaksi (Country).

Jika anda diminta untuk menampilkan informasi penjualan seperti pernyataan di bawah ini, maka penyelesaiannya bisa dengan mengikuti langkah-langkah penggunaan pivot table.

    1. Tampilkan total penjualan masing-masing produk
    2. Urutkan tampilan total penjualan dari besar ke kecil
    3. Ganti perhitungan total penjualan menjadi rata-rata
    4. Tampilkan informasi penjualan produk pada negara tertentu
    5. Tampilkan Penjualan Produk sesuai kriteria kategori yang dipilih.

## Cara Penggunaan Pivot Table

1. Buka file microsoft excel yang akan menjadi database utama.

2. Aktif pada salah satu cell pada data tersebut lalu Klik *Insert*  
<div align="center">
<img width="294" height="307" alt="image" src="https://github.com/user-attachments/assets/7c25cc6a-e234-48dd-803f-1aedb87f0bee" />
</div>

3.Pada group Table, Pilih Pivot Table  
<div align="center">
<img width="303" height="308" alt="image" src="https://github.com/user-attachments/assets/5fd12fa2-f1a1-43e7-912b-dafab4504ca1" />
</div>
            
4. Setelah mengklik pivot table, akan akan mucul kotak dialog Create Pivot Table yang secara otomatis menseleksi table data kita. Hanya saja pastikan yang terseleksi adalah tabel data yang digunakan. Terakhir tekan OK.  
<div align="center">
<img width="290" height="245" alt="image" src="https://github.com/user-attachments/assets/14c8a836-8408-4b2c-b707-efeb9c552bf4" />
</div>  

5. Maka akan tampil worksheet baru untuk menggunakan pivot table.   
<div align="center">
<img width="533" height="285" alt="image" src="https://github.com/user-attachments/assets/775b2365-0f77-487f-8ab4-11f6dfdcbb58" />
</div>  



