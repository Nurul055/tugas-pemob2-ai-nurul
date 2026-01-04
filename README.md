# tugas-pemob2-ai-nurul


SmartSpend yaitu Pengelola Anggaran & Target Tabungan".
1.	Konsep Utama 
SmartSpend untuk mencatatan keuangan fokusnya adalah pada "Goal-Based Saving
"SmartSpend dibuat bukan cuma buat nyatet angka, tapi buat ngubah kebiasaan. Banyak orang nyatet pengeluaran tapi tetep boros. Dengan fitur Goal-Based Saving, aplikasi ini ngebantu user buat punya prioritas: mending jajan sekarang atau nabung buat beli laptop? Jadi ada unsur edukasi keuangan-nya."
Contoh: kita punya target nabung buat bayar publikasi jurnal atau beli laptop baru. Nah, web/aplikasi ini bakal nemenin kita sampai target itu 100%.


2. Arsitektur Teknologi 
Aplikasi ini berdiri di atas tiga pilar utama:

Frontend (Flutter): Menggunakan bahasa Dart untuk membangun tampilan yang cantik dan responsif (bisa jadi aplikasi Android atau Web PWA).
Backend (Firebase):
Firebase Auth: Mengelola keamanan akun (siapa yang boleh masuk).
Cloud Firestore: Database NoSQL untuk menyimpan transaksi secara real-time.
External Data (REST API): Mengambil data luar (seperti kurs USD ke IDR) agar aplikasi terasa "hidup" dan informatif.

3. Strategi Deployment (The Delivery)
Setelah koding selesai, Anda memiliki dua output:
Android (APK): File .apk yang bisa langsung di-install di HP dosen atau teman.
Web (PWA): Aplikasi dijalankan di browser (lewat Netlify). Keunggulannya adalah PWA bisa di-"Add to Home Screen" sehingga terasa seperti aplikasi asli tanpa perlu download dari Play Store.

Biar tampilan aplikasi SmartSpend kamu terlihat profesional dan nggak bikin bingung (apalagi buat dosen yang nilai), desainnya harus bersih, simpel, dan "berbau" finansial. Karena kamu orang Akuntansi, kita pakai tema warna Teal (Hijau Kebiruan) atau Biru Navy supaya terkesan terpercaya dan rapi.

4. Tampilan Aplikasi
- Halaman Login & 2. Register
- Halaman Dashboard Berisi Total Saldo, Pemasukan, Pengeluaran.
- Halaman Catat Transaksi
- Halaman Riwayat / History berisi ikon kategori, nama transaksi, tanggal, dan nominalnya.
- Halaman Target Tabungan (Fitur Jagoan) Ini tempat fitur Goal-Based Saving
- Halaman Kurs & Berita (REST API)
  
5. Teknologi Yang Digunakan

Flutter
Dart
REST API (MockAPI.io)
Firebase
Firebase Authentication
Flutter Web (PWA)
Netlify (Deployment)

6.Tujuan Proyek
1. Membantu Kedisiplinan Finansial (Goal-Oriented)
Tujuan utamanya bukan cuma jadi "buku catatan" pengeluaran, tapi jadi motivator. Aplikasi ini mau ngubah kebiasaan user yang tadinya cuma bisa belanja jadi lebih fokus ke nabung. Dengan adanya fitur Target Tabungan, user punya alasan kuat buat ngerem pengeluaran demi mencapai target yang udah mereka buat (misal: buat dana riset S3 atau beli gadget baru).

2. Digitalisasi Pencatatan Akuntansi Sederhana
Sebagai orang yang paham akuntansi, kamu mau mindahin prinsip Arus Kas (Cash Flow) dari cara manual/tradisional ke aplikasi digital. Tujuannya supaya pencatatan lebih akurat, otomatis menghitung saldo, dan nggak ribet bawa-bawa buku. Semuanya ada di genggaman tangan.

3. Keamanan dan Kemudahan Akses Data (Cloud)
Dengan teknologi Firebase, tujuan proyek ini adalah mastiin data user aman. Kalau HP ganti atau rusak, catatan keuangannya nggak ilang karena semuanya tersimpan di cloud server. Jadi, user punya "brankas data" pribadi yang bisa diakses kapan saja.
