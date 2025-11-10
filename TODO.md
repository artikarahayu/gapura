# TODO: Implementasi Popup App Detail untuk Mobile

## Tugas Utama

- Untuk tampilan mobile, ganti button "Buka" dan "Segera Hadir" dengan popup saat klik card, seperti di Google Play Store atau Galaxy Store.
- Popup berisi deskripsi aplikasi, tombol keluar di kanan atas, dan tombol aksi di dalam popup.

## Langkah-langkah Implementasi

### 1. Edit index.html

- [ ] Tambahkan struktur HTML untuk popup modal app detail (mirip popup notifikasi, tapi untuk app).
- [ ] Popup berisi: ikon app, nama app, deskripsi lengkap, tombol "Keluar" di kanan atas, tombol "Buka" atau "Segera Hadir" di bawah.
- [ ] Tambahkan JavaScript untuk event listener pada setiap .app-card (hanya di mobile, cek window.innerWidth < 768).
- [ ] Script untuk toggle popup saat klik card atau tombol keluar, isi popup dengan data dari card yang diklik.

### 2. Edit css/beranda.css

- [ ] Tambahkan styling untuk popup modal app detail (mirip popup notifikasi, tapi disesuaikan untuk app).
- [ ] Pastikan popup responsif untuk mobile.
- [ ] Tambahkan class untuk membedakan popup app dari popup notifikasi (e.g., .app-popup-overlay).

### 3. Testing dan Debugging

- [ ] Test di browser mobile atau dev tools untuk memastikan popup muncul saat klik card.
- [ ] Pastikan popup tidak muncul di desktop, hanya mobile.
- [ ] Debug JavaScript jika ada error pada event listener.

## Status

- [x] Plan disetujui, mulai implementasi.
