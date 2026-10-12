# Kertas Studio

Aplikasi web untuk mengubah teks dan dokumen menjadi PDF atau membuat kode QR yang dapat diunduh sebagai PNG. Semua pemrosesan dilakukan di browser.

## Menjalankan aplikasi

```sh
npm install
npm run dev
```

## Publikasi di Netlify

1. Push proyek ini ke repository GitHub.
2. Di Netlify, pilih **Add new site → Import an existing project** lalu hubungkan repository tersebut.
3. Netlify membaca `netlify.toml` secara otomatis. Konfigurasi build menggunakan `npm run build` dan folder publikasi `dist`.

Untuk memeriksa hasil build secara lokal:

```sh
npm run build
npm run preview
```

## Fitur

- Tulis atau edit teks sebelum mengekspor PDF ukuran A4.
- Unggah file TXT, Markdown, atau DOCX untuk diubah menjadi PDF.
- Buat kode QR dari URL atau teks biasa dan unduh sebagai PNG.
