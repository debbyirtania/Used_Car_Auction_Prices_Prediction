## Dataset
Industri mobil bekas merupakan suatu industri yang menarik untuk diamati pertumbuhannya disamping itu harga mobil terus berubah tergantung berbagai faktor. Di bawah ini adalah penjelasan atas fitur/kolom dari data mobil bekas yang paling penting untuk dipahami ketika akan membeli mobil bekas di lelang:

- `Year` : Tahun produksi mobil
- `Make` : Merk/pabrikan mobil
- `Model` : Model/jenis mobil dari brand tertentu. cth: avanza, innova, mobilio, dll
- `Trim` : Jenis mobil berbeda dari model brand tertentu
- `Body` : Tipe/Jenis dari mobil cth: sedan, suv, dll
- `Transmission` : Jenis transmisi dari mobil yaitu manual dan automatic
- `VIN` : Vehicle identification number/Plat Nomor Mobil
- `State` : Daerah dimana mobil dilelang
- `Condition` : Kondisi mobil saat dilakukan lelang mulai dari 1 - 5
- `Odometer` : Jarak tempuh dari mobil sejak keluar pabrik
- `Color` : Warna exterior mobil
- `Interior` : Warna interior mobil
- `Seller` : Penjual mobil/dealer
- `mmr` : Manhiem market record/harga estimasi market price
- `sellingprice` : Harga mobil yang terjual pada saat lelang
- `saledate` : tanggal mobil terjual di lelang

## Problem Statement:
Salah satu bagian penting dari industri used-car adalah kesesuaian harga jual kendaraan dengan kondisi dan spesifikasi.
Apakah harga yang kita tentukan dalam penjualan unit sudah sesuai?
Seberapa besar odometer mempengaruhi harga jual?
Seberapa kondisi mempengaruhi harga jual?

## Goal
Membuat model dan prediksi yang dapat digunakan untuk menentukan harga mobil bekas secara otomatis, berdasarkan spesifikasi dan kondisi yang di-input oleh user. Sehingga proses penilaian & penentuan harga bisa menjadi lebih cepat & akurat sehingga mendapatkan keuntungan maksimal

## Objective
Membuat model untuk memprediksi harga secara otomatis
Memberikan estimasi harga yang sesuai dalam pembelian unit kendaraan berdasarkan spesifikasi & kondisi

## Business Metrics
Kenaikan Revenue atas selisih antara MMR dengan Selling Price


