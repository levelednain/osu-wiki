# Panduan menyunting audio

[osu!academy](/wiki/Community/Video_series/osu!academy) telah menjelaskan hal ini di [Episode 15: Audio Encoding (4:02)](https://www.youtube.com/watch?v=muu3HkG38kk). Episode itu juga berisikan cara memasang dan menggunakan Audacity dengan kemampuan ekspor `.mp3` dari LAME.

Artikel ini bertujuan sebagai panduan untuk membantu Anda dalam melakukan penyuntingan kecil kepada file-file audio Anda untuk keperluan membuat beatmap. Dengan membantu mengembangkan artikel ini, Anda bisa membantu kreator beatmap yang lain untuk membuat file-file audio yang sesuai untuk kebutuhan apapun.

*Program yang hanya tercantumkan di artikel ini bukan berarti hanya program yang dapat Anda gunakan, namun itu adalah program-program dari orang yang telah menambahkannya disini. Jika Anda mengetahui program lain yang dapat digunakan dan dapat menjelaskan cara menggunakannya untuk bagian yang dijelaskan di bawah ini, silakan tambahkan.*

## Audacity

[Audacity](https://www.audacityteam.org/download) adalah program perekam dan penyunting audio gratis berbasis open-source. Program ini menggunakan pustaka encoding [LAME](https://lame.sourceforge.io) untuk dapat mengekspor audio ke format MP3 dan sudah tersedia dalam Audacity di Windows dan macOS.

Untuk pengguna Linux, dimohon membaca [Audacity Reference Manual](https://manual.audacityteam.org/man/installing_and_updating_audacity_on_linux.html#linlame) untuk informasi tambahan, karena sebagian distribusi Linux mungkin tidak menyediakan LAME ketika memasang Audacity.

### Menurunkan Bit Rate

*Untuk informasi dasar tentang kompresi file, lihat: [Compressing files](/wiki/Guides/Compressing_files)*

Pasang dan buka Audacity, lalu ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang Anda ingin kecilkan bitratenya.
2. Tekan `Ctrl` + `Shift` + `E`, lalu di bagian `Save as type:` pilih `MP3 Files`, atau:
   1. Klik `File`, lalu `Export`, dan `Export as MP3`.
3. Pada bagian `Format Options`, ganti pengaturannya mengikuti pengaturan ini:
   1. `Bit Rate Mode`: `Preset`
   2. `Quality`: `Medium, 145-185 kbps`
4. Tentukan lokasi yang Anda inginkan untuk menyimpan filenya.
   - Anda juga bisa mengganti nama filenya.
5. Klik `Save` dan sebuah dialog akan muncul untuk memasukkan metadata.
6. Klik `OK` jika sudah selesai memasukkan metadata.

### Perulangan/Looping

Pasang dan buka Audacity, lalu ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang Anda inginkan untuk diulang.
2. Klik dan seret untuk menandai bagian yang Anda inginkan untuk diulang.
   - Yang jarang adalah pada bagian awal hingga akhir dari musiknya.
   - Terkadang bagian reff adalah bagian yang paling terbaik untuk perulangan.
3. Tekan `Ctrl` + `C`, atau:
   1. Klik `Edit`
   2. Klik `Copy` 
4. Temukan lokasi dimana anda dapat mengulang bagian yang sudah disalin.
   - Ini juga bisa untuk akhir dari bagian yang Anda telah tandai.
5. Tekan `Ctrl` + `V`, atau:
   1. Klik `Edit`
   2. Klik `Paste` 
6. Dengarkan seluruh musiknya dan pastikan pengulangannya sudah pas.
7. Ulangi sebanyak yang dibutuhkan
8. Tekan `Ctrl` + `Shift` + `E`, lalu di bagian `Save as type:` pilih `MP3 Files`, atau:
   1. Klik `File`, lalu `Export`, dan `Export as MP3`.
9. Pada bagian `Format Options`, ganti pengaturannya mengikuti pengaturan ini:
   1. `Bit Rate Mode`: `Preset`
   2. `Quality`: `Medium, 145-185 kbps`
10. Tentukan lokasi yang Anda inginkan untuk menyimpan filenya.
   - Anda juga bisa mengganti nama filenya.
11. Klik `Save` dan sebuah dialog akan muncul untuk memasukkan metadata.
12. Klik `OK` jika sudah selesai memasukkan metadata.

### Memotong

Pasang dan buka Audacity, lalu ikuti langkah-langkah berikut:

1. Buka file `.mp3` yang Anda ingin potong.
2. Klik dan seret untuk menandai bagian yang Anda inginkan untuk diulang.
   - Ini seharusnya bagian outro panjang yang Anda tidak ingin untuk di map.
3. Tekan `Delete`.
4. Klik dan seret bagian 3 sampai 5 detik yang menuju bagian akhir.
5. Klik `Effect`
6. Klik `Fade Out`
7. Tekan `Ctrl` + `Shift` + `E`, lalu di bagian `Save as type:` pilih `MP3 Files`, atau:
   1. Klik `File`, lalu `Export`, dan `Export as MP3`.
8. Pada bagian `Format Options`, ganti pengaturannya mengikuti pengaturan ini:
   1. `Bit Rate Mode`: `Preset`
   2. `Quality`: `Medium, 145-185 kbps`
9. Tentukan lokasi yang Anda inginkan untuk menyimpan filenya.
   - Anda juga bisa mengganti nama filenya.
10. Klik `Save` dan sebuah dialog akan muncul untuk memasukkan metadata.
11. Klik `OK` jika sudah selesai memasukkan metadata.

## mp3DirectCut

[mp3DirectCut](https://mpesch3.de) adalah perangkat lunak penyunting audio gratis yang dapat menyunting file-file MP3 secara langsung tanpa diencode ulang, sering kali dapat mencegah penurunan kualitas audio. Perangkat lunak ini sangat direkomendasikan ketika perlu menaikkan dan menurunkan audio atau memotong audio.

### Perulangan/Looping

Pasang dan buka mp3DirectCut, lalu ikuti langkah-langkah ini:

1. Buka file `.mp3` yang Anda inginkan untuk diulang.
2. Klik dan seret untuk menandai bagian yang Anda inginkan untuk diulang.
   - Yang jarang adalah pada bagian awal hingga akhir dari musiknya.
   - Terkadang bagian reff adalah bagian yang paling terbaik untuk perulangan.
3. Tekan `Ctrl` + `C`, atau
   1. Klik `Edit`
   2. Klik `Copy`
4. Temukan lokasi dimana anda dapat mengulang bagian yang sudah disalin.
   - Ini juga bisa untuk akhir dari bagian yang Anda telah tandai.
5. Tekan `Ctrl` + `V`, atau:
   1. Klik `Edit`
   2. Klik `Paste` 
6. Dengarkan seluruh musiknya dan pastikan pengulangannya sudah pas.
7. Ulangi sebanyak yang dibutuhkan
8. Tekan `Ctrl` + `W`, atau
   - Klik `File`
   - Klik `Save complete audio...`
9. Tentukan lokasi yang Anda inginkan untuk menyimpan filenya.
   - Anda juga bisa mengganti nama filenya.
10. Klik `Save`

### Memotong

Pasang dan buka mp3DirectCut, lalu ikuti langkah-langkah ini:

1. Buka file `.mp3` yang Anda ingin potong.
2. Klik dan seret untuk menandai bagian yang Anda inginkan untuk diulang.
   - Ini seharusnya bagian outro panjang yang Anda tidak ingin untuk di map.
3. Tekan `Delete`.
4. Klik dan seret bagian 3 sampai 5 detik yang menuju bagian akhir.
5. Tekan `Ctrl` + `F`, atau
   1. Klik `Edit`.
   2. Klik `Simple fade to/from position`.
6. Tekan `Ctrl` + `W`, atau
   1. Klik `File`.
   2. Klik `Save complete audio...`.
7. Tentukan lokasi yang Anda inginkan untuk menyimpan filenya.
   - Anda juga bisa mengganti nama filenya.
8. Klik `Save`.

### Mengatur Volumenya

Pasang dan buka mp3DirectCut, lalu ikuti langkah-langkah ini:

1. Buka file `.mp3` yang anda inginkan untuk diatur volumenya.
2. Tekan `Ctrl` + `A` untuk memilih semuanya.
3. Tekan `Ctrl` + `G`, atau
   1. Klik `Edit`
   2. Klik `Gain...`
4. Periksa kolom centang `Lock Sliders`.
5. Tekan dan tahan slider kirinya dan turunkan.
   - dB (desibel) yang anda atur akan beragam, cukup coba berbagai macam volume hingga Anda melakukannya dengan benar.
6. Ketika Anda sudah puas, klik `OK`.
7. Tekan `Ctrl` + `W`, atau
   1. Klik `File`.
   2. Klik `Save complete audio...`.
8. Tentukan lokasi yang Anda inginkan untuk menyimpan filenya.
   - Anda juga bisa mengganti nama filenya.
9. Klik `Save`.
