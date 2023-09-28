# Lab1Web

Jawab Pertanyaan Berikut
### 1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

adanya tambahan tag "hr" yg tidak perlu

### 2. Apa perbedaan dari tag p dengan tag br, berikan penjelasannya!

* Tag "p" berfungsi untuk memberi perintah paragraf baru pada halaman html, antara baris atau paragraf terbentuk jarak.
* Tag "br" dituliskan pada kerangka html untuk memberikan perintah "break line", artinya meng intruksikan baris baru. tag ini adalah tag tunggal tanpa diawali tag pembuka dan diakhiri tag penutup. Ia berdiri sendiri

  perbedaan dari keduanya yang mencolok adalah kedua tag ini adalah pada jarak yang terbentuk.
  Kesimpulannya jika hanya ingin membuat baris baru tanpa jarak gunakan tag "br" , tapi jika ingin membuat baris baru namun memiliki jarak dengan paragraf diatasnya maka bungkuslah paragraf baru tersebut dengan sepasang tag "p"

### 3. Apa perbedaan atribut title dan alt pada tag "img", berikan penjelasannya!

* Alt Tag, adalah singkatan dari Alternative Tag. Lalu ada juga yang menyebutnya dengan Alternative Text atau Alt Text. Pengertiannya adalah keterangan singkat sebuah gambar yang terdapat pada sebuah blog atau website. Keterangan itu berfungsi untuk memberi tahu robot mesin pencari tentang keberadaannya. Sama dengan radar yang memancarkan sinyal. Selain untuk memberi tahu robot, juga untuk menberi tahu pada pengunjung ketika sebuah gambar tidak berhasil diload oleh browser, baik karena jaringan lelet maupun karena gambar tersebut telah dihapus di sumbernya dimana gambar itu tersimpan di internet.

* Title Tag adalah balon teks yang muncul saat sebuah gambar disentuh kursor mouse tanpa diklik. Fungsinya juga sama, yaitu untuk memberi tahu robot mesin pencari tentang keberadaannya. Dan juga untuk memberi tahu pengunjung. 
   
### 4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

Sebenarnya mengisi salah satunya atau keduanya juga tidak masalah, tetapi jika hanya ingin mengecilkan atau memperbesar gambar secara proporsional bisa isi salah satunya saja yaitu width, nanti heightnya akan menyesuaikan secara otomatis gambarnya.
kecuali memang ingin merubah secara spesifik terkait ukuran gambarnya bisa menggunakan keduanya.

### 5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

Atribut ini mempengaruhi cara halaman baru akan dibuka ketika tautan tersebut diklik, yg terjadi adalah:

* _blank:
Ketika atribut target diatur ke "_blank", tautan akan membuka halaman baru dalam jendela atau tab baru (tergantung pada pengaturan peramban pengguna).
Halaman baru ini tidak akan menggantikan atau menimpa halaman asal tempat tautan itu ditempatkan.

* _self:
Atribut target "_self" adalah nilai default jika atribut target tidak didefinisikan.
Jika tautan menggunakan atribut "_self", halaman baru akan terbuka di jendela atau tab yang sama seperti halaman tempat tautan itu ditempatkan.

* _top:
Ketika atribut target diatur ke "_top", tautan akan membuka halaman baru dan menggantikan halaman paling atas atau paling tinggi dari hierarki jendela atau bingkai saat ini.
Dengan kata lain, jika ada beberapa bingkai atau jendela, tautan akan memuat halaman baru di jendela atau bingkai teratas.

* _parent:
Jika halaman web memiliki bingkai atau bingkai induk, atribut target "_parent" akan membuka halaman baru di bingkai yang mengandung tautan itu.
Jika halaman web tidak menggunakan bingkai, maka _parent akan berperilaku seperti "_self" (membuka di jendela atau tab yang sama).
