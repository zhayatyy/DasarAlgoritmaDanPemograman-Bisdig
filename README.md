**SISTEM E-COMMERCE**
Struktur kontrol percabangan (if statement) digunakan untuk mengambil keputusan berdasarkan kondisi tertentu. Dalam kasus ini, kita akan mengecek apakah total belanja lebih dari Rp500.000. Jika iya, maka pelanggan mendapatkan diskon 10%, jika tidak, maka tidak ada diskon.
Program ini menghitung total bayar setelah pemberian diskon 10% jika pelanggan berbelanja lebih dari Rp500.000. Program menggunakan struktur kontrol percabangan `if` dalam Python untuk memeriksa syarat diskon.

Cara Menjalankan
1. Jalankan program.
2. Masukkan total belanja.
3. Program akan menampilkan total bayar dengan atau tanpa diskon sesuai ketentuan.

**RATA-RATA NILAI SISWA**
Penjelasan Tipe Data dan Operator:
Dalam perhitungan rata-rata dan pengecekan kelulusan, tipe data yang digunakan adalah:
Integer (int) untuk menyimpan nilai ujian yang dimasukkan.
Float (float) untuk menghitung rata-rata agar hasilnya bisa mencakup desimal.
Boolean (bool) dan operator logika digunakan untuk menentukan apakah siswa lulus atau tidak berdasarkan syarat tertentu.

Operator yang digunakan:
Operator aritmatika: +, / untuk menjumlahkan dan membagi nilai.
Operator pembanding: >= untuk mengecek apakah rata-rata nilai memenuhi syarat kelulusan (≥ 75).

**FUNGSI UNTUK MENGHITUNG FAKTORIAL**
Penjelasan Fungsi Rekursif untuk Menghitung Faktorial:
Manfaat Penggunaan Fungsi
Penggunaan fungsi dalam pemrograman, terutama fungsi rekursif, memiliki beberapa manfaat:
Kode lebih ringkas dan mudah dipahami untuk masalah yang bersifat rekursif secara alami seperti faktorial, deret Fibonacci, dan traversing struktur pohon.
Mempermudah pemecahan masalah kompleks menjadi sub-masalah yang lebih kecil dan serupa (divide and conquer).
Mengurangi pengulangan kode karena proses berulang ditangani oleh pemanggilan fungsi itu sendiri.

Cara Kerja Rekursi dalam Menghitung Faktorial
Rekursi bekerja dengan memanggil fungsi itu sendiri hingga mencapai kondisi dasar (base case). Pada kasus faktorial, definisi matematisnya adalah:
Faktorial dari 0 adalah 1 (0! = 1)
Faktorial dari n (n > 0) adalah n × (n-1)!

**NILAI TERTINGGI DARI 5 SISWA**
Program Cari Nilai Tertinggi
Program ini digunakan untuk menerima input nilai dari 5 siswa, lalu mencari dan menampilkan nilai tertinggi serta siswa yang mendapatkannya.
Penjelasan
- List (`array`) digunakan untuk menyimpan data nilai siswa.
- Perulangan (`for`) digunakan untuk input nilai dan pencarian nilai tertinggi.

Contoh Input:
Nilai siswa: 80, 90, 85, 70, 95

Output:
Nilai tertinggi adalah: 95  
Didapatkan oleh siswa ke-5

**MENGHITUNG TOTAL PEMBELIAN 3 BARANG**
Langkah-langkah Algoritma:
Mulai (Start) – Program dimulai.
Input harga barang – Pengguna diminta untuk memasukkan harga tiga barang satu per satu.
Hitung total – Program menjumlahkan ketiga harga tersebut.
Tampilkan total – Program menampilkan hasil total harga yang telah dihitung.
Selesai (End) – Program selesai dijalankan.
penjelasan program
Penjelasan baris per baris:
float(input(...)): Mengambil input dari pengguna dan mengubahnya ke dalam bentuk angka desimal (float), supaya bisa menghitung nilai yang mengandung sen (misalnya Rp10.500,50).
total = barang1 + barang2 + barang3: Menjumlahkan ketiga harga barang.
print(...): Menampilkan total harga dengan format dua angka di belakang koma (misalnya Rp12345.67).
