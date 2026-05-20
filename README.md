# Portofolio Dani Mauludi

Portofolio ini dibuat sebagai situs statis yang bisa dibuka di HP siapa saja dan langsung dibagikan lewat link. Halaman ini juga dilengkapi dengan tombol `Lamar Kerja` untuk menghubungkan calon pemberi kerja lewat email.

## 🔧 Apa yang sudah ditambahkan
- Tombol **Lamar Kerja** langsung di halaman utama
- Tombol **Bagikan Link Portfolio** untuk menyalin URL publik
- Fitur **Ganti Foto** pada bagian foto utama dan bagian "Tentang Saya"
- Panduan deploy GitHub Pages dan cara membagikan link

## 1. Deploy ke GitHub Pages (Rekomendasi)
1. Buat akun GitHub jika belum punya.
2. Buat repository baru misalnya `portofolio-danimauludi`.
3. Pastikan semua file portofolio ada di folder project, termasuk gambar `IMG_2750.jpg` dan `def6cb9f-3248-4413-b27d-eaca994f36ef.jpg`.
4. Jalankan perintah berikut di folder project:
   ```bash
   cd /Users/f/portofolio-danimauludi
git init
git add .
git commit -m "Publish portofolio Dani Mauludi"
git branch -M main
git remote add origin https://github.com/<username>/portofolio-danimauludi.git
git push -u origin main
   ```
5. Buka GitHub → repository kamu → `Settings` → `Pages`.
6. Pada bagian `Build and deployment` pilih `Deploy from a branch`.
7. Pilih branch `main` dan folder `/root`.
8. Klik `Save`.

Setelah beberapa menit, link publik biasanya akan aktif seperti:

```text
https://<username>.github.io/portofolio-danimauludi/
```

## 2. Cara pakai tombol lamaran langsung
Pada halaman utama, kamu sudah memiliki:
- Tombol **Lamar Kerja**: membuka aplikasi email dengan subject dan body awal yang bisa langsung dikirim.
- Tombol **Rekrut Saya**: menuju bagian kontak di halaman.
- Tombol **Bagikan Link Portfolio**: menyalin URL ke clipboard.

Gunakan link publik yang sudah aktif untuk melamar:

```text
https://<username>.github.io/portofolio-danimauludi/
```

## 3. Cara mengedit foto di portofolio
Di halaman portofolio, ada tombol **Ganti Foto** pada:
- foto utama di bagian hero
- foto di bagian "Tentang Saya"

Klik tombol tersebut lalu pilih file gambar dari komputer atau HP kamu. Gambar akan langsung berubah di halaman.

> Catatan: perubahan ini bersifat sementara untuk tampilan browser saat itu. Untuk mengganti foto secara permanen, unggah ulang file gambar baru ke repo GitHub:
> - `IMG_2750.jpg`
> - `def6cb9f-3248-4413-b27d-eaca994f36ef.jpg`

## 4. Jika ingin deploy ulang setelah mengganti foto
1. Ganti file foto di folder project dengan nama yang sama.
2. Commit perubahan:
   ```bash
   git add IMG_2750.jpg def6cb9f-3248-4413-b27d-eaca994f36ef.jpg
   git commit -m "Update foto portofolio"
   git push
   ```
3. GitHub Pages akan mempublish versi terbaru dalam beberapa menit.

## 5. Contoh pesan WA untuk share

```text
Halo, ini portofolio online saya:
https://<username>.github.io/portofolio-danimauludi/

Silakan lihat profil, pengalaman kerja CNC, dan kontak untuk lamaran.
```

## 6. Jika ingin bantuan lanjut
- Saya bisa bantu buatkan repo GitHub dan push file otomatis.
- Saya bisa bantu cek jika GitHub Pages belum muncul.
- Saya bisa bantu perbaiki teks CTA lamaran di halaman atau menambahkan nomor WA.
