# ZIP Password Cracker

ZIP Password Cracker adalah aplikasi berbasis web yang mencoba membuka file ZIP yang diproteksi dengan password. Aplikasi ini menggunakan pendekatan brute-force dengan kombinasi huruf, angka, dan simbol dari `server.json`.

## Fitur
- Menggunakan **zip.js** untuk membaca file ZIP secara langsung di browser.
- Menghasilkan password secara acak berdasarkan karakter di `server.json`.
- Otomatis berhenti jika berhasil menemukan password.
- Batas waktu **5 menit** untuk mencegah looping tanpa henti.

## Cara Menggunakan
1. **Clone Repository ini** atau download sebagai ZIP:
   ```sh
   git clone https://github.com/username/repo-name.git
   ```
2. **Buka file `index.html`** di browser.
3. **Upload file ZIP** yang ingin dibuka.
4. Klik tombol **"Crack ZIP"** dan tunggu prosesnya.
5. Jika password ditemukan, akan ditampilkan di layar.
6. Jika dalam **5 menit** tidak berhasil, sistem akan menyatakan gagal.

## Struktur File
```
repo-folder/
│── index.html       # File utama (HTML, CSS, JS digabung)
│── server.json      # Karakter yang digunakan untuk brute-force
│── README.md        # Dokumentasi
```

## Catatan
- **Tidak semua ZIP bisa dibuka** tergantung dari kompleksitas password.
- **Browser memiliki batasan** dalam menangani file ZIP besar.
- **Jangan gunakan untuk tujuan ilegal!** Aplikasi ini hanya untuk edukasi.

## Lisensi
Proyek ini tersedia di bawah lisensi **MIT**. Bebas digunakan dan dimodifikasi selama mematuhi aturan yang berlaku.

