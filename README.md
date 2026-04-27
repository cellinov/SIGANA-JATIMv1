# SIGANA JATIM  
**Sistem Informasi Siaga Bencana Jawa Timur**

SIGANA JATIM adalah aplikasi berbasis mobile yang dirancang untuk mendukung pengelolaan dan distribusi informasi bencana secara digital di lingkungan BPBD Provinsi Jawa Timur. Sistem ini menghubungkan personel lapangan dan pusat kendali (PUSDALOPS) dalam satu platform terintegrasi.

---

## Daftar Fitur

- [Autentikasi Berbasis Role](#autentikasi-berbasis-role)
- [Dashboard Situasional](#dashboard-situasional)
- [Riwayat dan Arsip Laporan](#riwayat-dan-arsip-laporan)
- [Pelaporan Cepat](#pelaporan-cepat)
- [Manajemen Laporan](#manajemen-laporan)
- [Notifikasi](#notifikasi)
- [Hotline dan Portal Informasi](#hotline-dan-portal-informasi)

---

## Autentikasi Berbasis Role

Sistem autentikasi menggunakan pendekatan Role-Based Access Control (RBAC) untuk mengatur hak akses pengguna. Peran yang didukung meliputi Agen (lapangan), Admin (PUSDALOPS), dan Tamu. Setiap peran memiliki akses fitur yang berbeda sesuai kebutuhan operasional.

<img width="30%" alt="Screenshot_20260427-141148 SIGANA JATIM" src="https://github.com/user-attachments/assets/80baa910-1728-40eb-81d1-4e2b4074b527" />

User Role Menu (Agen BPBD) :

<img width="30%" alt="Screenshot_20260427-141638 SIGANA JATIM" src="https://github.com/user-attachments/assets/0eb1119a-5cdd-44e9-bdc0-8440e6dc3fb4" />

Admin Role Menu (PUSDALOPS BPBD) :

<img width="30%" alt="Screenshot_20260427-141623 SIGANA JATIM" src="https://github.com/user-attachments/assets/86c587f9-6d24-479e-a6e8-9ac26aba6a64" />


---

## Dashboard Situasional

Halaman dashboard menampilkan informasi terkait kondisi bencana, cuaca, dan aktivitas seismik sebagai referensi bagi pengguna dalam memahami situasi terkini.

<img width="30%" alt="Screenshot_20260427-141258 SIGANA JATIM" src="https://github.com/user-attachments/assets/733512c8-9d4f-4b17-ae81-2450ceae28b6" />


---

## Riwayat dan Arsip Laporan

Fitur ini menyediakan penyimpanan laporan bencana secara terstruktur. Data ditampilkan dalam bentuk daftar dan terintegrasi dengan visualisasi peta dari website (https://smartpb.bpbd.jatimprov.go.id/dasbor/) untuk melihat persebaran kejadian.

<img width="30%" alt="Screenshot_20260427-141329 SIGANA JATIM" src="https://github.com/user-attachments/assets/1615be18-36ff-4fdb-9403-c95e735f9433" />


---

## Pelaporan Cepat

Fitur pelaporan menggunakan formulir digital terstandarisasi. Sistem mendukung pengambilan lokasi otomatis (geotagging) untuk mencatat koordinat kejadian secara langsung dari perangkat pengguna.

<img width="30%" alt="Screenshot_20260427-141349 SIGANA JATIM" src="https://github.com/user-attachments/assets/cd1568f0-1ab8-4554-ab82-e0ed3c764cf9" />


---

## Manajemen Laporan

Modul ini digunakan oleh Admin untuk melakukan peninjauan, verifikasi, serta pembaruan status laporan. Status laporan meliputi Menunggu, Diproses, dan Selesai.

<img width="30%" alt="Screenshot_20260427-141611 SIGANA JATIM" src="https://github.com/user-attachments/assets/fead3955-f47d-4b91-8f94-4e76f1f468a3" />


---

## Notifikasi

Sistem notifikasi digunakan untuk menyampaikan informasi terkait laporan dan pembaruan status kepada pengguna secara langsung melalui perangkat masing-masing.

<img width="30%" alt="Screenshot 2026-04-08 092633" src="https://github.com/user-attachments/assets/18d8547f-c17d-47b5-a16f-7818c395d893" />


---

## Hotline dan Portal Informasi

Aplikasi menyediakan akses ke informasi resmi serta daftar kontak BPBD berdasarkan wilayah, guna mendukung kebutuhan koordinasi dan komunikasi.

<img width="30%" alt="Screenshot_20260427-141420 SIGANA JATIM" src="https://github.com/user-attachments/assets/819fd1ce-23d5-4b8a-b3b5-b0a20177252b" />

<img width="30%" alt="Screenshot_20260427-141444 SIGANA JATIM" src="https://github.com/user-attachments/assets/9994dd46-e5e3-44f9-882d-90cf9b4d48fc" />


---

## Tech Stack

- Android (Kotlin)
- Firebase (Firestore, Firebase Cloud Messaging)
- Google Play Services (Fused Location Provider)
- Cloud Functions
