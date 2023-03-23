# Minggu 1
## 1. Whetting Your Appetite

"Whetting Your Appetite" adalah bagian dari tutorial resmi [Python](https://python.org). Bagian ini memberikan pengantar singkat tentang [Python](https://python.org) dan menyajikan beberapa contoh sederhana tentang cara menggunakan bahasa pemrograman ini.

Pada point 1 dari "Whetting Your Appetite", dijelaskan tentang sejarah [Python](https://python.org) dan fitur utama yang membuat bahasa pemrograman ini populer. Bahasa [Python](https://python.org) pertama kali diciptakan pada awal 1990-an oleh [Guido van Rossum](https://id.wikipedia.org/wiki/Guido_van_Rossum) dan sekarang merupakan bahasa pemrograman yang sangat populer di kalangan pengembang perangkat lunak. [Python](https://python.org) adalah bahasa pemrograman yang mudah dipelajari dan kuat, yang juga sangat populer di kalangan pemula dan profesional. Python memiliki sintaks yang mudah dibaca dan dipelajari, sehingga menjadi bahasa pemrograman yang populer di kalangan pemula dan profesional.

Selanjutnya, fitur utama [Python](https://python.org) dipaparkan, seperti dukungan untuk tipe data yang dinamis, dukungan untuk pemrograman berorientasi objek, dan kemampuan untuk menangani eksepsi atau error. Python juga memiliki banyak modul dan pustaka yang tersedia, yang membuatnya mudah digunakan dalam berbagai bidang seperti pemrograman web, ilmu data, dan pengembangan game.

Bagian "Whetting Your Appetite" ini merupakan pengantar singkat tentang [Python](https://python.org) dengan tujuan memberikan pengguna pemula gambaran tentang sintaks dasar dan cara kerja [Python](https://python.org). Bagian ini juga dapat menjadi referensi yang berguna bagi pengguna yang lebih berpengalaman yang ingin mengingat kembali konsep dasar [Python](https://python.org). Dalam keseluruhan, "Whetting Your Appetite" adalah pengantar yang bagus bagi siapa saja yang tertarik untuk mempelajari [Python](https://python.org).

## 2. Using the Python Interpreter

Python akan terinstall di `/usr/local/bin/python3.11` sesuai dengan versi python yang di install. Adapun cara  untuk mengecek python sudah terinstall atau belum yaitu dengan mengetikkan

```sh
python3.11
```

di shell (linux) atau command propt (windows). Jika menggunakan windows, perlu menambahkan Python ke environment variable apabila ingin menggunakan python di command propt. Kecuali jika anda menginstallnya dari Microsoft Store.

Salah satu cara menjalankan Python yaitu dengan cara mengetikkan `python`,  `python3`, ataupun `python3.11` di shell. Jika muncul tanda `>>>` maka anda berhasil masuk ke interactive mode Python.

![interactive mode](https://github.com/callmeumm/workshop-python/blob/master/docs/interactive_1.png?raw=true)

Cara selanjutnya yaitu dengan mengetikkan `python -c command [arg] ...` atau `python -m module [arg] ...` jika kode berupa kode kompleks. Untuk melihat argument, bisa anda cari dengan mengetikkan `python -h`.

## 3. An Informal Introduction to Python
### A. Numbers

Dalam penggunaan type data `Number` di Python, dapat menggunakan operator:

- `+` - Penjumlahan
- `-` - Pengurangan
- `*` - Perkalian
- `/` - Pembagian

contoh:
![number calculator](https://github.com/callmeumm/workshop-python/blob/master/docs/number_1.png?raw=true)

### B. Strings
Selain Number, Python juga dapet digunakan untuk memanipulai String, contoh:

contoh:
![string manipulation](https://github.com/callmeumm/workshop-python/blob/master/docs/string_1.png?raw=true)

### C. Lists
Python juga dapat digunakan untuk mengedit atau membaca Lists atau Array, contoh:

![number calculator](https://github.com/callmeumm/workshop-python/blob/master/docs/lists_1.png?raw=true)

Jika data berupa string, maka akan muncul kode dari string atau char tersebut dengan format Unsigned Int 8.