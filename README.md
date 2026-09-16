# SI CEKTIS

Prototype PWA untuk Sistem Informasi Cek Kesehatan Gratis. Hasil aplikasi adalah skrining awal dan bukan diagnosis medis.

## Menjalankan aplikasi
```bash
npm install
npm run dev
npm run build
npm run preview
```

## Deploy Vercel
Import repository ke Vercel. Vite otomatis memakai perintah build `npm run build`; `vercel.json` menangani routing SPA.

## Teknologi
Vite, React, TypeScript, Tailwind CSS-ready, Framer Motion, Lucide React, Recharts, React Router, Service Worker dan LocalStorage-ready.

## Struktur
`src/pages` berisi tampilan utama; `src/components` berisi shell/layout dan komponen reusable; `src/data` menyediakan data mock.
