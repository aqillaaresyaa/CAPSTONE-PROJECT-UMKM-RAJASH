# RENCANA PENGUJIAN SISTEM RAJASH

## Tujuan Pengujian

Pengujian dilakukan untuk memastikan seluruh fitur sistem pencatatan keuangan RAJASH berjalan sesuai kebutuhan dan fungsi yang telah dirancang.

## Daftar Rencana Pengujian

| No. | Fitur yang Diuji | Cara Menguji | Hasil yang Diharapkan | Penanggung Jawab |
|---|---|---|---|---|
| 1 | Autentikasi Pengguna: Login Kredensial Valid | MMemasukkan username dan password pemilik yang benar pada formulir login, lalu menekan tombol masuk. | Pengguna berhasil login, token sesi terbentuk, dan sistem mengarahkan halaman ke dashboard utama. | Reinald Oryza Apriancahya (AI Full-Stack Developer) |
| 2 | Autentikasi Pengguna: Login Kredensial Salah | Memasukkan username yang benar tetapi password salah, atau memasukkan akun yang belum terdaftar. | Sistem menolak akses masuk, sesi tidak terbentuk, dan menampilkan pesan kesalahan kredensial yang jelas. | Reinald Oryza Apriancahya (AI Full-Stack Developer) |
| 3 | Pencatatan Pemasukan: Input Penjualan Tunai Valid | Memasukkan penjualan air galon senilai Rp25.000 dengan status pembayaran tunai, lalu menekan tombol simpan. | Data tersimpan ke basis data, muncul notifikasi sukses, dan nilai pemasukan langsung bertambah di riwayat. | Brian Dicky Vanka Andaraneva (AI Full-Stack Developer) |
| 4 | Validasi Form: Input Pemasukan Kosong / Tidak Valid | Mengosongkan kolom nominal transaksi atau memasukkan karakter non-angka/negatif, lalu mencoba menyimpan. | Sistem menolak penyimpanan, form menampilkan indikator validasi kesalahan, dan data tidak tersimpan. | Brian Dicky Vanka Andaraneva (AI Full-Stack Developer) |
| 5 | Pencatatan Pengeluaran: Input Biaya Operasional | Memasukkan pengeluaran BBM becak Rp30.000 dan servis Rp50.000 dengan memilih kategori yang sesuai, lalu menyimpan. | PData pengeluaran tersimpan akurat sesuai kategori biaya dan langsung memotong saldo kas rekapitulasi. | Brian Dicky Vanka Andaraneva (AI Full-Stack Developer) |
| 6 | Pencatatan Piutang: Input Transaksi Penjualan Tempo | Memasukkan transaksi penjualan galon atas nama pelanggan tertentu dengan memilih opsi pembayaran piutang/tempo. | Transaksi tercatat pada daftar piutang dengan status 'Belum Lunas', nominal piutang bertambah, dan kas tunai tidak bertambah. | Reinald Oryza Apriancahya (AI Full-Stack Developer) |
| 7 | Pengelolaan Piutang: Pembaruan Status Pelunasan | Memilih tagihan pelanggan yang belum lunas, menekan tombol pelunasan, lalu mengonfirmasi pembayaran lunas. | Status tagihan berubah menjadi 'Lunas', saldo piutang berkurang, dan nominal uang masuk ke kas pemasukan. | Reinald Oryza Apriancahya (AI Full-Stack Developer) |
| 8 | Kalkulasi Keuangan: Rekapitulasi Filter Periode | Memilih filter tanggal tertentu (harian dan bulanan), lalu memverifikasi agregasi total pemasukan dan pengeluaran. | Tabel rekapitulasi menyajikan seluruh transaksi pada periode tersebut dengan penjumlahan total yang presisi. | Meutia Shafira Ramadhani (Data Science Specialist) |
| 9 | Kalkulasi Keuangan: Perhitungan Laba Bersih Otomatis | Melakukan verifikasi nilai laba bersih otomatis pada periode dengan pemasukan Rp500.000 dan pengeluaran Rp200.000. | Sistem menampilkan nilai laba bersih tepat sebesar Rp300.000 (total pemasukan dikurangi total beban operasional). | Meutia Shafira Ramadhani (Data Science Specialist) |
| 10 | Validasi Integritas: Deteksi Transaksi Ganda | Menginput dua transaksi penjualan dengan nominal, tanggal, dan atribut yang identik secara berturut-turut dalam 1 menit. | Sistem mendeteksi indikasi transaksi duplikat dan memunculkan dialog konfirmasi pencegahan pencatatan ganda. | Aqilla Resya Luthfiya (Data Science Specialist) & Reinald Oryza Apriancahya (AI Full-Stack Developer) |
| 11 | Fitur Pengingat: Tampilan Ringkasan Tagihan Piutang | Mengakses halaman dashboard aplikasi menjelang akhir jam operasional depot air untuk melihat modul piutang. | Modul menampilkan daftar pelanggan yang memiliki piutang aktif secara jelas sebagai pengingat penagihan. | Brian Dicky Vanka Andaraneva (AI Full-Stack Developer) |
| 12 | Responsivitas UI: Tampilan Desktop dan Mobile |Membuka seluruh halaman aplikasi pada peramban laptop (desktop) dan peramban ponsel pintar (layar sempit/mobile). | Seluruh komponen antarmuka, tabel, dan formulir menyesuaikan resolusi layar secara responsif tanpa elemen terpotong. | Brian Dicky Vanka Andaraneva (AI Full-Stack Developer) |

## Pencatatan Hasil Pengujian

Seluruh temuan pengujian fungsional, bug atau anomali sistem, serta verifikasi perbaikan akan dicatat secara terpusat melalui spreadsheet pengujian bersama tim.


