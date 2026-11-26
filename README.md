# Generator Laporan Kinerja Harian

Sub Bagian Perencanaan Data dan Informasi
Sekretariat KPU Kabupaten Hulu Sungai Tengah

Aplikasi web satu halaman: ketik kegiatan dalam satu prompt, AI (Gemini) menyusun tabel laporan kinerja harian, lalu bisa diunduh sebagai .xlsx.

## Cara publikasi di GitHub Pages
1. Buat repository baru di GitHub (misalnya `laporan-kinerja`).
2. Upload `index.html`, `README.md`, dan file **`logo-kpu.png`** (logo resmi KPU, nama file harus persis ini).
3. Buka **Settings > Pages**, pada *Build and deployment* pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1 sampai 2 menit. Alamatnya: `https://NAMA-GITHUB.github.io/laporan-kinerja/`

## Memakai
1. Buka aplikasi, klik ikon gir di kanan atas, tempel API key, lalu Simpan.
   Key gratis dibuat di https://aistudio.google.com/apikey
2. Ketik kegiatan, misalnya: `hari ini apel senin dan notulen rapat. kemarin bersih-bersih ruangan`
3. Tekan **Susun laporan**, periksa hasilnya, lalu **Unduh .xlsx**.

## Catatan
- Setiap pengguna memasukkan API key sendiri. Key dan data tabel hanya tersimpan di browser masing-masing, tidak ada di repository.
- Jangan menaruh API key di dalam file `index.html` karena repository publik bisa dibaca siapa saja.
- Jika `logo-kpu.png` belum ada, aplikasi menampilkan tulisan "KPU" sebagai pengganti.
- Hasil AI perlu diperiksa sebelum dilaporkan.
