# PBOPertemuan6
Dalam pengembangan aplikasi berbasis desktop, Java menyediakan pustaka Swing untuk membangun antarmuka pengguna (GUI). Salah satu kebutuhan umum dalam sistem manajemen data adalah melakukan operasi CRUD (Create, Read, Update, Delete) pada database. Untuk menjaga kerapian tampilan dan memisahkan fungsi, Java Swing mendukung penggunaan JDialog sebagai jendela tambahan selain JFrame utama.

Pada praktikum ini, dilakukan perancangan sebuah aplikasi sederhana untuk mengelola data minuman. JFrame utama menampilkan data dalam bentuk tabel, sedangkan operasi Insert, Update, dan Delete dilakukan melalui Swing Windows JDialog yang dipanggil dari tombol pada JFrame utama.

# Tujuan
1.	Mempelajari cara menambahkan JDialog pada JFrame menggunakan Swing Windows.  
2.	Mengimplementasikan fungsi CRUD dengan dialog terpisah untuk insert, update, dan delete.  
3.	Menampilkan data dari database PostgreSQL ke JTable.  
4.	Membuat validasi pada saat update dan delete (data harus dipilih dulu dari tabel).  

# Teori Singkat
1.	Java Swing  
Merupakan toolkit GUI di Java yang menyediakan komponen seperti JFrame, JButton, JTable, dan JDialog.  

2.	JFrame  
Merupakan jendela utama aplikasi GUI yang menjadi container utama.  

3.	JDialog  
Jendela tambahan (popup window) yang digunakan untuk input, konfirmasi, atau pesan tertentu. Pada praktikum ini digunakan untuk operasi Insert, Update, Delete.  

4.	Database & JDBC  
PostgreSQL digunakan sebagai database penyimpanan.  
JDBC (Java Database Connectivity) digunakan untuk menghubungkan Java dengan PostgreSQL melalui class Connection, Statement, dan PreparedStatement.  

5.	CRUD  
1.	Create (Insert) → menambah data ke database.  
2.	Read (Select) → membaca data dari database dan ditampilkan ke JTable.  
3.	Update → mengubah data tertentu berdasarkan ID.  
4.	Delete → menghapus data tertentu berdasarkan ID.  


