# Portofolio Dani Mauludi

Untuk membuat portofolio ini bisa dibuka oleh semua orang di HP dan langsung dibagikan lewat link, kamu perlu meng-host `index.html` dan semua gambar secara publik.

## Opsi 1: GitHub Pages (Rekomendasi)
1. Buat akun GitHub jika belum punya.
2. Buat repository baru, misal `portofolio-danimauludi`.
3. Pastikan semua file portofolio ada di folder project, termasuk gambar yang dipakai di `index.html`.
4. Jalankan perintah berikut di folder project:
   ```bash
   git init
   git add .
   git commit -m "Publish portofolio Dani Mauludi"
   git branch -M main
   git remote add origin https://github.com/<username>/portofolio-danimauludi.git
   git push -u origin main
   ```
5. Buka GitHub → repo kamu → Settings → Pages.
6. Pilih branch `main`, lalu pilih folder `/root`.
7. Simpan.

Setelah beberapa menit, link aktif di:
`https://<username>.github.io/portofolio-danimauludi/`

## Opsi 2: Netlify
1. Buat akun di https://www.netlify.com/.
2. Login, pilih `Add new site` → `Import from Git`.
3. Hubungkan repositori GitHub yang berisi project kamu.
4. Pilih repo `portofolio-danimauludi` dan deploy.

Netlify akan memberikan URL publik yang bisa langsung dibagikan ke WA grup.

## Opsi 3: Vercel
1. Buat akun di https://vercel.com/.
2. Pilih `New Project` dan hubungkan repo GitHub.
3. Pilih repo `portofolio-danimauludi` lalu deploy.

## Catatan penting
- Pastikan file gambar yang disebut di `index.html` ikut berada di folder project.
- Setelah deploy, buka link publik dan cek apakah semua gambar tampil.
- Link tersebut bisa dibagikan ke WA dan HP orang lain akan bisa membuka portofolio lengkap.

## Jika ingin bantuan saya lanjutkan
- Siapkan perintah `git` untuk membuat repo
- Buatkan `README` deploy ke GitHub Pages atau Netlify secara lebih lengkap
- Bantu cek URL setelah deploy
