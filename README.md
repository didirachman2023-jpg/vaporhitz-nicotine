# Halaman Meja Vaporhitz Vapestore

Isi folder ini:
- index.html  -> kerangka halaman (biasanya tidak perlu diubah)
- style.css   -> WARNA & GAYA (ubah bagian paling atas)
- config.js   -> ISI: nama, tagline, WiFi, link menu, link Google Maps, Google Form
- app.js      -> logika halaman
- assets/     -> logo.png, menu-1..5.jpg, qrcode.js

## 1. Unggah ke GitHub
1. Masuk ke akun GitHub vaporhitz, klik New repository.
2. Nama repository: vaporhitz-meja  (Public) -> Create repository.
3. Klik "uploading an existing file", seret SEMUA isi folder ini
   (index.html, style.css, config.js, app.js, README.md, dan folder assets) -> Commit changes.
4. Buka Settings -> Pages. Pada "Build and deployment", pilih
   Source: Deploy from a branch, Branch: main, folder: / (root) -> Save.
5. Tunggu 1-2 menit. Alamat halaman:
   https://vaporhitz.github.io/vaporhitz-meja/

## 2. Mengubah isi / tampilan
- Buka file di GitHub -> ikon pensil -> ubah -> Commit changes. Halaman ikut berubah dalam 1-2 menit.
- Ganti logo: unggah logo baru ke folder assets dengan nama logo.png (menimpa yang lama).
- Ganti menu: unggah gambar baru (JPG), lalu sesuaikan daftar di config.js.
- Ganti warna: ubah kode warna di bagian :root pada style.css.

## 3. Penilaian ke Google Form (dashboard = tab Respons)
1. Buat Google Form: pertanyaan "Bintang" (skala linear 1-5) dan "Kesan" (paragraf).
2. Menu titik tiga -> Dapatkan link isi otomatis -> isi contoh -> Dapatkan link -> salin.
3. Dari link itu ambil:
   - bagian sebelum "viewform"  -> ganti "viewform" dengan "formResponse"  (isi form.action)
   - entry.xxxxx untuk bintang   (isi form.entryBintang)
   - entry.yyyyy untuk kesan     (isi form.entryKesan)
4. Simpan di config.js. Penilaian customer langsung masuk ke tab Respons Google Form.
