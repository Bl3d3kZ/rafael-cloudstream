# RAFAEL CLOUDSTREAM — Catatan Build dan Repositori

## Status proyek
- Cabang pengembangan: `rafael-branding-v1`.
- Nama aplikasi: RAFAEL CLOUDSTREAM.
- Tema aksen: ungu.
- Terjemahan Indonesia awal tersedia.
- Pengaturan Gradle diringankan untuk komputer RAM 8 GB.
- Build APK stabil sebelumnya berhasil dan sudah diuji dapat dipasang serta dibuka.
- Daftar repositori di bawah adalah sumber ekstensi terpisah; ekstensi tidak digabungkan ke dalam APK.

## Repositori ekstensi yang disiapkan
Tambahkan melalui **Pengaturan / Settings → Extensions / Ekstensi → Add Repository / Tambah Repositori**.

| Nama | URL manifest | Fokus yang dilaporkan |
|---|---|---|
| AnimeX | `https://raw.githubusercontent.com/HatsuneMikuUwU/AnimeX/refs/heads/master/repo.json` | Anime dan donghua, subtitle Indonesia |
| OCE (byimam2nd) | `https://raw.githubusercontent.com/byimam2nd/oce/master/repo.json` | Animasu, Samehadaku, Anichin, donghua dan lainnya |
| TheAlyss Repo | `https://raw.githubusercontent.com/TheAlyss/cloudstream-AlyssRepo/builds/repo.json` | YLnime dan beberapa sumber film/serial Indonesia |
| CloudStream Official Providers | `https://raw.githubusercontent.com/recloudstream/extensions/master/repo.json` | Plugin resmi umum; bukan katalog anime Indonesia utama |

URL manifest diperiksa saat penyusunan dokumen, tetapi isi repo, domain penyedia, dan kompatibilitas plugin dapat berubah sewaktu-waktu. Hanya pasang ekstensi yang sumbernya Anda percaya. Gunakan layanan yang memiliki izin distribusi konten di wilayah Anda.

## Langkah pemasangan
1. Tambahkan satu URL repositori.
2. Tunggu daftar plugin muncul.
3. Cari provider anime yang diinginkan, misalnya Samehadaku atau Animasu.
4. Pasang plugin, lalu kembali ke halaman utama.
5. Pilih provider tersebut dan uji pencarian serta pemutaran.
6. Ulangi untuk repositori berikutnya. Jika plugin dengan nama sama muncul dari beberapa repo, jangan pasang semuanya sekaligus; uji satu versi/sumber dahulu.

## Catatan penting V3
CloudStream memang mendukung banyak repositori sekaligus. Menambahkan repo tidak berarti semua plugin otomatis terpasang atau semua sumber pasti berfungsi. Untuk menjaga APK tetap ringan dan kompatibel, repositori dikelola dari menu Extensions, sedangkan plugin dipasang sesuai kebutuhan. Jangan mengunduh APK/plugin dari mirror tidak dikenal.

## Build di Windows 10
- Gunakan Android Studio yang kompatibel dengan konfigurasi Gradle proyek dan JDK 17.
- Buka folder proyek, tunggu Gradle Sync selesai.
- Pilih Build → Build Bundle(s) / APK(s) → Build APK(s).
- Untuk build otomatis, jalankan workflow **Build RAFAEL CLOUDSTREAM APK** pada branch `rafael-branding-v1`.
- Uji instalasi, navigasi, pencarian provider, dan pemutaran sebelum menyebut build sebagai rilis siap pakai.
