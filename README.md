# PHP7yang1-2Alya
# Hasil
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/1.jpg)
# Setelah klik Simpan
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/2.jpg)
# Setelah klik lihat data
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/3.jpg)
# Setelah klik Edit
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/4.jpg)
# Mengubah Nama dosen
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/5.jpg)
# Setelah klik simpan
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/6.jpg)
# Hasil
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/7.jpg)
# Klik hapus
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/8.jpg)
# Klik lihat data 
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/9.jpg)
# Hasil
![alt text](https://github.com/AlyaSelviaTamzila/PHP7yang1-2Alya/blob/master/10.jpg)


1. Berikan contoh kode keneksi untuk ke database pd php?

  =>$connect = mysqli_connect($host, $uname, $pass, $db);
  
    mysqli_connect() adalah extension yang digunakan php untuk membuat koneksi dengan database .
    
2. Bagaimana cara anda membuat database pada phpMySQl!

  => contohnya kodingannya:
  
     $result = mysqli_query($connect, $query);
     
     Keterangannya fungsi mysql_query() untuk membuat database MySQL, fungsi ini membutuhkan dua parameter dan 
     
     mengembalikan nilai TRUE jika berhasil atau FALSE jika gagal.
     
3. Berikan code query untuk menampilkan sebuah data yang ada pada ke database?

  =>$query = "SELECT * FROM dosen WHERE id_dosen = $id_dosen";
  
4. Berikan code query untuk mengupdate sebuah data yang ada pada ke database?

  =>$query = "UPDATE dosen SET nama_dosen = '$nama_dosen', telp = '$telp' WHERE id_dosen = $id_dosen";
  
5. Berikan code query untuk menghapus sebuah data yang ada pada ke database?

  =>$query = "DELETE FROM dosen WHERE id_dosen = $id_dosen";
