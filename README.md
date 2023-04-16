# Regression-Analytic-ICE-CREAM-Revenue
you can read my medium https://github.com/Ryan77Ariesta/Regression-Analytic-ICE-CREAM-Revenue
1. Introduction
Artikel ini akan membahas menganalisa jika kita memiliki bisnis ice cream dan kita ingin membuat model prediksi terkait dnegan daily revenue (dalam dollar) based on temperatur udara luar. dimana kita akan memutuskan bahwa model linear regresi dapat menjadi salah satu optional yang baik untuk menyelesaikan masalah.
Independant variable X: Temperatur udara luar
Dependant variable Y: keseluruhan daily revenue dalam dollar

2. Dataset
Sebelum masuk masuk kedalam metode regression, mari lakukan analisa statistik dasar untuk melihat bagaimana data yang akan diolah nantinya dengan menggunakan fungsi describe.
3. Statistical Test
dengan fungsi describe dapat memberikan gambaran tentang jumlah data, rata-rata, std deviasi , min max hingga persentil dari data, sebagai contoh sebagai berikut
lalu dengan menggunakan sns dan pembuatan grafic scatter plot dapat dilihat bahwa ada keterkaitan / korelasi yang cukup kuat antara revenue vs temperatur udara luar

4. Regression Model
lalu setelah dataset sudah dimaksukan maka menggunakan sklearn model untuk mencari linear model coeficient (M) dan (B) yang di dapat seperti pada gambar di bawah ini
lalu model dijalankan dan menghasilkan data trainning sebagai berikut:
setelah mendapatkan hasil training kemudian kita melakukan testing pada sumbu Y lalu mengukur nya dengan data actual dan melihat korelasinya atau keterkaitannya dengan data actual yang ada 
5. Conclusion
dari hasil trainning dan testing dalam grafic scatterplot dapat disimpulkan model regresi dapat di terima dan selanjutnya dapat digunakan untuk melakukan prediction jika diberikan temperatur dengan suhu tertentu dapat menghasilkan revenue berapa , sperti pada contoh di bawah ini:
ketika diberikat sampel T atau temperature 30 maka dapat menghasilkan revenue sebesar 687,1
-Ryan Ariesta-
