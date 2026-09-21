# SITAMPAN Voice V7

SITAMPAN Voice V7 adalah PWA gratis untuk mencatat aktivitas harian dengan voice-to-text.

## Fitur V7
- Login/daftar lokal per pengguna
- 117 jenis aktivitas SITAMPAN
- Voice-to-text Bahasa Indonesia
- Mode input berulang
- **Mode Pintar**: membantu mendeteksi jenis aktivitas dari ucapan
- Koreksi jenis aktivitas per hasil
- Draft otomatis
- Riwayat + pencarian + filter tanggal + pengurutan
- Dashboard statistik
- Rekap rentang tanggal
- Export Excel (.xlsx) dan CSV
- Backup/restore JSON
- **Mode terang & gelap**, tersimpan di perangkat
- PWA / dapat dipasang ke layar utama

## Catatan data
Akun dan data disimpan di localStorage browser pada perangkat yang digunakan. Tidak ada server database pada versi ini. Backup JSON disediakan untuk pemindahan data manual antar perangkat.

## Deploy GitHub Pages
1. Buat repository publik.
2. Upload seluruh isi folder ini sehingga `index.html` berada di root repository.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Simpan dan buka URL GitHub Pages yang diberikan.

## Excel
Export Excel menggunakan SheetJS Community Edition melalui CDN resmi. Jika library tidak termuat, aplikasi menyediakan CSV sebagai fallback.
