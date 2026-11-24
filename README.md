# Personal Portfolio

Template website pribadi modern profesional menggunakan HTML, CSS, dan JavaScript.

## Cara menjalankan di komputer
1. Ekstrak folder `personal-portfolio`.
2. Buka folder tersebut di Visual Studio Code atau editor pilihan.
3. Buka `index.html` di browser. Untuk pengalaman pengembangan yang lebih nyaman, gunakan ekstensi Live Server.

## Bagian yang perlu Anda ubah
- `index.html`: ganti `Nama Anda`, jabatan, deskripsi, email, LinkedIn, GitHub, keahlian, dan daftar proyek.
- Foto: simpan foto pribadi sebagai `assets/profile.jpg`. Saat ini area foto masih berupa placeholder; untuk menampilkan foto, ganti blok `.portrait-placeholder` di `index.html` dengan:
  `<img class="profile-photo" src="assets/profile.jpg" alt="Foto Nama Anda">`
  Lalu tambahkan CSS:
  `.profile-photo { width:100%; height:100%; object-fit:cover; border-radius:inherit; }`
- `css/style.css`: ubah warna, ukuran, dan tata letak.
- `js/script.js`: mengatur menu mobile, tahun otomatis, animasi scroll, dan navigasi aktif.

## Publikasi dengan GitHub Pages
1. Buat akun di https://github.com jika belum punya.
2. Buat repository baru bernama `portofolio_tfany` dan pilih Public.
3. Unggah seluruh isi folder ini ke repository (bukan folder ZIP-nya).
4. Buka Settings > Pages.
5. Pada Build and deployment, pilih `Deploy from a branch`.
6. Pilih branch `main` dan folder `/ (root)`, lalu Save.
7. Tunggu beberapa menit. Alamat website Anda:
   `https://tfanany.github.io/portofolio_tfany/`

## Catatan
GitHub Pages hanya menjalankan website statis (HTML, CSS, JavaScript). PHP dan MySQL tidak berjalan langsung di GitHub Pages.
