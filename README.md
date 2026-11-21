# Cyberpunk Red Blue Portfolio

Portofolio Next.js + React + TypeScript dengan background galaksi bergerak, bintang berkelip, efek orbit cyberpunk merah-biru, dan tanpa foto pribadi.

## Menjalankan di VS Code

1. Ekstrak ZIP.
2. Buka folder `portfolio-cyberpunk-nextjs` di VS Code.
3. Pilih Terminal > New Terminal.
4. Jalankan:

```bash
npm install
npm run dev
```

5. Buka `http://localhost:3000`.

## Build untuk mengecek project

```bash
npm run build
```

## Personalisasi

Edit `app/page.tsx`:
- Ganti `emailkamu@example.com` dengan email aktif.
- Ganti `@usernamekamu` dan tautan Instagram.
- Ubah isi proyek, pengalaman, dan keahlian sesuai data sebenarnya.

Nama, universitas, dan program studi sudah diisi berdasarkan detail portofolio yang pernah diberikan. Tidak ada foto pribadi di project ini.

## Struktur

- `app/page.tsx` — isi halaman portofolio.
- `app/globals.css` — seluruh desain dan animasi.
- `components/GalaxyBackground.tsx` — animasi bintang dan galaksi berbasis canvas.
- `app/layout.tsx` — metadata dan layout Next.js.
- `postcss.config.mjs` — konfigurasi PostCSS.

Catatan: Next.js App Router menggunakan `app/page.tsx` sebagai halaman utama, bukan `index.html`.
