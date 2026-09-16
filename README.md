# Proyek Pemrograman Mobile

## Deskripsi
Aplikasi Flutter pertama (aplikasi_pertama) berbasis template counter bawaan yang dibuat sebagai latihan dasar pemrograman mobile di pertemuan 1.

## Pengembang
Nama panggilan / akun GitHub: GadingAnanta

## Status
Proyek awal perkuliahan.

## Tujuan
Membuat dan menjalankan aplikasi Flutter pertama untuk memahami alur kerja dasar pengembangan mobile: menulis kode Dart, membangun UI dengan widget, serta menjalankan aplikasi pada emulator atau perangkat Android.

## Rencana Fitur
1. Menampilkan angka counter di tengah layar yang bertambah setiap tombol (+) ditekan.
2. Tombol reset untuk mengembalikan angka counter ke 0.
3. Hot reload dan hot restart sehingga perubahan kode langsung terlihat tanpa membangun ulang aplikasi.

## Cara Menjalankan

### Prasyarat
- Flutter SDK terpasang
- Android Studio dengan Android SDK dan emulator
- VS Code atau IDE lain sebagai editor

### Langkah-langkah
1. Clone repository: git clone https://github.com/GadingAnanta/mobile-praktikum.git
2. Masuk ke folder proyek: cd mobile-praktikum
3. Install dependensi: flutter pub get
4. Jalankan aplikasi: flutter run

### Catatan Kendala
Pada pertemuan 1, muncul error terkait Gradle yang kemungkinan disebabkan oleh lisensi Android SDK yang belum diterima. Langkah penyelesaian yang direncanakan:
1. Jalankan `flutter doctor --android-licenses` dan setujui seluruh lisensi.
2. Pastikan versi Gradle dan Android SDK kompatibel dengan versi Flutter yang digunakan.