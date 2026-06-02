# PANDUAN LENGKAP — frankach.github.io

## ISI FOLDER INI

```
frankach-site/
├── index.html               ← Halaman utama (homepage)
├── template-artikel-baru.html  ← Template untuk setiap artikel baru
├── artikel-olimpiade.html   ← Contoh artikel (bisa dihapus/edit)
└── README.md                ← Panduan ini
```

---

## FASE 1 — SETUP AWAL (dilakukan sekali saja)

### Step 1 — Buat akun GitHub
1. Buka https://github.com → Sign up
2. Pilih username: **frankach**
3. Verifikasi email

### Step 2 — Buat repository
1. Klik tombol **"New"** (pojok kiri atas, ikon +)
2. Repository name: **`frankach.github.io`** ← HARUS PERSIS INI
3. Pilih **Public**
4. Centang **"Add a README file"**
5. Klik **"Create repository"**

### Step 3 — Upload semua file
1. Di halaman repository, klik **"Add file"** → **"Upload files"**
2. Drag & drop SEMUA file dari folder ini ke browser
3. Di bawah, tulis commit message: `first commit`
4. Klik **"Commit changes"**

### Step 4 — Aktifkan GitHub Pages
1. Di repository, klik tab **"Settings"**
2. Di sidebar kiri, klik **"Pages"**
3. Di bagian "Source", pilih **"Deploy from a branch"**
4. Branch: **main**, folder: **/ (root)**
5. Klik **Save**

### Step 5 — Tunggu 2-3 menit
Website kamu akan live di: **https://frankach.github.io**

---

## FASE 2 — PUBLISH ARTIKEL BARU (lakukan kapan saja)

### Langkah publish artikel baru:

1. **Copy file template**
   - Duplikat file `template-artikel-baru.html`
   - Rename jadi nama artikel, contoh: `artikel-tentang-python.html`

2. **Edit isinya**
   - Buka file dengan Notepad/VS Code
   - Ganti semua teks yang diawali kata `GANTI:`
   - Isi judul, kategori, tanggal, dan isi artikel

3. **Tambahkan ke homepage**
   - Buka `index.html`
   - Cari bagian `<!-- TAMBAH ARTIKEL BARU DI SINI -->`
   - Copy paste satu blok `<div class="art-row">` dan edit isinya
   - Ubah `onclick` ke nama file artikel baru kamu

4. **Upload ke GitHub**
   - Buka repository di github.com/frankach/frankach.github.io
   - Klik **"Add file"** → **"Upload files"**
   - Upload file artikel baru + `index.html` yang sudah diedit
   - Commit → selesai, artikel live dalam 1-2 menit

---

## TIPS PRIVASI

- JANGAN cantumkan NIM di halaman manapun
- Untuk lokasi, cukup tulis "West Java, Indonesia" atau "Indonesia"
- Email kontak: buat email khusus publik (misal Gmail baru) jangan email kampus

---

## CARA BELI DOMAIN SENDIRI (opsional)

Jika ingin domain `frenkhy.me` atau `frenkhy.id`:
1. Beli di Niagahoster, Domainesia, atau Namecheap (~Rp 100rb–200rb/tahun)
2. Di GitHub Pages Settings → Custom domain → masukkan domain kamu
3. Di provider domain, tambahkan DNS record yang diberikan GitHub

---

## PERTANYAAN?

Semua file sudah siap pakai. Kamu hanya perlu:
1. Upload ke GitHub (15 menit pertama kali)
2. Edit template untuk setiap artikel baru (kapan saja)
