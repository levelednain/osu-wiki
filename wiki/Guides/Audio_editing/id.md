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

### Cropping

Install and open Audacity, then follow these steps:

1. Open the `.mp3` file that you want to crop.
2. Click and drag to highlight the parts you want to crop.
   - This should be the long outro that you don't want to map.
3. Press `Delete`.
4. Click and drag the last 3 to 5 seconds towards the end.
5. Click `Effect`.
6. Click `Fade Out`.
7. Press `Ctrl` + `Shift` + `E`, then in `Save as type:` select `MP3 Files`, or:
   1. Click `File`, then `Export`, then `Export as MP3`.
8. In the `Format Options`, change the following settings:
   1. `Bit Rate Mode`: `Preset`
   2. `Quality`: `Medium, 145-185 kbps`
9. Navigate to the location you want to save the file as.
   - You could rename the file too.
10. Click `Save` and a dialog will appear to enter metadata.
11. Click `OK` once done entering metadata.

## mp3DirectCut

[mp3DirectCut](https://mpesch3.de) is a free-to-use audio editing software that can directly edit MP3 files without re-encoding, often preventing loss of quality. It is recommended when needing to raise/lower the volume or crop the audio.

### Looping

Install and open mp3DirectCut, then follow these steps:

1. Open the `.mp3` file that you want to loop.
2. Click and drag to highlight the parts you want to loop.
   - Rarely, it would be the start to the end of the music.
   - Sometimes the chorus or refrain is where looping is done best.
3. Press `Ctrl` + `C`, or
   1. Click `Edit`
   2. Click `Copy`
4. Find a location for where you can loop the part you have copied.
   - This could be the end of the part you had highlighted.
5. Press `Ctrl` + `V`, or
   1. Click `Edit`
   2. Click `Paste`
6. Play through the entire music and make sure that the loop sounds good.
7. Repeat as needed.
8. Press `Ctrl` + `W`, or
   1. Click `File`.
   2. Click `Save complete audio...`.
9. Navigate to the location you want to save the file as.
   - You could rename the file too.
10. Click `Save`.

### Cropping

Install and open mp3DirectCut, then follow these steps:

1. Open the `.mp3` file that you want to crop.
2. Click and drag to highlight the parts you want to crop.
   - This should be the long outro that you don't want to map.
3. Press `Delete`.
4. Click and drag the last 3 to 5 seconds towards the end.
5. Press `Ctrl` + `F`, or
   1. Click `Edit`.
   2. Click `Simple fade to/from position`.
6. Press `Ctrl` + `W`, or
   1. Click `File`.
   2. Click `Save complete audio...`.
7. Navigate to the location you want to save the file as.
   - You could rename the file too.
8. Click `Save`.

### Adjusting the Volume

Install and open mp3DirectCut, then follow these steps:

1. Open the `.mp3` file that you want to adjust.
2. Press `Ctrl` + `A` to select all.
3. Press `Ctrl` + `G`, or
   1. Click `Edit`
   2. Click `Gain...`
4. Check the `Lock Sliders` checkbox.
5. Take the left slider and lower it.
   - The dB (decibels) you set it to will vary, just try various volumes until you get it right.
6. When you are satisfied, press `OK`.
7. Press `Ctrl` + `W`, or
   1. Click `File`.
   2. Click `Save complete audio...`.
8. Navigate to the location you want to save the file as.
   - You could rename the file too.
9. Click `Save`.
