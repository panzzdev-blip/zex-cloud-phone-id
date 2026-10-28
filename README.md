# ZEX Cloud Phone ID — UI Prototype

Prototype website responsif bertema Black + Neo Green.

## Fitur yang sudah ada
- Loading screen dan animasi tombol/kartu.
- Dashboard perangkat, pencarian, filter status, pilihan kolom, refresh.
- Tambah kartu perangkat demo dan simulasi start/stop.
- Halaman Beli, Hadiah/Redeem, dan Profil.
- Profil lokal (username, avatar inisial, bio, warna aksen) tersimpan di browser.
- Dialog login/daftar dan tombol Google sebagai placeholder UI.
- Responsif untuk layar HP dan desktop.

## Batasan penting
Ini **prototype frontend**, bukan layanan cloud phone sungguhan. Data perangkat dan profil disimpan di browser menggunakan `localStorage`. Tombol login/daftar/Google belum terhubung ke autentikasi. Kartu perangkat tidak membuat Android virtual; untuk itu perlu backend, server/penyedia Android virtual, dan streaming layar.

## Menjalankan dari HP Android
1. Ekstrak ZIP.
2. Buka `index.html` di browser untuk melihat prototype.
3. Untuk GitHub Pages: buat repository baru, unggah `index.html` sebagai file root, lalu aktifkan **Settings → Pages → Deploy from a branch → main / root**.
4. Setelah deploy, tes website dari browser HP.

Termux bisa dipakai untuk mengelola Git dan mengunggah source, tetapi hosting website biasanya lebih mudah melalui GitHub Pages. Jangan memasukkan kredensial asli ke form demo.

## Struktur
- `index.html` — seluruh UI, CSS, dan JavaScript dalam satu file.
- `README.md` — panduan penggunaan.
