# Proyek UTS Pemrograman Web Dasar — HIMASTI

## Identitas Mahasiswa
- Nama: [Isi nama lengkap]
- NPM: [Isi NPM]
- Program Studi: Sistem dan Teknologi Informasi
- Tema: Profil Organisasi Kampus
- Objek: HIMASTI (Himpunan Mahasiswa Sistem dan Teknologi Informasi)

## Deskripsi
Website profil HIMASTI dibuat sebagai proyek UTS menggunakan HTML5, CSS3, dan JavaScript murni. Website memiliki empat halaman yang saling terhubung: Beranda, Tentang, Program Kerja, dan Kontak.

## Fitur
- Navigasi yang sama pada seluruh halaman.
- HTML semantik: header, nav, main, section, article, dan footer.
- Beranda berisi hero section, ringkasan organisasi, dan tiga kegiatan unggulan.
- Halaman Tentang berisi profil, visi, misi, dan contoh struktur pengurus.
- Halaman Program Kerja memiliki enam kartu kegiatan, pencarian nama, dan filter kategori.
- Halaman Kontak berisi informasi alamat, tautan media sosial, peta, formulir, dan tabel.
- Formulir memakai validasi HTML5: required, email, pola nomor HP 10–13 digit, serta pesan 10–500 karakter.
- CSS eksternal menggunakan Flexbox, Grid, variabel CSS, hover, transition, keyframes, dan dua media query.
- JavaScript untuk menu hamburger, pencarian/filter katalog, dan pesan hasil validasi formulir.

## Struktur Folder
```text
HIMASTI_UTS/
├── index.html
├── tentang.html
├── katalog.html
├── kontak.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
└── README.md
```

## Cara Menjalankan
1. Ekstrak folder proyek.
2. Buka folder menggunakan Visual Studio Code.
3. Jalankan `index.html` melalui browser (atau ekstensi Live Server).
4. Coba seluruh menu dan fitur pada empat halaman.

## Sumber Gambar
Gambar contoh menggunakan URL dari Unsplash. Gambar dimuat dari internet dan dapat diganti dengan foto kegiatan HIMASTI yang memiliki izin penggunaan.
- https://unsplash.com/
- Foto pada halaman Tentang: Unsplash, foto diskusi kelompok.
- Foto katalog dan latar hero: Unsplash, foto teknologi, desain, dan kegiatan kelompok.

## Catatan Penyesuaian Sebelum Dikumpulkan
- Ganti nama ketua, wakil, dan sekretaris dengan data pengurus yang benar.
- Pastikan visi, misi, sejarah, program kerja, dan jadwal sesuai informasi resmi HIMASTI.
- Ganti tautan Instagram dan email contoh dengan kontak resmi organisasi.
- Isi nama dan NIM pada README.
- Uji keempat halaman melalui W3C Markup Validator dan simpan tangkapan layar hasil validasi ke folder `bukti/`.
- Buat repositori GitHub dengan nama `NIM-Nama-UTS` dan lakukan minimal lima commit bertahap sesuai instruksi modul.
- Formulir pada proyek ini hanya simulasi front-end; belum mengirim pesan ke server atau email.

## Penjelasan Teknologi
- HTML membentuk struktur dan isi setiap halaman.
- CSS mengatur warna, ukuran, tata letak, dan tampilan responsif.
- JavaScript memberi interaksi pada menu, katalog, dan formulir.
