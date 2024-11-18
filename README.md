# PRATIKUM 5 
## PENEJELASAN KODE PEMROGRAMAN 

### data_mahasiswa 
- Sebuah dictionary yang menyimpan semua data mahasiswa. 
- Dictionary ini menyimpan informasi mahasiswa, dengan NIM sebagai key dan data mahasiswa(berupa nama, tugas, UTS dan nilai akhir) Sebagai value. 

![Gambar1](SS/ss1.png)

### Fungsi tampilkan_data()
- Fungsi digunakan untuk menampikan data mahasiswa dalam bentuk tabel. 
- Heade tabel menggunakan format string agar data tersusun rapi. 
- Jika data_mahasiswa kosong, maka akan terdapat pesan "Tidak ada data". 
- Menggunakan enumerate() untuk memberikan nomor urut pada data. 

![Gambar 2](SS/ss2.png)

### Fungsi tambah_data()
- Menambahkan data mahasiswa ke dalam dictionary 
- Nilai akhir dihitung dihitung menggunakan rumus NILAI AKHIR = (Tugas x 30%) + (UTS x 35%) + (UAS x 35%)
- Hasil perhitungan nilai akhir disimpan bersama data mahasiswa. 
- Apabila input nilai bukan angka, maka program akan menampilkan pesan error tanpa berhenti.

![Gambar 3](SS/ss3.png)


### Fungsi ubah_data()
- Mengubah data mahasiswa berdasarkan NIM. Program akan mencari data berdasarkan NIM.
- Jika NIM ditemukan fungsi tambah_data() dipanggil untuk mengganti data dengan data baru. 
- Jika NIM tidak ditemukan, muncul pesan "Data tidak ditemukan". 

![Gambar 4](SS/ss4.png)

### Fungsi hapus_data()
- Fungsi ini digunakan untuk menghapus data mahasiswa dari dictionary berdasarkan NIM. 
- Menggunakan fungsi pop() untuk menghapus data mahasiswa. 
- Jika NIM ditemukan, data dihapus, dan muncul pesan "Data berhasil dihapus" 

![Gambar 5](SS/ss5.png)

### Fungsi cari_data()
- Fungsi ini digunakan untuk mencari dan menampilkan detail data mahasiswa berdasarkan NIM. 
- Apabila NIM ditemukan, detail mahasiswa(nama, tugas, UTS, UAS, nilai akhir) ditampilkan. 
- Apabila data tidak ditemukan maka akan muncul sebuah pesan. 

![Gambar 6](SS/ss6.png)

### Fungsi menu()
- Fungsi ini menampilkan menu utama yang memungkinkan kita untuk memilih opsi yang tersedia. 

- Opsi Menu: 
- (L)ihat: Ketik L untuk menampilan data mahasiswa
- (T)ambah: Ketik T untuk menambahkan data baru
- (U)bah: Ketik K Mengubah data berdasarkan NIM 
- (H)apus: Ketik H Menghapus data berdasarkan NIM 
- (C)ari: Ketik C Mencari data berdasarkan NIM
- (K)eluar:Ketik K Mengakhiri program 

- Apabila memilih opsi selain yang disediakan makan input tidak valid. 

![Gambar 7](SS/ss7.png)





