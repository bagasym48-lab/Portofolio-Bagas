# Portofolio — Bagas Yoga Mahendra

Website portofolio satu halaman (Civil Engineer). Sudah dipecah menjadi HTML ringan + folder gambar terpisah.

## Struktur

```
portfolio/
├─ index.html          # halaman utama (± 90 KB)
└─ assets/
   └─ img/             # semua foto proyek, sertifikat, dan foto profil
```

## Cara membuka

Buka `index.html` langsung di browser (klik dua kali), atau di VS Code klik kanan → "Open with Live Server".
Pastikan folder `assets/` tetap berada di samping `index.html` agar gambar tampil.

## Cara mengganti / menambah gambar

Semua gambar ada di `assets/img/` dengan nama yang deskriptif (mis. `render-kantor-gubernur-papua-selatan.jpg`).
Untuk mengganti, timpa file dengan gambar baru memakai nama yang sama — tidak perlu mengubah kode.
Untuk menambah, taruh file baru di `assets/img/` lalu rujuk dari `index.html` (`src="assets/img/namafile.jpg"`).

## Cara hosting (gratis)

- **GitHub Pages**: buat repository, unggah folder ini, aktifkan Pages di Settings → Pages.
- **Netlify / Vercel**: drag-and-drop folder ini ke dashboard, langsung online.

## Ganti bahasa

Tombol **ID / EN** di kanan atas mengganti seluruh teks tanpa reload.

## Ekspor PDF

Buka di browser → Ctrl/Cmd + P → "Save as PDF". Layout cetak sudah disiapkan (animasi & elemen navigasi otomatis disembunyikan).
