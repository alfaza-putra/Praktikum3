# Praktikum3
Praktikum 3
•	Implementasikan penggunaan constraint foreign key pada semua table yang berelasi 
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss1.jpeg)

•	Lakukan penambahan pada data table dengan mengisi kd_ds yang belum ada pada data dosen
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss2.png)

•	Hapus satu record data pada table dosen yang telah dirujuk pada table mahasiswa
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss3.png)

•	Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRIC
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss4.png)

•	Lakukan perubahan data pada table dosen (kd_ds)
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss5.png)

•	Lakukan penghapusan data pada table dosen
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss6.jpeg)

•	Ubah menjadi ON UPDATE CASCADE ON DELETE SET NULL
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss7.png)

•	Menghapus data pada table dosen
![output](https://github.com/alfaza-putra/Praktikum3/blob/main/screnshootpraktikum3/ss8.png)


Pertanyaan :

Apa bedanya penggunaan RESTRIC dan penggunaan CASCADE !

•	Restrict merupakan perubahan data dan penghapusan data tidak diijinkan pada table referensi (parent table) apabila pada table child sudah ada yang merujuk pada data tersebut, Sedangkan
Cascade merupakan perubahan atau penghapusan data pada table referensi (parent table) akan di ikuti oleh table child

Kesimpulan ;

•	Dalam penulisan sebuah query SQL, dengan menggunakan constraint, kita dapat menghindari kesalahan penulisan data, sehingga konsistensi dan integritas dari sebuah data dapat terjaga dengan baik untuk digunakan pada proses selanjutnya. performa dari database juga dapat ditingkatkan karena dengan adanya constraint, maka jumlah kesalahan yang mungkin terjadi dapat berkurang. Salah satu keuntungan lainnya adalah dapat mencegah pengguna lain untuk memasukkan data yang tidak sah pada kolom tertentu.
		
