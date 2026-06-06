# UGC Kling Generator

Web app Next.js siap deploy ke Vercel untuk generate prompt video UGC, motion control, storyboard, VO, judul, hashtag, dan template API Kling.

## Jalankan lokal
```bash
npm install
npm run dev
```

## Deploy Vercel
1. Upload folder ini ke GitHub.
2. Buka Vercel > Add New Project.
3. Import repository.
4. Tambahkan Environment Variables:
```
KLING_API_KEY=isi_api_key_kling_bro
KLING_API_URL=https://api.kling.ai/v1/videos/generations
```
5. Deploy.

## Catatan
Endpoint/payload Kling bisa disesuaikan mengikuti dokumentasi API resmi akun bro.
