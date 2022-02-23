My-book adalah aplikasi web yang dapat disesuaikan dengan ponsel, dibuat dengan tumpukan MERN. Dalam aplikasi ini Anda dapat melihat riwayat pinjaman Anda,
memesan buku dan juga membatalkannya. Sisi klien dikembangkan dengan reaksi; backend dengan node dan express;
database adalah mongoDB, diimplementasikan dengan luwak.




LANGKAH-LANGKAH INSTALASINYA.



1). Instalasi basis data:

  
  -Instal mongoDB
  
  -Aktifkan layanan mongoDB
  
  -Buat database bernama "buku saya" di port 27017, Anda dapat mengubah port di file "/backend/app.js".
  
  -Tambahkan buku ke koleksi baru yang disebut "buku" (Satu dokumen untuk setiap buku; dalam file "/backend/json/books.json" Anda dapat menemukan contoh buku dan format setiap dokumen).
  
  
dua). Persiapan Server
  
  
  -Instal nodeJS.
  
  -Jalankan perintah "npm install" di konsol saat berada di /backend/, untuk menginstal dependensi. Pastikan file package.json dan package-lock.json ada di folder.
  
  -Jalankan perintah "node app.js" di console saat berada di lokasi /my-book/ untuk menginisialisasi server pada port 4000 (Harus dijalankan pada port 4000)
  
  
3). Persiapan antarmuka grafis


  -Jalankan perintah "npm install" di konsol saat berada di /my-book/, untuk menginstal dependensi. Pastikan file package.json dan package-lock.json ada di folder.
  
  -Jalankan perintah "npx http-server -o" di konsol saat berada di lokasi /my-book/build untuk menginisialisasi aplikasi.
  
  -Buka di browser http://localhost:8080/.
  
  
4). CERDIK!