# Pengumuman Kelulusan Online – SMP Negeri 2 Sidoharjo

Website statis untuk pengumuman kelulusan siswa kelas 9 TA 2025/2026.

## Struktur File

```
kelulusan-smpn2sidoharjo/
├── index.html   ← Halaman utama (profil sekolah + form pencarian + hasil)
├── style.css    ← Tampilan (color palette: putih & hijau)
├── script.js    ← Logika pencarian berdasarkan NISN
├── data.js      ← Data 223 siswa (nama, nisn, nis, status)
└── README.md
```

## Pencarian
- User memasukkan **NISN** (angka) → klik "Cek Kelulusan" atau tekan Enter
- Sistem mencari di `data.js` secara client-side (tanpa server, tanpa database)
- Hasil tampil: Nama Lengkap, NISN, NIS, Status Kelulusan

## Update Data
Edit file `data.js` – ubah/tambah objek dalam array `students`.
Format: `{"nama":"...","nisn":"...","nis":"...","status":"LULUS"}`

## KODE INI MASIH BERSIFAT MENTAH DAN BELUM DI POLISH
