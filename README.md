# MongoDB with Pymongo
### by Putri Bunga Rahmalita
------------------------------
Pada file ini akan dilakukan practice case dengan menggunakan pymongo. PyMongo sendiri merupakan distribusi Python yang berisi tools untuk bekerja dengan MongoDB, dan merupakan cara yang disarankan untuk bekerja dengan MongoDB dari Python.<br><br>

Practice yang akan dilakukan adalah dengan cara membuat collection baru dengan nama clean_movies yang sama persis dengan movies collection pada database sample_mflix dengan memakai collection movies_intial (projecting_queries pymongo). Setelah itu, akan divalidasi collection yang telah dibuat dengan parameter sebagai berikut :
- Semua document pada clean_movies dan movie sama,
- Banyak document pada clean_movies dan movie sama, 
- Semua fields pada clean_movies ada pada movie,
- Semua value pada clean_movies sama dengan semua value pada movies dengan urutan yang sama <br>
----------------------------
Berikut adalah beberapa langkah yang dapat dilakukan untuk melakukan practice case ini :<br><br>
1. Connect cluster pymongo pada link berikut (pilih salah satu yang bisa) : <br>
• mongodb+srv://userstudent:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true&w=majority  <br>
• mongodb+srv://mongodb-intro:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true&w=majority <br>
• mongodb+srv://admin1234:12345@cluster0-miqju.gcp.mongodb.net/test?retryWrites=true&w=majority <br><br>

Saya connect pada cluster pymongo mongodb+srv://admin1234:12345@cluster0-miqju.gcp.mongodb.net/test?retryWrites=true&w=majority <br><br>
2. Mengeksplorasi movies_initial *collection* dan movies *collection* <br>

3. Menyamakan (Matching) dokumen yang ada pada movies_initial *collection* dan movies *collection* untuk melihat perbedaan dari kedua *collection*<br>

4. Melakukan *pipeline aggregation* dan *projecting queries* untuk membuat dokumen pada movies_initial *collection* dan movies *collection* menjadi sama<br>
5. Melakukan *validation* terhadap movies_initial *collection* dan movies *collection* untuk mengetahui apakah dokumen benar-benar sama atau ada yang berbeda<br>
6. Kesimpulan
