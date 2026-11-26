# Aplikasi Surat Jalan

Aplikasi web satu halaman (`index.html`) untuk membuat, menyimpan, mencetak, mengimpor, dan mengekspor surat jalan.
Data disimpan di Supabase (tabel `suratjalan`).

## Fitur
- Buat dan cetak surat jalan (Bangunan / Manika Stone Art)
- Riwayat dengan filter bulan, tahun, dan pencarian
- Import Excel (pilih per sheet) dan Ekspor Excel (satu sheet per bulan, berbentuk tabel)
- Login admin dengan password

## Hosting di GitHub Pages
1. Unggah semua file di folder ini ke repositori GitHub (root repositori).
2. Settings → Pages → Branch `main`, folder `/ (root)` → Save.
3. Buka `https://<username>.github.io/<nama-repo>/`.

## Konfigurasi
Alamat dan kunci publik Supabase ada di `index.html` (variabel `SB_URL` dan `SB_KEY`).
Pastikan RLS aktif di tabel Supabase agar data terlindungi.

## Ikon
`favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`
dan `manifest.webmanifest` membuat aplikasi bisa dipasang ke layar utama HP ("Add to Home Screen").
