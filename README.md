# TRY-OUT UABN-MDT — Adventure Learning Game

Aplikasi web interaktif gamifikasi try-out untuk persiapan **Ujian Akhir Bersama Nasional Madrasah Diniyah Takmiliyah Awaliyah (UABN-MDT)**.

## Fitur Utama

- **20 Paket Try-Out Lengkap (Total 420 Butir Soal):**
  - Masing-masing paket terdiri atas 21 butir soal dengan alokasi 60 menit.
  - Komposisi 7 mata pelajaran konsisten: 
    1. Soal 1–3: Al-Qur'an
    2. Soal 4–6: Hadits
    3. Soal 7–9: Tauhid
    4. Soal 10–12: Akhlaq
    5. Soal 13–15: Fiqih
    6. Soal 16–18: Bahasa Arab
    7. Soal 19–21: Tarikh Islam
- **Standar Aksara Pegon Nusantara:**
  - Pegon gundul tanpa harakat lengkap.
  - Tanda vokal e-pepet menggunakan tanda engkol (` ٓ `).
  - Vokal fonetik terbuka lengkap pada setiap suku kata.
  - Konsonan Nusantara bertitik tiga: `چ` (c), `ڠ` (ng), `ڤ` (p), `ݢ` (g), `ۑ` (ny).
  - Konsonan k mati konsisten menggunakan kaf (`ك`), bukan qaf (`ق`) atau hamzah (`ء`).
  - Istilah serapan Arab tetap menggunakan ejaan asli (`صلاة`, `زكاة`, `منافق`, dll.).
- **Sistem Hidden Transliteration → Reveal After Submission:**
  - Transliterasi Latin bahasa Indonesia tersembunyi saat soal pertama kali dikerjakan untuk melatih santri membaca aksara Pegon secara mandiri.
  - Transliterasi pertanyaan dan seluruh opsi A–D terbuka otomatis setelah tombol "Jawab Soal" ditekan.
- **Penyimpanan Ganda Tangguh (IndexedDB + LocalStorage):**
  - Otomatis menyimpan progres jawaban, sisa waktu, dan statistik.
  - Dilengkapi fitur *Session Recovery* (otomatis mendeteksi sesi pengerjaan yang belum selesai saat halaman dimuat ulang).
  - Fitur ekspor/impor cadangan berkas JSON (`Backup & Restore`).
- **Papan Nilai, Ekspor Laporan & WhatsApp:**
  - Papan nilai komprehensif 7 mata pelajaran.
  - Ekspor kartu nilai format gambar PNG berkualitas tinggi via HTML5 Canvas.
  - Integrasi WhatsApp Click-to-Chat resmi ke nomor `+6285119955995`.