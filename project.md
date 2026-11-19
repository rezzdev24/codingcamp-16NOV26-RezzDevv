# Life Dashboard — Project Steering

## Deskripsi Proyek
To-Do List Life Dashboard adalah aplikasi web sederhana yang membantu pengguna mengatur aktivitas harian mereka. Dibangun menggunakan HTML, CSS, dan Vanilla JavaScript tanpa framework atau backend.

## Tumpukan Teknologi
- **HTML** — struktur halaman
- **CSS** — styling dan tema (light/dark)
- **Vanilla JavaScript** — logika aplikasi
- **LocalStorage** — penyimpanan data di sisi klien

## Struktur Folder
```
kiroprojek/
├── .kiro/
│   └── steering/
│       └── project.md
├── css/
│   └── style.css
├── js/
│   └── app.js
└── index.html
```

## Fitur MVP
- Greeting: jam real-time, tanggal, sapaan berdasarkan waktu hari
- Focus Timer: timer 25 menit dengan tombol mulai, berhenti, reset
- To-Do List: tambah, edit, hapus, tandai selesai, simpan di LocalStorage
- Quick Links: tambah dan hapus tautan favorit, simpan di LocalStorage

## Tantangan yang Dipilih (3 dari 5)
1. **Light/Dark Mode** — toggle tema, preferensi disimpan di LocalStorage
2. **Nama kustom di sapaan** — pengguna bisa mengatur nama yang tampil di greeting
3. **Cegah tugas duplikat** — validasi input mencegah tugas yang sama ditambahkan dua kali

## Batasan Teknis
- Tidak menggunakan framework JavaScript (React, Vue, dll.)
- Tidak memerlukan backend atau server
- Semua data disimpan di browser (LocalStorage)
- Harus berjalan di Chrome, Firefox, Edge, dan Safari
