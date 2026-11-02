# Sistem Pengingat Absensi Dokter Spesialis

Aplikasi web satu halaman untuk bagian administrasi Klinik Utama Rawat Inap Parung: mengatur jadwal dokter spesialis, mengirim pengingat absensi lewat WhatsApp, dan memonitor kehadiran.

## Fitur
- Dashboard, Data Dokter, Kalender Jadwal, Pengingat Absensi, Monitoring Absensi, Riwayat dan Laporan, Pengaturan
- Jadwal per tanggal tertentu atau berulang per hari, dengan validasi jadwal ganda
- Pengingat 1 hari, 3 jam, 1 jam, atau waktu khusus, dengan pesan WhatsApp terisi otomatis
- Ekspor laporan ke Excel dan PDF A4

## Menjalankan
Buka `index.html` di peramban, atau gunakan GitHub Pages. Tidak perlu server atau proses build.

## Penyimpanan data
Data disimpan di `localStorage` peramban, jadi tiap perangkat punya data sendiri. Gunakan **Pengaturan > Unduh cadangan** untuk memindahkan data antar perangkat. Data dokter awal hanya contoh dan dapat dihapus.

## Catatan
Ekspor PDF dan Excel memuat pustaka jsPDF dan SheetJS dari CDN, sehingga memerlukan koneksi internet.
