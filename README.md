# Safety Walk

Aplikasi observasi keselamatan kerja yang dirancang untuk penggunaan offline di perangkat Android.

## Prinsip
- Nama aplikasi: Safety Walk
- Offline-first: data lokal menggunakan IndexedDB
- PWA: dapat dipasang dari browser Android setelah di-host melalui HTTPS
- Login lokal multi-user dengan akun yang dikelola Super Admin
- Master data Unsafe Action dan Unsafe Condition dapat disesuaikan Super Admin
- Dokumentasi foto sebelum dan sesudah
- Ekspor laporan PDF dan Excel

## Status
Tahap awal: kerangka PWA dan fondasi penyimpanan lokal. Fitur autentikasi dan data operasional akan dikembangkan bertahap.

## Catatan
Login lokal pada satu perangkat tidak otomatis membagikan akun atau data ke perangkat lain. Sinkronisasi antarperangkat merupakan fitur terpisah dan opsional.
