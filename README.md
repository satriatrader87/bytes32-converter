# Bytes & Base64 Converter Web Tool

Sebuah alat berbasis web sederhana untuk melakukan konversi antara format data:
- Base64 ↔ Bytes
- Decimal Array ↔ Bytes32
- Otomatis menambahkan prefix `0x` untuk output Bytes/Bytes32

## Fitur
- **Base64 to Bytes**: Mengubah string Base64 menjadi array byte atau `0x`-hex string.
- **Bytes to Base64**: Mengubah array byte menjadi string Base64.
- **Decimal Array to Bytes32**: Mengubah array angka (0–255) menjadi string `0x`-hex panjang 32 byte.
- **Bytes32 to Decimal Array**: Mengubah `0x`-hex 32 byte menjadi array decimal.

## Cara Pakai
1. Buka halaman web (`index.html`) di browser atau akses melalui GitHub Pages.
2. Masukkan input sesuai format yang diminta (Base64 string atau array decimal).
3. Tekan tombol konversi untuk mendapatkan hasil.

## Deploy di GitHub Pages
1. Buat repository baru di GitHub.
2. Upload `index.html`, `README.md`, dan `LICENSE`.
3. Aktifkan GitHub Pages di Settings → Pages → Branch → `(main)` → root (`/`).
4. Akses di `https://satriatrader87.github.io/bytes32-converter/`.

## Lisensi
Proyek ini menggunakan lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail.
