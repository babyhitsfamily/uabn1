# Panduan Publikasi ke GitHub Pages

Berikut langkah-langkah mempublikasikan aplikasi ini ke GitHub Pages:

### Langkah 1: Buat Repositori Baru di GitHub
1. Masuk ke akun [GitHub](https://github.com/).
2. Klik ikon **+** di pojok kanan atas, lalu pilih **New repository**.
3. Beri nama repositori, misalnya: `tryout-uabn-mdt`.
4. Pilih opsi **Public**.
5. Jangan centang "Add a README file" jika ingin mengunggah file langsung.
6. Klik **Create repository**.

### Langkah 2: Unggah Berkas Proyek
**Cara Termudah (Via Web Browser):**
1. Pada halaman repositori kosong, klik tautan **uploading an existing file**.
2. Tarik dan lepaskan berkas berikut:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `README.md`
   - Folder `.github` (jika menggunakan GitHub Actions)
3. Tulis pesan commit, misalnya: `feat: initial release tryout uabn-mdt`.
4. Klik **Commit changes**.

### Langkah 3: Aktifkan Fitur GitHub Pages
1. Masuk ke tab **Settings** di repositori Anda.
2. Pada menu bilah samping kiri, pilih **Pages** (di bawah menu *Code and automation*).
3. Di bagian **Build and deployment**:
   - **Source:** Pilih `Deploy from a branch`.
   - **Branch:** Pilih `main` (atau `master`), foldernya pilih `/ (root)`.
   - Klik **Save**.
4. Tunggu sekitar 1–2 menit hingga proses build selesai.
5. URL publikasi Anda akan muncul di bagian atas, dengan format:
   `https://<username-anda>.github.io/tryout-uabn-mdt/`

### Langkah 4: Tautkan ke Google Sites
Di Google Sites:
- Anda dapat menyematkan URL GitHub Pages langsung melalui blok **Embed > By URL**, atau
- Membuat tombol besar: **"Buka Ujian Layar Penuh"** yang mengarah langsung ke URL GitHub Pages tersebut.