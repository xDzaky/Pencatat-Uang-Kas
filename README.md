Berikut **README.md versi lengkap & profesional**, lengkap dengan struktur, instalasi, fitur, preview section, serta badge-friendly.
Setelah itu ada **Topics** untuk metadata GitHub.

---

# ✅ **README.md (Lengkap & Siap Upload)**

````md
# KasKelas — Dashboard Pengelolaan Uang Kas Kelas

KasKelas adalah aplikasi web sederhana namun powerful untuk membantu bendahara kelas mengelola kas harian tanpa formulir manual. Dengan tampilan yang ringkas dan fitur yang lengkap, KasKelas mempermudah proses pencatatan pemasukan, pengeluaran, tunggakan, serta kontrol saldo dompet dan bank.

---

## 🎯 Tujuan Proyek
Bendahara kelas biasanya mencatat kas di buku, chat, atau spreadsheet yang berpotensi hilang, sulit dicari, dan rawan salah hitung. KasKelas dibuat untuk:
- Mengelola kas harian dengan lebih cepat dan rapi  
- Menampilkan saldo real-time  
- Mendeteksi siapa yang masih nunggak  
- Menyusun rekap mingguan otomatis  
- Membantu bendahara mempertanggungjawabkan kas dengan bukti rapi  

---

## 🚀 Fitur Utama

### 📌 Dashboard
- Ringkasan siswa aktif
- Total saldo dompet & saldo bank
- Total tunggakan
- Informasi hari kas berjalan

### 📌 Manajemen Siswa (CRUD)
- Tambah, edit, nonaktifkan siswa  
- Data tersimpan di LocalStorage  
- Siswa tetap memiliki histori meskipun dinonaktifkan  

### 📌 Kas Harian
- Catat pembayaran kas Rp 1.000/hari (Senin–Jumat)
- Pembayaran **lumpsum** (misal 10 ribu → menutup 10 hari)
- Menentukan “lunas sampai tanggal berapa” secara otomatis
- Saldo otomatis masuk ke dompet (default deposit)

### 📌 Rekap & Tunggakan
- Hitung total hari kas seharusnya dibayar sampai hari ini  
- Hitung hari yang sudah ditutup oleh pembayaran  
- Hitung tunggakan otomatis  
- Sort by “penunggak terbanyak”  
- Laporan ringan untuk wali kelas  

### 📌 Dompet & Bank
- Saldo dompet (kas tunai)
- Saldo bank (kas virtual)
- Pindahkan dana dari dompet → bank
- Pindahkan dana dari bank → dompet

### 📌 Riwayat Penarikan
- Catat penarikan dari bank
- Isi alasan & jumlah
- Sebagai bukti penggunaan kas

### 📌 Penyimpanan Data
- Menggunakan `localStorage`
- Tidak membutuhkan backend
- Data tetap aman di perangkat pengguna

---

## 🧩 Tech Stack
- **HTML**
- **CSS / TailwindCSS**
- **JavaScript (Vanilla)**
- **LocalStorage (Browser)**

Tanpa framework seperti React/Next agar aplikasi ringan dan cukup dijalankan secara lokal.

---

## 🛠️ Cara Menjalankan Proyek

### 1️⃣ Menggunakan Live Server (VS Code — Direkomendasikan)
1. Buka folder project di VS Code  
2. Pastikan extension **Live Server** terpasang  
3. Klik kanan `index.html` → **Open with Live Server**  
4. Browser terbuka di `http://127.0.0.1:5500`

### 2️⃣ Menggunakan `npx serve`
Jika ingin menjalankan tanpa VS Code:

```bash
npx serve
````

Atau menentukan port:

```bash
npx serve -l 4000
```

---

## 📁 Struktur Folder (Contoh)

```
/KasKelas
│── index.html
│── style.css (atau tailwind.css build)
│── app.js
│── /assets
│     ├── icons/
│     └── images/
│── /components
│── /pages
```

---

## 📸 Preview

> Tambahkan screenshot dashboard agar tampilan lebih menarik.


```