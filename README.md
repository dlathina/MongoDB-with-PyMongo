# MongoDB-with-PyMongo
MongoDB, PyMongo, NoSQL
### Practice Case ini diberikan oleh Mr Husni.
Anda dapat melihat GitHub beliau  [disini](https://github.com/husnirama).
Anda juga dapat mengunjungi profil linkedin beliau [disini](https://www.linkedin.com/in/husni-ramanda-0b3521108).

## Instruksi untuk mengerjakan Practice Case
Connect cluster pymongo pada link berikut (pilih salah satu yang bisa) :
*   mongodb+srv://userstudent:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true&w=majority
*   mongodb+srv://mongodb-intro:admin1234@cluster0-nnbxe.gcp.mongodb.net/test?retryWrites=true
&w=majority

1. Membuat collection baru dengan nama clean_movies yang sama persis dengan movies collection
pada database sample_mflix dengan memakai collection movies_intial (projecting_queries pymongo)

2. Validasi collection yang telah dibuat dengan parameter sbb :
*   Semua document pada clean_movies dan movie sama
*   Banyak document pada clean_movies dan movie sama
*   Semua fields pada clean_movies ada pada movie
*   Semua value pada clean_movies sama dengan semua value pada movies dengan urutan yang sama

## Kesimpulan dari Practice Case
Kesimpulan yang saya dapatkan dari Practice Case kali ini adalah :


*   Pertama: kita harus melalakukan Install Module PyMongo dan import libraries yang diinginkan.
*   Kedua: kita buat connection dengan cluster yang kita inginkan. 
*   Ketiga: kita bisa menampilkan database pada cluster yang tersedia, dan collection yang kita inginkan pada database. 
*   Keempat: setelah kita menampilkan keys pada sumber data (movies_initial collection) dan movies collection, kita buat pipeline untuk projecting. 
*   Kita harus memastikan bahwa saat membuat pipeline sesuai dengan kebutuhan. Beberapa cara dapat kita lakukan, misalnya renaming, splitting, membuat embeded document, dan matching. 
*   Terakhir, kita dapat melakukan validating. Dengan memastikan bahwa jumlah dokumennya, keys, jumlah keys, values, dan urutannya sama semuanya. 

