# DALVORA V2 — Toko Online + Admin

Project starter untuk DALVORA:
- Frontend toko
- Login pelanggan
- Keranjang & checkout
- Database SQLite
- Dashboard admin
- Manajemen produk
- Manajemen pesanan/status
- Struktur pembayaran QRIS/payment gateway siap dihubungkan
- PWA

## Jalankan
1. Install Node.js 20+.
2. `npm install`
3. `npm start`
4. Buka `http://localhost:3000`

Admin demo:
- Email: admin@dalvora.id
- Password: ganti-password-ini

## Penting untuk produksi
Ganti kredensial admin, JWT secret, dan koneksi payment gateway.
QRIS otomatis membutuhkan akun merchant/payment gateway dan kredensial API.
File ini menyediakan adapter/demo payment agar aplikasi dapat diuji tanpa transaksi nyata.
