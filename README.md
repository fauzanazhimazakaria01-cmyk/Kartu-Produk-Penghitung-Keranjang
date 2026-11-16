# Kartu-Produk-Penghitung-Keranjang
Menggunakan CSS Grid (repeat(auto-fit, minmax(280px, 1fr))) agar susunan kartu &lt;article> otomatis menyesuaikan lebar layar. Tombol tambah memicu JavaScript untuk memperbarui angka keranjang secara langsung dan memberi umpan balik visual sementara pada tombol.
# Implementasi Komponen Dasar Antarmuka Web

Proyek ini merupakan implementasi dari wireframe Tugas 1 menggunakan HTML5 semantik, CSS3 murni (dengan *custom properties*), dan Vanilla JavaScript tanpa *framework* eksternal.

## Komponen yang Diimplementasikan
1. **Header & Navigasi (`<header>`, `<nav>`)**: Dilengkapi logo, tautan navigasi responsif, tombol *toggle* menu untuk layar kecil, dan lencana penghitung keranjang.
2. **Hero Banner (`<section>`)**: Bagian pengenalan utama dengan tombol ajakan (*call-to-action*).
3. **Katalog Kartu Produk (`<main>`, `<article>`)**: Tata letak *grid* responsif yang menampilkan informasi produk dan tombol interaktif.
4. **Formulir Login (`<form>`)**: Formulir masuk akun dengan validasi sisi klien (*client-side validation*).
5. **Footer (`<footer>`)**: Informasi hak cipta halaman.

## Struktur Proyek
```text
.
├── index.html   # Struktur utama HTML semantik
├── styles.css   # Gaya tampilan dan variabel CSS (custom properties)
├── script.js    # Logika interaktivitas (menu, keranjang, validasi form)
└── README.md    # Dokumentasi proyek
```

## Cara Menjalankan
1. Unduh atau *clone* repositori ini ke komputer lokal Anda:
   ```bash
   git clone https://github.com
   ```
2. Buka folder proyek, lalu klik dua kali berkas `index.html` untuk membukanya langsung di peramban (*browser*) seperti Chrome, Firefox, atau Edge.
3. *(Opsional)* Anda juga dapat menjalankannya melalui ekstensi **Live Server** di VS Code.
4. 
