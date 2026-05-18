PANDUAN UPLOAD DOMAIN UTAMA KALIERP

UPLOAD SEMUA FILE INI KE ROOT DOMAIN / PUBLIC_HTML:

1. index.html
   - Landing page penjualan
   - Otomatis menjadi halaman depan domain

2. app.html
   - Aplikasi ERP login/register
   - User yang sudah beli bisa langsung buka: https://domainmu.com/app.html

3. firestore.rules
   - Tidak perlu dibuka publik
   - Copy isinya ke Firebase Console > Firestore Database > Rules > Publish

ALUR:
https://domainmu.com/
  = landing page

Klik "Masuk Aplikasi"
  = membuka app.html

CATATAN:
- Jangan rename app.html jika landing page masih mengarah ke app.html.
- Jika mau mengganti nama app.html, semua href="app.html" di index.html harus ikut diganti.
- Akun baru di app.html dimulai kosong dari awal.
