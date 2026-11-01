# Safety Walk

Aplikasi observasi dan monitoring K3 untuk lingkungan Kebun, PKS, Bulking, dan Workshop.

## Teknologi
- Progressive Web App (PWA), mobile-first.
- Penyimpanan lokal menggunakan IndexedDB.
- Service Worker untuk cache aplikasi dan penggunaan offline setelah kunjungan pertama.
- Login lokal; tidak memerlukan Supabase atau layanan cloud.

## Login dan akun
- Saat pertama kali dibuka, perangkat meminta pembuatan akun Super Admin.
- Super Admin membuat akun pengguna secara manual.
- Tidak tersedia pendaftaran mandiri.
- Password disimpan sebagai hash PBKDF2-SHA-256 dengan salt unik.
- Super Admin dapat mengaktifkan/menonaktifkan akun dan reset password.

## Catatan penting
- Akun, sesi, dan data tersimpan pada browser/perangkat yang digunakan.
- Akun dan data tidak otomatis tersinkron antarperangkat.
- Gunakan HTTPS untuk instalasi PWA dan pastikan perangkat tepercaya.
- Jangan hapus data situs/browser karena akan menghapus database lokal.
- Modul login dan manajemen pengguna merupakan tahap awal. Modul observasi, monitoring, master data, dan ekspor laporan masih dalam pengembangan.
