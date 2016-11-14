Membuat Method dan Class Retrive Data Geospasial

Latar Belakang :
Penggunaan Sistem Informasi Geografis, terbilang masih minim tentang pengetahuan dan bagaimana cara memanipulasi data retrive. Untuk itu diperlukan pemahaman yang baik untuk bisa mengerti tata cara seperti itu. Berikut ada beberapa hal yang akan saya bahan tentang manipulasi data dengan shapefile geospasial menggunakan bahasa program phyton dan juga bagaimana cara pemakaian class dan method tersebut.
1.	Apa yang di maksud retrive data?
2.	Apa itu Shapefile?
3.	Bagaimana Operasi Pengambilan data?
4.	Membuat class geospasial!
5.	Membuat Method Select, dimana negara?
 Pembahasan :
-	Retrive Data biasanya juga disebut sebagai Retrive atau meretrive data vektor.  biasanya digunakan untuk melihat data/ menghitung  jumlah data. 
-	Shapefile adalah suatu standar file vektor geospasial yang dikeluarkan oleh ESRI
Shapefile sendiri terbagi menjadi 2  yaitu .shp data geometri dan .dbf basis data
-	Operasi untuk pengambilan data 
Method DBF 
Fields    -    record(n)   -     Record(n) baris ke(n) records
Method SHP
Shapes()Menampilkan semua    -    shape(n) menampilkan dengan parameter.
Bbox,parts,point S, shape type

Bbox merupakan batas tampilan atau view pada peta seperti misalnya pada gambar dibawah ini :

                       Pada koodinat a,b,c,d disebut Bbox

Points yaitu koodinat pada pembentukan peta
Shapefile yaitu jenis geometri yang dari points.

1.	Menampilkan Jumlah Record dengan menggunakan terminal
 
 
2.	Menampilkan record py shp
 

Kesimpulan yang saya dapat dari materi tersebut adalah terdapat kesulitan dalam memahami namun di perlukan ketelitian dalam penggunaan dan pengerjaan tentang retrive data tersebut.

       
