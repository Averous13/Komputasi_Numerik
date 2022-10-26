# Komputasi_Numerik
Nama Kelompok :

Muhammad Adib Syambudi (5025211017)
Ilham Insan Wafi (5025211255)
Yusna Millaturrosyidah (5025211254)
Dengan menggunakan dua library dari phython yaitu numpy dan matplotlib. Variabel yang digunakan a,b,c,d untuk variabel pada fungsi. Kemudian xl adalah input batas bawah dan xu adalah input batas atas. Terdapat juga variabel error dan toleransi, dimana kedua variabel ini digunakan sebagai acuan berjalan iterasi. Kemudian menyimpan titik-titik x pada xlist dan hasil perhitungan fungsi x ke dalam ylist.

Kemudian langkah-langkah algoritma bolzano sebagai berikut :

Mengecek fungsi dengan batas bawah dikali dengan batas atas. Jika hasilnya positif maka hasil terdapat pada rentang yang dimasukkan,
Perulangan proses selama memiliki nilai error diatas nilai toleransi.
Menggunakan rumus xr = (xl + xu )/2
Mencetak nilai dari xr.
Mengubah nilai error dengan rumus nilai mutlak dari ((xr - xr_lama)/xr) * 100
Jika hasil dimasukkan ke fungsi dikali dengan batas atas bernilai negatif, maka xr menjadi batas bawah. Selain itu, maka xr menjadi batas atas.
Proses yang diulang adalah NO 3 sampe 6.
Menggambar grafik dengan menggunakan plot dengan memasukkan xlist dan ylist.
Menggeser garis sumbu x ke tengah dan memberi judul.
Menampilkan grafik fungsi
