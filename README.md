# Quotation Generator

Aplikasi web statis (HTML + JavaScript) untuk membuat quotation PDF. Tidak perlu build.

## Deploy ke Vercel

### Cara 1: Vercel CLI
```
npm i -g vercel
cd vercel-quotation
vercel          # preview
vercel --prod   # produksi
```
Saat ditanya Framework Preset pilih "Other"; Build Command dan Output Directory dikosongkan.

### Cara 2: lewat GitHub
1. Upload isi folder ini ke repository GitHub.
2. Di vercel.com pilih Add New > Project, lalu import repository.
3. Framework Preset: Other. Klik Deploy.

## Catatan
- Pustaka jsPDF dan autotable sudah disertakan di folder `lib/`, jadi tidak bergantung pada CDN.
- Riwayat quotation dan profil perusahaan disimpan di localStorage browser. Gunakan tombol Ekspor/Impor untuk memindahkan data antar perangkat.
