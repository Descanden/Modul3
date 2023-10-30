# Modul3

Program Java di atas adalah sebuah kalkulator sederhana yang memungkinkan pengguna untuk memasukkan dua angka dan memilih operasi matematika (tambah, kurang, kali, atau bagi) yang ingin dilakukan pada dua angka tersebut. Program kemudian menghitung hasil operasi dan menampilkannya kepada pengguna.

Deskripsi langkah-langkah kerja program tersebut adalah sebagai berikut:

1. Program dimulai dengan mengimpor kelas `Scanner` untuk memungkinkan input dari pengguna melalui konsol.


2. Pengguna diminta untuk memasukkan dua angka pertama, yaitu `angka1` dan `angka2`, dan operasi matematika yang diinginkan, yaitu `operasi`. Angka-angka ini disimpan dalam variabel dan operasi disimpan dalam bentuk string.


3. Program menggunakan struktur `switch` untuk memilih operasi yang diminta oleh pengguna. Terdapat empat pilihan operasi: tambah, kurang, kali, dan bagi.


4. Jika operasi yang dipilih adalah "tambah," program akan menjumlahkan `angka1` dan `angka2` dan menyimpan hasilnya dalam variabel `hasil`.


5. Jika operasi yang dipilih adalah "kurang," program akan mengurangkan `angka1` dari `angka2` dan menyimpan hasilnya dalam variabel `hasil`.


6. Jika operasi yang dipilih adalah "kali," program akan mengalikan `angka1` dan `angka2` dan menyimpan hasilnya dalam variabel `hasil`.


7. Jika operasi yang dipilih adalah "bagi," program akan memeriksa apakah `angka2` tidak sama dengan 0. Jika iya, program akan membagi `angka1` dengan `angka2` dan menyimpan hasilnya dalam variabel `hasil`. Jika `angka2` sama dengan 0, program akan menampilkan pesan kesalahan karena tidak bisa membagi dengan nol.


8. Jika operasi yang dimasukkan oleh pengguna tidak sesuai dengan keempat pilihan yang ada ("tambah," "kurang," "kali," atau "bagi"), program akan menampilkan pesan kesalahan bahwa operasi tidak valid.


9. Terakhir, program akan menampilkan hasil operasi matematika yang dilakukan kepada pengguna dengan menggunakan operasi matematika yang diminta dan nilai hasil yang dihitung.


10. Setelah selesai, program akan menutup objek `Scanner` yang digunakan untuk input.

Program ini adalah contoh sederhana penggunaan pengkondisian `switch` dalam bahasa pemrograman Java untuk melakukan operasi matematika berdasarkan pilihan pengguna. Program ini memungkinkan pengguna untuk melakukan perhitungan matematika dasar dengan mudah melalui konsol.