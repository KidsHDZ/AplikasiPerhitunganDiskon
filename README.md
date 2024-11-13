# AppPerhitunganDiskon

`AppPerhitunganDiskon` adalah aplikasi GUI berbasis Java yang dirancang untuk membantu pengguna menghitung diskon pada harga suatu barang dengan memasukkan harga asli, menerapkan persentase diskon, dan menggunakan kupon diskon opsional. Aplikasi ini menyediakan antarmuka yang mudah digunakan untuk melihat harga setelah diskon, persentase penghematan, dan total penghematan.

## Deskripsi

Aplikasi ini memungkinkan pengguna untuk memasukkan harga asli suatu barang dan menerapkan diskon menggunakan slider atau dropdown untuk memilih persentase. Pengguna juga dapat memasukkan kode kupon untuk tambahan diskon. Aplikasi ini akan menghitung dan menampilkan harga akhir setelah diskon serta jumlah penghematan.

## Fitur Utama

1. **Input Harga Asli**: Pengguna dapat memasukkan harga asli barang.
2. **Pemilihan Diskon**: Pengguna dapat memilih persentase diskon menggunakan slider atau memilih nilai yang sudah tersedia dari daftar dropdown.
3. **Kode Kupon**: Opsi untuk memasukkan kode kupon ("10") untuk tambahan diskon 10%.
4. **Perhitungan Otomatis**: Ketika pengguna mengklik tombol "Hitung," aplikasi akan menampilkan harga akhir setelah diskon dan total penghematan.
5. **Penanganan Error**: Memberikan peringatan untuk input yang tidak valid dan menampilkan pesan kesalahan jika angka yang dimasukkan tidak valid.

## Keunggulan

- **Antarmuka yang Mudah Digunakan**: GUI yang sederhana dan intuitif, ideal untuk perhitungan diskon cepat.
- **Feedback Real-Time**: Slider dan dropdown tersinkronisasi, memungkinkan pengguna untuk melihat diskon yang diperbarui secara instan.
- **Output Perhitungan yang Terperinci**: Hasil ditampilkan secara terorganisir, menunjukkan semua data relevan (harga asli, persentase diskon, harga akhir, dan penghematan).
- **Pesan Error**: Memvalidasi input untuk memastikan data yang salah tidak mengganggu perhitungan.

## Cara Menjalankan Aplikasi

1. **Pra-syarat**: Pastikan Anda sudah memiliki JDK dan IDE Java yang kompatibel (seperti NetBeans atau IntelliJ IDEA) terpasang.
2. **Kompilasi dan Jalankan**:
   - Buka proyek di IDE Anda.
   - Jalankan kelas `AppPerhitunganDiskon` untuk memulai aplikasi.
3. **Menggunakan Aplikasi**:
   - Masukkan harga asli di kolom `Harga Asli`.
   - Pilih persentase diskon menggunakan slider atau menu dropdown.
   - Opsional, masukkan kode kupon ("10") di kolom `Kupon Diskon` untuk diskon tambahan 10%.
   - Klik tombol "Hitung" untuk menghitung harga akhir dan penghematan.

## Contoh Penggunaan

1. Masukkan "100000" sebagai harga asli.
2. Atur slider ke 20% atau pilih "20%" dari dropdown.
3. Masukkan "10" di kolom kupon.
4. Klik "Hitung" untuk melihat perhitungan harga akhir dan penghematan.

## Catatan

- Untuk aplikasi ini, input kode kupon yang valid adalah "10" (memberikan diskon tambahan 10%).
- Jika kode kupon yang tidak valid dimasukkan, aplikasi akan menampilkan pesan peringatan.

## Pembuat Aplikasi
Muhammad Ikhya 2210010405

## Demo
![Demo GIF](img/Diskon.gif)
