# R3KT-INTENT
### Teori <br>
##### Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum intent dalam aplikasi Android yaitu: <br>
     •	Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
     •	Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task). 
     •	Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut. 

##### Intent memiliki dua bentuk yaitu: <br>
      1. Explicit Intent 
         Adalah tipe Intent yang digunakan untuk menjalankan komponen dari dalam sebuah aplikasi. Explicit intent bekerja dengan menggunakan nama kelas yang dituju misal : com.dicoding.activity.DetailActivity. Umumnya intent ini digunakan untuk mengaktifkan komponen pada satu aplikasi. 
      2. Implicit Intent 
         Adalah tipe intent yang tidak memerlukan detail nama kelas yang ingin diaktifkan. Model ini memungkinkan komponen dari aplikasi lain bisa merespon request intent yang dijalankan. 
         Penggunaan tipe intent ini umumnya diperuntukkan untuk menjalankan fitur/fungsi dari komponen aplikasi lain. Contohnya ketika kita membutuhkan fitur untuk mengambil foto. Daripada membuat sendiri fungsi kamera, lebih baik kita menyerahkan proses tersebut pada aplikasi kamera bawaan dari peranti atau aplikasi kamera lain yang telah terinstal sebelumnya di peranti.
         Hal yang sama misalnya ketika kita membutuhkan fungsi berbagi konten. Kita bisa memanfaatkan intent untuk menampilkan aplikasi mana saja yang bisa menangani fitur tersebut.
         Implementasi implicit intent ini akan sangat memudahkan bagi pengembang agar tetap fokus pada proses bisnis inti dari aplikasi yang dikembangkan.
         
         <br>
         
### Latihan Praktikum Intent <br>
Praktikum ini menitikberatkan pada implementasi intent untuk melakukan perpindahan dari activity ke activity lain, dengan atau tidak membawa data. Beberapa bagian dari praktikum ini akan menjawab beberapa pertanyaan umum dalam pengembangan aplikasi Android sebagai berikut: <br>
1. Bagaimana berpindah dari satu activity ke activity lain? <br>
2. Bagaimana berpindah dari satu activity ke activity lain dengan membawa data? <br>
3. Single value dari suatu variabel. <br>
4. Obyek model Plain Old Java Object (POJO). <br>
5. Menjalankan komponen di aplikasi lain untuk keperluan membuka browser atau melakukan pemanggilan melalui aplikasi telepon bawaan? <br>
6. Mengirimkan hasil nilai balik melalui Intent. <br>

### Logika Dasar <br>
Berpindah dari satu Activity ke Activity lain dengan membawa data. Activity asal akan mengirimkan data melalui Intent dan Activity tujuan akan menerima data yang dikirimkan. <br>

### Hasil Run <br>
![Alt Text](https://github.com/adam033/R3KT-INTENT/blob/master/Screenshot%20(276).png) <br>
Gambar diatas merupakan interface pertama dari hasil run project yaitu terdapat tombol yang nanti akan kita program apabila kita klik maka akan pindah ke activity lain.
<br>
![Alt Text](https://github.com/adam033/R3KT-INTENT/blob/master/Screenshot%20(277).png) <br>
Gambar diatas merupakan activity yang kedua hasil dari interaksi button yang terdapat pada interface yang pertama. <br>

### Untuk Selengkapnya Cek File Di Atas
##### Semoga Bermanfaat @admhmwan



      

