# Aplikasi Pendaftaran Mahasiswa Baru, Kerangka Frontend

Kemas Faris Rahadiansyah, 103022300040  
Tugas 4, Pemrograman Web: Frontend Skeleton dengan Tailwind CSS

## Deskripsi
Prototipe antarmuka Sistem Pendaftaran Mahasiswa Baru (PMB Nusantara) dengan navigasi sidebar bergaya portal akademik. Dibangun sebagai halaman HTML statis dengan Tailwind CSS Browser CDN dan Bootstrap Icons untuk ikon.

## Framework
Tailwind CSS dimuat melalui `https://cdn.tailwindcss.com`, sehingga proyek dapat dijalankan langsung tanpa Node.js, npm, atau langkah build. Bootstrap tidak digunakan sebagai framework CSS. Bootstrap Icons hanya menyediakan ikon.

## Halaman
- `index.html`: Dashboard, ringkasan contoh, tabel pendaftar terbaru, akses cepat, pengumuman, dan kalender contoh.
- `daftar.html`: Tabel pendaftar dengan pencarian client-side dan dialog detail native.
- `pendaftaran.html`: Form pendaftaran dengan validasi browser.
- `login.html`: Form tampilan login demo, belum memiliki autentikasi.

Data pendaftar pada halaman merupakan data contoh statis. Formulir dan dashboard belum terhubung ke backend/database.

## Screenshot Responsif
Tangkapan layar desktop 1280 x 900 dan mobile 375 x 812 tersimpan di `docs/screenshots/`:

Desktop: `desktop-index.png`, `desktop-daftar.png`, `desktop-pendaftaran.png`, `desktop-login.png`  
Mobile: `mobile-index.png`, `mobile-daftar.png`, `mobile-pendaftaran.png`, `mobile-login.png`
