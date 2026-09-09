# IG Unfollow Checker

Website statis untuk mengecek akun Instagram yang tidak follow balik kamu.

## Deploy ke Vercel

1. Import repo ini ke [vercel.com](https://vercel.com) -> New Project
2. Klik Deploy - selesai! Dapat domain `*.vercel.app`

**Via Vercel CLI:**
```bash
npx vercel --prod
```

## Cara Pakai

1. Instagram: **Pengaturan -> Akun -> Pusat Akun -> Unduh informasi -> Format HTML**
2. Tunggu email dari Instagram, ekstrak ZIP
3. Buka folder `followers_and_following/`
4. Upload `followers_1.html` dan `following.html`
5. Klik **Analisis Sekarang**

## Privasi

Semua data diproses **100% di browser** - tidak ada data yang dikirim ke server manapun.

## Fitur

- Upload drag & drop
- Deteksi otomatis akun yang tidak follow balik  
- Statistik ringkas (following, followers, tidak balik follow)
- Pencarian username real-time
- Link langsung ke profil Instagram
- Export hasil ke CSV
- Dark/light mode toggle
- Pagination 25 per halaman
- Mobile responsive
