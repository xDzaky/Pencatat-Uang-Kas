# KasKelas

Dasbor KasKelas dibuat untuk membantu bendahara kelas mengelola kas harian tanpa formulir manual yang rawan lupa dan salah hitung. Berikut ringkasan permasalahan dan cara aplikasi ini menyelesaikannya.

## Latar Belakang Permasalahan
- **Data kas tersebar** di buku, chat, atau spreadsheet sehingga sulit melihat total saldo terbaru.
- **Rekap mingguan dan bulanan memakan waktu** karena harus menggabungkan pemasukan, pengeluaran, serta tunggakan secara manual.
- **Minim notifikasi** terkait siswa yang belum bayar atau dompet kas yang perlu diisi ulang.
- **Validasi kas tunai** tidak rapi, sehingga bendahara kesulitan mempertanggungjawabkan dana saat diminta wali kelas.

## Solusi yang Ditawarkan
- **Dashboard ringkas** yang memperlihatkan total siswa aktif, saldo dompet, saldo kas, dan hari kas berjalan dalam satu tampilan.
- **Manajemen siswa** lengkap dengan status aktif, penambahan cepat, serta pencatatan kas per siswa untuk mengurangi salah input.
- **Log kas harian** dengan kategori pemasukan/pengeluaran sehingga bendahara tahu sumber dana dan penggunaannya.
- **Rekap & tunggakan otomatis** yang menyusun daftar top saldo, pengutang, dan target kas mingguan sehingga keputusan lebih cepat.
- **Riwayat penarikan** sebagai bukti saat kas ditarik untuk kebutuhan kelas.

## Cara Menjalankan Proyek

### 1. Menggunakan Go Live (VS Code Live Server)
1. Buka folder proyek ini di VS Code.
2. Pastikan ekstensi **Live Server** terpasang.
3. Klik kanan `index.html` lalu pilih **Open with Live Server** atau tekan tombol **Go Live** di status bar.
4. Peramban akan terbuka otomatis di `http://127.0.0.1:5500` (atau port Live Server lain) dan menampilkan dashboard.

### 2. Menggunakan `npx serve`
Metode ini cocok jika Anda ingin server statis ringan di luar VS Code.

1. Pastikan Node.js 16+ sudah terpasang di komputer.
2. Buka terminal pada folder proyek.
3. Jalankan perintah berikut:
   ```bash
   npx serve
   ```
4. `serve` akan menampilkan URL lokal (biasanya `http://localhost:3000`). Buka URL tersebut di peramban untuk melihat aplikasi.

> Tips: Tambahkan parameter `-l 4000` jika ingin mengganti port, misalnya `npx serve -l 4000`.

Dengan dua opsi tersebut, bendahara kelas bisa menjalankan dashboard secara lokal sesuai preferensi masing-masing.
