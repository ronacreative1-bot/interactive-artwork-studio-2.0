# Atelier — Real-Time Interactive Artwork Studio

Aplikasi web untuk membuat generative dan interactive artwork secara langsung. Dibuat dengan HTML, CSS, dan JavaScript murni; tidak membutuhkan framework, server, API key, atau proses build.

## Fitur

- Kanvas interaktif dengan mouse dan layar sentuh
- Empat alat: Kuas Neon, Partikel, Gelombang, dan Geometri
- Kontrol warna, ukuran, intensitas, latar, dan kecepatan
- Simetri horizontal
- Animasi otomatis (Auto Art)
- Undo, bersihkan kanvas, pause/resume
- Ekspor karya menjadi PNG
- Layout responsif untuk desktop dan ponsel

## Menjalankan di komputer

1. Unduh atau clone repository ini.
2. Buka folder proyek.
3. Buka `index.html` menggunakan browser modern.

Tidak ada instalasi dependency.

## Publikasikan melalui GitHub Pages

1. Buat repository baru di GitHub, misalnya `interactive-artwork-studio`.
2. Unggah `index.html`, `README.md`, dan `.gitignore` ke repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
6. Tunggu proses deployment selesai. GitHub akan menampilkan alamat website pada bagian Pages.

## Struktur proyek

```text
interactive-artwork-studio/
├── index.html
├── README.md
└── .gitignore
```

## Catatan

- Website ini berjalan sepenuhnya di browser; artwork tidak dikirim ke server.
- Tombol Export PNG menyimpan hasil kanvas yang sedang tampil.
- Untuk pengalaman terbaik, gunakan browser versi terbaru.
