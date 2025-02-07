Judul Proyek: Pencari Kata di Kamus

Deskripsi:

Program ini akan membaca sebuah file teks berisi daftar kata yang dipisahkan oleh baris baru, yang berperan sebagai kamus sederhana. Kemudian, program akan meminta pengguna untuk memasukkan kata yang ingin dicari. Program akan mencari kata tersebut dalam kamus menggunakan algoritma pencarian biner rekursif. Jika kata ditemukan, program akan menampilkan pesan "Kata ditemukan!". Jika tidak, program akan menampilkan pesan "Kata tidak ditemukan.".

Fitur:

Membaca kamus dari file: Program akan membaca file teks berisi daftar kata dan menyimpannya ke dalam array/list.
Pencarian kata: Program akan meminta pengguna untuk memasukkan kata yang ingin dicari dan mencarinya dalam kamus.
Pencarian biner rekursif: Program akan menggunakan algoritma pencarian biner rekursif untuk mencari kata dalam kamus secara efisien.
Menampilkan hasil pencarian: Program akan menampilkan pesan yang sesuai, mengindikasikan apakah kata ditemukan atau tidak.
Manipulasi string: Program akan menggunakan fungsi manipulasi string untuk membersihkan input pengguna (misalnya, mengubah menjadi huruf kecil) dan membandingkan kata.
File handling: Program akan membaca kamus dari file dan dapat menyimpan hasil pencarian atau informasi lain ke dalam file (opsional).
Implementasi:

Membaca kamus: Gunakan fungsi open() untuk membuka file kamus dan readlines() untuk membaca setiap baris dan menyimpannya ke dalam list.
Pencarian biner rekursif: Buat fungsi rekursif yang menerima list kata, kata yang dicari, dan indeks awal & akhir sebagai parameter. Fungsi ini akan membandingkan kata yang dicari dengan elemen tengah list. Jika cocok, kembalikan True. Jika lebih kecil, cari di bagian kiri list secara rekursif. Jika lebih besar, cari di bagian kanan list secara rekursif.
Manipulasi string: Gunakan fungsi lower() untuk mengubah input pengguna dan kata dalam kamus menjadi huruf kecil sebelum dibandingkan.
Menampilkan hasil: Gunakan print() untuk menampilkan pesan yang sesuai.
File handling (opsional): Gunakan fungsi write() untuk menyimpan hasil atau informasi lain ke dalam file.
