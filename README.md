# Enhanced for Loop dan Enhanced If Statement dalam Java

        Enhanced For Loop (For-Each Loop)
        
        Enhanced for loop dikenal sebagai perulangan for-each. for each loop digunakan untuk melakukan iterasi melalui elemen array atau koleksi di Java. Ini menyederhanakan sintaksis for loop tradisional dan menghilangkan kebutuhan akan manajemen indeks manual, membuat kode Anda lebih mudah dibaca dan mengurangi rawan kesalahan.

contoh dimana enhanced for loop tidak bisa digunakan
1. for loop hanya bisa membaca array tetapi tidak bisa mengubah array
2. for loop tidak bisa mengulangi koleksi yang bisa diubah jika itu terjadi maka dapat memicu ConcurrentModificationException
3. for loop juga tidak mendukung pengulangaan atau looping atau percabangan bersyarat.

# Enhanced If Statement (Ternary Operator)

        If statement digunakan untuk mengevaluasi ekspresi boolean. Jika ekspresi tersebut bernilai true, maka blok kode di dalam if statement akan dieksekusi. Jika ekspresi tersebut bernilai false, maka blok kode di dalam if statement akan dilewati.Juga enhanced if loop digunakan untuk mengulang elemen dalam array atau collection di Java. Dibandingkan dengan for loop tradisional, enhanced if loop tidak memerlukan variabel counter dan eksplisit incrementasi, sehingga lebih mudah dibaca dan ditulis.

contoh dimana enhanced if loop tidak bisa digunakan
1. enhanced if loop tidak bisa digunakan dalam penggabungan sebuah statement
2. Enhanced if statement hanya dapat digunakan di satu baris. Jika akan membuat pernyataan bersyarat yang lebih panjang dan kompleks, kita perlu menggunakan pernyataan if-else.
3. enhanced for loop juga bisa error atau tdk bisa digunakan ketika pemakai menggunakan pernyataan yang kompleks dan memiliki terlalu banyak percabangan

Jadi kesimpulannya adalah enhanced for loop dan enhanced if statement menyederhanakan kode Java. For each loop mengulangi elemen array/collection tanpa counter, sedangkan ternary operator mengevaluasi ekspresi boolean dan mengembalikan dua nilai berbeda dalam satu baris. Keduanya memiliki kekurangan, jadi gunakanlah dengan tepat. dan jika keduanya digunakan dengan benar dan sesuai syarat maka java bisa berjalan dengan baik dan benar.