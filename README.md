# Lab1Web
NAMA  : Muhammad Rifqi aziz

NIM   : 312210111

KELAS : TI.22.A.1
# Langkah-langkah Praktikum
Persiapan membuka VSCode dan Browser.

![10](https://github.com/iki020904/Lab1Web/assets/115804283/778de9b5-c752-440c-b80f-0e021fa27ac8)

Kemudian buat file baru dengan nama lab1_tag_dasar.html dan tambahkan tag dasar dokumen HTML.

![html1](https://github.com/iki020904/Lab1Web/assets/115804283/ff123d08-71cc-4f68-895c-ad9b7497f435)

Kemudian selanjutnya, buka file tersebut pada web browser misalnya Mozilla Firefox.

![html 2](https://github.com/iki020904/Lab1Web/assets/115804283/3b6e36db-c251-4c26-9138-b2eb0fcde999)

### 1. Membuat Paragraf

![html 4](https://github.com/iki020904/Lab1Web/assets/115804283/5017b4da-dac1-4d36-86e0-62322720ab45)

### 2. Menambahkan Judul
    <!--judul paragraf pertama-->
        <h1>Belajar Dasar HTML</h1>
     <!--judul paragraf kedua-->
            <h2>Paragraf Pada HTML</h2>

![html 5](https://github.com/iki020904/Lab1Web/assets/115804283/6b76e8ed-75e8-485e-93f3-fe2f70dee723)

### 3. Memformat teks
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada
penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.

![html 7](https://github.com/iki020904/Lab1Web/assets/115804283/696ce322-9679-46b8-80d5-650cf08514d4)


### 4. Menyisipkan Gambar
Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian
simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan
gambar dari website external.

      <!-- sub judul paragraf -->
          <h3>Menambahkan Gambar</h3>
      <!-- menambahkan gambar pada dokumen -->
          <img src="Logo_UPB.png" title="Logo Univeritas Pelita Bangsa">
    

Simpan perubahannya, kemudian refresh browser.

![html 8](https://github.com/iki020904/Lab1Web/assets/115804283/b9996f91-b966-4844-b1ec-995880dfa7b4)

### 5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

        <!-- menambahkan link navigasi -->
        <nav>!
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
        </nav>
        <hr>


![html 9](https://github.com/iki020904/Lab1Web/assets/115804283/4a9847c8-0ba9-48a9-929f-a6b141768fb7)



## Pertanyaan 
### 1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
~ Ya, kesalahan penulisan tag dalam kode HTML dapat menyebabkan error atau masalah dalam halaman web. Kesalahan tersebut dapat mencakup tag yang tidak ditutup dengan benar, tag yang tidak valid, atau atribut yang salah

### 2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya! 
~ Tag HTML `<p>` dan `<br>` memiliki perbedaan dalam penggunaan dan efek yang mereka miliki 
  dalam tata letak halaman web:
 1. `<p>` (Paragraph):
   - `<p>` digunakan untuk mengelompokkan teks menjadi paragraf atau blok teks.
   - Ini akan menambahkan jarak paragraf di atas dan di bawah teks yang ada, menciptakan 
     ruang vertikal yang signifikan.
   - Contoh penggunaan: `<p>Ini adalah paragraf pertama.</p> <p>Ini adalah paragraf kedua 
    </p>`
 2. `<br>` (Line Break):
   - `<br>` digunakan untuk membuat jeda baris tunggal dalam teks, yang berarti teks akan berlanjut di 
     baris berikutnya tanpa membuat paragraf baru.
   - Ini hanya menciptakan jeda baris dan tidak menambahkan spasi vertikal tambahan.
   - Contoh penggunaan: `Ini adalah baris pertama.<br>Ini adalah baris kedua.
Jadi, intinya adalah `<p>` digunakan untuk mengelompokkan teks menjadi paragraf dengan jarak vertikal, sementara `<br>` hanya digunakan untuk membuat jeda baris dalam teks tanpa menambahkan jarak vertikal tambahan.

### 3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
~ Atribut `title` dan `alt` dalam tag HTML `<img>` memiliki perbedaan dalam tujuan dan penggunaan mereka:
  1. Atribut `alt` (Alternative Text):
   - Atribut `alt` digunakan untuk memberikan teks alternatif atau deskripsi gambar.
   - Ini memiliki peran penting dalam aksesibilitas web, karena digunakan oleh pembaca layar untuk 
     membantu pengguna yang memiliki masalah penglihatan memahami konten gambar.
   - Jika gambar tidak dapat ditampilkan (misalnya, jika berkas gambar tidak dapat dimuat), teks `alt` 
     akan muncul sebagai teks pengganti.
   - Contoh penggunaan: `<img src="gambar.jpg" alt="Sebuah gambar bukit yang indah">`

   2. Atribut `title`:
   - Atribut `title` digunakan untuk memberikan informasi tambahan atau tooltip ketika pengguna 
     mengarahkan kursor mouse ke gambar.
   - Ini tidak memiliki dampak pada aksesibilitas web, tetapi dapat memberikan informasi tambahan kepada 
     pengguna tentang gambar tersebut.
   - Contoh penggunaan: `<img src="gambar.jpg" alt="Sebuah gambar bukit yang indah" title="Pemandangan 
     bukit di musim panas">`

     Jadi, perbedaan utama adalah bahwa `alt` digunakan untuk memberikan teks alternatif untuk gambar dan 
     penting untuk aksesibilitas, sementara `title` digunakan untuk memberikan informasi tambahan yang 
     muncul sebagai tooltip saat pengguna mengarahkan kursor mouse ke gambar.

### 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
~ Untuk mengatur ukuran gambar dalam HTML, dapat menggunakan atribut `width` (lebar) dan `height` (tinggi). Agar tampilan gambar tetap proporsional, sebaiknya mengisi hanya salah satu dari kedua atribut tersebut, biasanya `width` atau `height`, sementara yang lainnya akan dihitung secara otomatis oleh browser.
Ini dilakukan karena gambar memiliki rasio aspek (aspect ratio), yang merupakan perbandingan antara lebar dan tingginya. Jika mengisi baik `width` maupun `height`, tanpa memperhatikan rasio aspek gambar, gambar tersebut dapat terlihat terdistorsi atau tidak proporsional.

### 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
~ 1. `_blank`:
   - Ketika `target="_blank"` digunakan, tautan akan membuka halaman yang ditautkan dalam tab atau 
     jendela browser baru, terpisah dari halaman asal. Ini berguna ketika Anda ingin menjaga pengguna 
     tetap di halaman asal dan membuka tautan eksternal atau tautan yang tidak ingin menggantikan halaman 
     asal.

  2. `_self`:
   - Ini adalah nilai default untuk atribut `target`. Ketika `target="_self"` digunakan, tautan akan 
     membuka halaman yang ditautkan di jendela atau tab yang sama di mana halaman asal berada. Ini 
     berarti halaman asal akan digantikan dengan halaman yang baru.

  3. `_top`:
   - Ketika `target="_top"` digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab 
     paling atas atau paling tinggi dalam tumpukan jendela browser. Jadi, jika halaman asal ada dalam 
     bingkai (frame), tautan akan membuka halaman baru di luar bingkai tersebut.

  4. `_parent`:
   - `target="_parent"` digunakan ketika halaman web memiliki bingkai (frame) yang saling terkait. Ini 
     akan membuka tautan di jendela atau tab yang menggantikan bingkai "induk" yang berisi tautan 
     tersebut.


     ## Finish, Terima Kasih 




    


