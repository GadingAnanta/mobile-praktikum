# Analisis Aplikasi — Pertemuan 1

## Aplikasi yang diamati
Aplikasi Flutter pertama yang dibuat dengan `flutter create` (bernama `aplikasi_pertama`) berbasis template counter bawaan. Aplikasi ini dijalankan melalui emulator Android (Android Studio) di pertemuan 1.

## Pengguna
Saya Agus Adrian Satria Ananta ,Mahasiswa pemula yang baru memulai belajar Flutter; aplikasi ini juga bisa diamati oleh rekan sekelas dan dosen untuk melihat hasil praktik.

## Tiga fitur utama
1. Menampilkan angka counter di tengah layar yang bertambah setiap tombol (+) ditekan.
2. Tombol FAB (Floating Action Button) untuk menaikkan angka counter.
3. Mendukung hot reload dan hot restart, sehingga perubahan kode langsung terlihat tanpa harus membangun ulang aplikasi dari awal.

## Usulan perbaikan
Menambahkan tombol reset yang mengembalikan angka counter ke 0, sehingga pengguna dapat mengulang demo tanpa harus menutup dan menjalankan ulang aplikasi.

## Catatan kendala
Ketika menjalankan `flutter run`, terjadi error terkait Gradle yang kemungkinan besar disebabkan oleh lisensi Android SDK yang belum diterima secara eksplisit. Meskipun sudah dicoba berbagai cara, error tersebut belum terselesaikan pada pertemuan 1. Langkah yang direncanakan untuk penyelesaian di pertemuan berikutnya adalah menjalankan perintah `flutter doctor --android-licenses` dan menyetujui seluruh lisensi, lalu memastikan versi Gradle dan Android SDK kompatibel dengan versi Flutter yang digunakan.