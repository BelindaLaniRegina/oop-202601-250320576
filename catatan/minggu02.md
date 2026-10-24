# Catatan Minggu 2: Struktur OOP: Class, Object, Encapsulation

## Yang saya kerjakan
Saya menjalankan perintah yang terdapat di core/src/main/java/id/ac/upb/asetpinjam/model/Aset.java, seperti membuat class Aset, membuat field private (kode, nama, status, dan kondisi), terus saya juga ada membuat kontruktor dengan validasi null agar nilainya tidak kosong. Selain itu semua, saya juga ada membuat getter untuk membaca data dan setter untuk ubah nama, status, dan validasi biar isinya ga kosong atau ga sesuai.

## Keputusan desain
Saya memakai isBlank() buat memvalidasi kode dan nama biar tidak nerima nilai null, kosong, ataupun hanya berisi spasi. Saya juga ada netapin status awal TERSEDIA, kosisi awal BAIK, dan juga seperti yang saya katakan sebelumnya saya ada memakai getter serta setter.

## Kendala
Ada dioutputnya yang error terus menerus sampai saya bingung kenapa. Ternyata, outputnya error karena ada tanda kurung kurawal ({) yang ganda. Selain hal itu, kendala yang saya alami yaitu saya masih belum terlalu paham mengenai materi encapsulation.

## Penggunaan AI
- Alat yang dipakai: chatGPT
- Bagian yang dibantu AI: Saya dibantu dalam bagian memecahkan masalah pada output yang error
- Prompt utama: Apa yang salah dengan codingannya karena output yang dihasilkan error lalu saya pastekan hasil errornya.
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Saya ada menolak saran yang diberikan oleh ai saat memecahkan masalah errornya. Karena dia menyarankan untuk mengubah bagian yang seharusnya tidak perlu diubah. Lalu saya mengubah dan menjelaskan lebih lanjut kepada AInya sampai akhirnya saya mendapatkan hasil yang saya inginkan
- Satu hal yang saya pahami lebih baik sekarang:
