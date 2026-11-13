# Website Profil Pribadi

Website statis menggunakan HTML, CSS, dan JavaScript. Bisa di-host gratis dengan GitHub Pages.

## 1. Edit isi profil
Buka `index.html`, lalu cari dan ganti:
- `Nama Lengkap`
- Deskripsi perkenalan
- Domisili umum (opsional)
- Pendidikan (cukup informasi umum)
- Keahlian dan proyek
- Tautan GitHub dan media sosial

Foto profil yang kamu kirim sudah dipasang sebagai `assets/foto-profil.jpg`. Jika ingin menggantinya, timpa file tersebut dengan foto baru menggunakan nama yang sama.

## 2. Ganti username GitHub
Ganti semua teks `USERNAME` di:
- `index.html`
- `robots.txt`
- `sitemap.xml`

Gunakan alamat GitHub Pages yang benar. Untuk repositori khusus `USERNAME.github.io`, alamat umumnya `https://USERNAME.github.io/`.

## 3. Upload ke GitHub
1. Buat akun di https://github.com/ jika belum punya.
2. Buat repository baru bernama `USERNAME.github.io` (ganti USERNAME dengan username GitHub).
3. Pilih Public.
4. Upload seluruh isi folder ini, bukan file ZIP-nya.
5. Buka Settings → Pages.
6. Pada Build and deployment, pilih Deploy from a branch.
7. Pilih branch `main` dan folder `/ (root)`, lalu Save.
8. Tunggu proses publikasi, kemudian buka `https://USERNAME.github.io/`.

## 4. Agar bisa ditemukan Google
- Pastikan website sudah publik dan bisa dibuka tanpa login.
- Buka Google Search Console: https://search.google.com/search-console
- Tambahkan properti URL Prefix sesuai alamat GitHub Pages.
- Verifikasi kepemilikan mengikuti metode yang ditawarkan Google.
- Kirim sitemap: `https://USERNAME.github.io/sitemap.xml`.
- Gunakan URL Inspection untuk meminta pengindeksan halaman utama.

Google tidak menjamin halaman langsung muncul atau mendapat peringkat tertentu. Proses crawling dan indexing dapat memerlukan waktu.

## Keamanan dan privasi
Karena website ini publik, jangan masukkan alamat rumah, nomor identitas, nomor telepon pribadi, lokasi real-time, jadwal rutin, atau informasi sensitif. Gunakan hanya informasi dan tautan yang memang ingin dipublikasikan.
