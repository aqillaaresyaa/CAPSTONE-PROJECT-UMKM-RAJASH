# RENCANA PENGUJIAN SISTEM RAJASH

## 1. Tujuan Pengujian

Pengujian dilakukan untuk memastikan seluruh fitur sistem pencatatan keuangan RAJASH berjalan sesuai kebutuhan dan fungsi yang telah dirancang.

## 2. Daftar Rencana Pengujian

| No. | Fitur yang Diuji | Cara Menguji | Hasil yang Diharapkan | Penanggung Jawab |
|---|---|---|---|---|
| 1 | Login Kredensial Valid | Memasukkan username dan password pemilik yang benar, lalu menekan tombol masuk. | Pengguna berhasil login dan diarahkan ke dashboard utama. | Reinald Oryza Apriancahya |
| 2 | Login Kredensial Salah | Memasukkan username benar dengan password salah atau akun yang belum terdaftar. | Sistem menolak akses dan menampilkan pesan kesalahan. | Reinald Oryza Apriancahya |
| 3 | Input Penjualan Tunai Valid | Memasukkan penjualan air galon senilai Rp25.000 dengan pembayaran tunai. | Data tersimpan dan pemasukan bertambah di riwayat. | Brian Dicky Vanka Andaraneva |
| 4 | Validasi Input Pemasukan | Mengosongkan nominal atau memasukkan karakter non-angka/negatif. | Sistem menolak penyimpanan dan menampilkan pesan validasi. | Brian Dicky Vanka Andaraneva |
| 5 | Input Biaya Operasional | Memasukkan pengeluaran BBM Rp30.000 dan servis Rp50.000. | Pengeluaran tersimpan sesuai kategori dan saldo kas diperbarui. | Brian Dicky Vanka Andaraneva |
| 6 | Input Transaksi Piutang | Memasukkan penjualan galon dengan metode pembayaran tempo. | Transaksi masuk daftar piutang dengan status Belum Lunas. | Reinald Oryza Apriancahya |
| 7 | Pembaruan Status Pelunasan | Memilih tagihan belum lunas dan mengonfirmasi pembayaran. | Status berubah menjadi Lunas dan saldo piutang berkurang. | Reinald Oryza Apriancahya |
| 8 | Rekapitulasi Filter Periode | Memilih filter tanggal harian dan bulanan. | Sistem menampilkan total transaksi sesuai periode. | Meutia Shafira Ramadhani |
| 9 | Perhitungan Laba Bersih | Memeriksa pemasukan Rp500.000 dan pengeluaran Rp200.000. | Sistem menampilkan laba bersih Rp300.000. | Meutia Shafira Ramadhani |
| 10 | Deteksi Transaksi Ganda | Memasukkan dua transaksi dengan nominal, tanggal, dan atribut identik secara berurutan. | Sistem mendeteksi indikasi transaksi duplikat. | Aqilla Resya Luthfiya dan Reinald Oryza Apriancahya |
| 11 | Ringkasan Tagihan Piutang | Membuka dashboard dan melihat modul piutang. | Sistem menampilkan daftar pelanggan dengan piutang aktif. | Brian Dicky Vanka Andaraneva |
| 12 | Responsivitas Desktop dan Mobile | Membuka aplikasi melalui laptop dan ponsel. | Tampilan menyesuaikan ukuran layar tanpa elemen terpotong. | Brian Dicky Vanka Andaraneva |

## 3. Pencatatan Hasil Pengujian

Seluruh temuan pengujian fungsional, bug atau anomali sistem, serta verifikasi perbaikan akan dicatat secara terpusat melalui spreadsheet pengujian bersama tim.

## 4. Tindak Lanjut

Setiap masalah yang ditemukan akan diperbaiki oleh anggota tim yang bertanggung jawab. Setelah perbaikan selesai, fitur terkait akan diuji kembali untuk memastikan masalah telah teratasi.
