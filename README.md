# AKTIVITAS VOICE V8

Aplikasi web/PWA untuk mencatat aktivitas harian menggunakan voice-to-text, dengan 117 jenis aktivitas.

## Fitur V8
- Nama web: AKTIVITAS VOICE
- Login/daftar lokal per pengguna
- Dashboard dan statistik
- 117 jenis aktivitas
- Mode Pintar untuk mendeteksi jenis aktivitas dari ucapan
- **Sesi suara panjang**: Speech Recognition memakai mode continuous dan auto-reconnect ketika browser mengakhiri sesi karena jeda
- Mode input berulang
- Draft otomatis
- Riwayat, pencarian, filter, dan rekap
- Export Excel dan CSV
- Backup/restore JSON
- Mode terang dan gelap
- Animasi UI, efek mic aktif, transisi panel, hover dan micro-interaction
- PWA untuk pemasangan di perangkat

## Catatan voice input
Teknologi voice-to-text menggunakan Web Speech API browser. Durasi aktual tetap dipengaruhi browser, perangkat, izin mikrofon, dan koneksi. V8 mengurangi masalah berhenti cepat dengan `continuous=true` dan menyambungkan kembali sesi secara otomatis selama pengguna belum menekan tombol berhenti.

## Data
Data akun dan aktivitas disimpan di localStorage perangkat/browser. Tidak ada server database pada versi ini. Gunakan Backup JSON untuk memindahkan data.

## Deployment GitHub Pages
Upload seluruh isi folder ke root repository. Pastikan `index.html` berada di root. Aktifkan Settings → Pages → Deploy from a branch → main → /(root).
