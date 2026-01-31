# flutter_application_1
📌 Deskripsi Aplikasi
SmartSpend hadir sebagai solusi digital untuk mencatat setiap pemasukan dan pengeluaran. Aplikasi ini membantu pengguna untuk tetap disiplin pada rencana anggaran dan mencapai target tabungan tertentu dengan sistem pemantauan kemajuan (progress tracking).

🎯 Tujuan

Mempermudah pencatatan transaksi keuangan harian. Memberikan gambaran saldo akhir secara real-time. Membantu perencanaan finansial jangka panjang melalui fitur Target Tabungan. Menyediakan informasi kurs mata uang global untuk kebutuhan transaksi internasional.

✨ Fitur Utama

Aplikasi ini memiliki berbagai fitur unggulan untuk kebutuhan finansial: Manajemen Transaksi: Mencatat pemasukan dan pengeluaran dengan kategori yang jelas. Dashboard Finansial: Ringkasan total saldo, total pemasukan, dan total pengeluaran dalam satu layar. Target Tabungan (Savings Goal): Menentukan target nominal tabungan dan melihat persentase progres pencapaiannya. Kurs Mata Uang Real-time: Informasi nilai tukar mata uang dunia (USD, SGD, JPY, dll) terhadap Rupiah menggunakan API terbaru. Autentikasi Aman: Sistem Login dan Register menggunakan Firebase Authentication. Penyimpanan Cloud: Semua data transaksi tersimpan aman dan tersinkronisasi di Firebase Firestore.

🛠️ Teknologi yang Digunakan

Framework: Flutter (Dart) Backend: Firebase (Authentication & Firestore) State Management: Provider API: ExchangeRate-API (Untuk data kurs) Database: Cloud Firestore

🏗️ Arsitektur Sistem

Aplikasi ini menggunakan arsitektur Clean Architecture sederhana dengan pola MVVM (Model-View-ViewModel) melalui Provider: Model: Representasi data (Transaction, Goal, User). View: Antarmuka pengguna (UI Screens). ViewModel (Provider): Logika bisnis dan penghubung antara UI dengan Firebase.

🔄 Alur Aplikasi

Registrasi/Login: Pengguna masuk ke sistem menggunakan akun Firebase. Dashboard: Pengguna melihat ringkasan keuangan dan saldo terkini. Input Transaksi: Pengguna menambahkan pemasukan/pengeluaran; saldo akan terupdate otomatis. Target Tabungan: Pengguna membuat target baru dan mengupdate saldo tabungan secara berkala. Cek Kurs: Pengguna memantau nilai tukar mata uang global di menu Kurs.

demo aplikasi:


https://github.com/user-attachments/assets/4102d8b9-76a2-4eed-a5f4-25c66466e038



