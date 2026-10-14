# Praktikum 4 — CSS Lanjutan

Latihan membuat struktur halaman web dengan HTML dan mengatur layout menggunakan CSS. Praktikum dimulai dari elemen `div` dan properti `float`, lalu dilanjutkan dengan situs sederhana yang memiliki navigasi, hero panel, konten utama, sidebar, widget, artikel, dan footer.

## Identitas

- **Nama:** Rendi Ichtiar Prasetyo
- **NIM:** 312510087
- **Kelas:** I251A

## Isi Praktikum

- Membuat box element menggunakan `div`, lalu mengatur posisi elemen dengan `float` dan `clear`.
- Menyusun halaman utama dengan header, navigasi, hero panel, konten, sidebar, dan footer.
- Menambahkan widget dan konten artikel pada layout utama.
- Membuat halaman About berisi profil singkat dan portofolio latihan.
- Membuat halaman Contact dengan form nama, email, subjek, dan pesan.
- Menggunakan satu stylesheet untuk tampilan halaman Home, About, dan Contact.

## Tangkapan Layar

Gambar berikut diambil dari bagian tampilan web pada laporan praktikum.

### Box Element dan Float

![Hasil latihan box element dan float](screenshots/box-float.png)

### Halaman Home

Bagian hero, kartu konten, dan sidebar:

![Halaman Home: hero, kartu konten, dan sidebar](screenshots/home-hero-cards.png)

Bagian artikel, widget, dan footer:

![Halaman Home: artikel, widget, dan footer](screenshots/home-articles-footer.png)

### Halaman About

![Halaman About dengan profil dan portofolio](screenshots/about.png)

### Halaman Contact

![Halaman Contact dengan formulir pesan](screenshots/contact.png)

## Struktur Proyek

```text
Lab4Web/
├── lab4_box.html
├── README.md
├── screenshots/
│   ├── box-float.png
│   ├── home-hero-cards.png
│   ├── home-articles-footer.png
│   ├── about.png
│   └── contact.png
└── lab4_layout/
    ├── home.html
    ├── about.html
    ├── contact.html
    └── style.css
```

## Menjalankan

Buka `lab4_box.html` di browser untuk melihat latihan box element. Untuk melihat layout situs, buka `lab4_layout/home.html`. Proyek ini menggunakan HTML dan CSS statis, jadi tidak memerlukan proses build atau instalasi dependensi.

Form pada halaman Contact merupakan contoh layout dan belum terhubung ke layanan pengiriman pesan.
