# SITAMPAN Voice V6

SITAMPAN Voice V6 adalah PWA statis untuk membantu pencatatan aktivitas harian berbasis voice-to-text.

## Fitur V6
- Login/daftar pengguna lokal.
- Data aktivitas dipisahkan per akun pada localStorage.
- Migrasi otomatis data V5 (jika ditemukan).
- 117 jenis aktivitas SITAMPAN.
- Input suara Bahasa Indonesia.
- Mode input suara berulang.
- Setiap hasil dapat diubah jenis aktivitasnya sebelum disimpan.
- Draft otomatis.
- Salin satu/semua hasil.
- Riwayat dengan pencarian, filter tanggal, dan pengurutan.
- Dashboard statistik harian, bulanan, total, dan aktivitas terbanyak.
- Rekap rentang tanggal.
- Export Excel XLSX dan CSV.
- Backup/pemulihan data JSON.
- PWA/service worker untuk pengalaman seperti aplikasi.

## Catatan
- Login bersifat lokal, bukan autentikasi server.
- Data tersimpan di browser/perangkat yang digunakan.
- Membersihkan data situs/browser dapat menghapus akun dan riwayat.
- Speech Recognition bergantung pada dukungan browser/perangkat dan pada sebagian browser memerlukan internet.
- Export XLSX memakai SheetJS Community Edition dari CDN resmi; jika library tidak termuat, aplikasi menyediakan CSV sebagai cadangan.

## GitHub Pages
Upload seluruh isi folder ini ke root repository GitHub Pages. Pastikan `index.html` berada di root.
