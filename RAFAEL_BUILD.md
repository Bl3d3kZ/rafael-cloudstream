# RAFAEL CLOUDSTREAM — Catatan Build

## Status
Ini adalah tahap awal kustomisasi merek di branch `rafael-branding-v1`. ID paket CloudStream sengaja dipertahankan agar kompatibilitas ekstensi tetap terjaga. APK belum dibangun atau diuji pada perangkat.

## Kustomisasi awal
- Nama aplikasi: RAFAEL CLOUDSTREAM
- Warna aksen: ungu
- Resource terjemahan Indonesia awal: `app/src/main/res/values-id/strings.xml`
- Pengaturan Gradle diringankan untuk komputer RAM 8 GB.

## Menambahkan ekstensi AnimeX
Setelah aplikasi terpasang:
1. Buka Pengaturan / Settings.
2. Masuk ke Extensions / Ekstensi.
3. Pilih Add Repository / Tambah Repositori.
4. Tambahkan URL manifest AnimeX berikut:

`https://raw.githubusercontent.com/HatsuneMikuUwU/AnimeX/refs/heads/master/repo.json`

5. Cari dan pasang provider Samehadaku dari daftar ekstensi AnimeX, jika tersedia dan masih berfungsi.

AnimeX adalah repositori ekstensi terpisah; perubahan branding aplikasi ini tidak menyalin atau menggabungkan kode provider ke APK. Ketersediaan dan fungsi sumber dapat berubah.

## Build di Windows 10
- Gunakan Android Studio versi yang kompatibel dengan konfigurasi Gradle proyek.
- Pasang JDK 17 sesuai kebutuhan proyek.
- Buka folder proyek, tunggu Gradle Sync selesai, lalu jalankan Build > Build Bundle(s) / APK(s) > Build APK(s).
- Uji APK pada perangkat Android sebelum distribusi.

Jangan menganggap APK siap rilis sampai proses build berhasil dan pengujian instalasi, navigasi, ekstensi, serta pemutaran selesai.
