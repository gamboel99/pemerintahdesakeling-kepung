# Website Resmi Desa Keling – Kepung, Kediri

Struktur proyek:
- `index.html` — situs utama (HTML + CSS + JS satu file)
- `assets/logo.png` — logo desa
- `assets/batik.svg` — pola batik islami untuk latar

## Cara Deploy ke GitHub Pages atau Vercel

### GitHub
1. Buat repositori baru di GitHub.
2. Upload seluruh isi folder ini (index.html dan folder `assets`).
3. Aktifkan GitHub Pages (Settings → Pages → Source: `main` → `(root)`).
4. Akses situs pada URL Pages yang diberikan.

### Vercel
1. Masuk ke vercel.com dan `New Project` → `Import Git Repository`.
2. Pilih repo ini dan deploy. Tidak perlu build command (static).
3. Pastikan `index.html` di root, Vercel akan melayani sebagai halaman utama.

Jika ingin memecah menjadi banyak halaman, buat file baru (mis. `profil.html`) dan sesuaikan tautan.