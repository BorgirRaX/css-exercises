# The Holy Grail of Layout

Di latihan flexbox terakhir ini lo akan membuat ulang layout website yang sangat umum. Ini sangat umum sehingga sering disebut layout [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img)... dan dengan flexbox sebenarnya cukup mudah untuk dilakukan.

Seperti latihan sebelumnya, kita tinggalkan sedikit lebih banyak untuk lo lakukan.

### Petunjuk
- Lo perlu mengubah flex-direction untuk mendorong footer ke bawah.
- Lo perlu menambahkan beberapa div sebagai container untuk membuat semuanya sejajar dengan benar.
- `flex-wrap` akan membantu membuat card sejajar dengan benar.
- Pastikan lo menentukan berapa banyak ruang yang harus diambil card, agar `flex-wrap` bekerja seperti yang diinginkan.

## Hasil yang diinginkan

![desired outcome](./desired-outcome.png)

Jumlah card yang berbaris di bagian itu akan berubah berdasarkan lebar layar lo, jadi jangan stress tentang mendapatkan grid _persis_ 2x3 atau 3x2.

Di layar yang lebih kecil akan terlihat seperti ini:

![smaller](./desired-outcome-smaller.png)

Catatan: Emoji mungkin muncul sebagai satu atau beberapa simbol teks (misalnya &#9734;&#9794;) jika lo tidak punya font family berbasis emoji yang terinstal di sistem operasi lo. Ini tidak mempengaruhi latihan dan bisa diabaikan.

### Self Check
- Teks header berukuran 32px dan weight 900.
- Teks header dipusatkan secara vertikal dan 16px dari tepi layar.
- Footer didorong ke bagian bawah layar (footer mungkin berada _di bawah_ bagian bawah layar jika konten bagian 'cards' overflow dan/atau jika layar lo lebih pendek).
- Teks footer dipusatkan secara horizontal dan vertikal.
- Sidebar dan cards mengambil semua ruang yang tersedia di atas footer.
- Sidebar lebar 300px (dan tidak menyusut).
- Link sidebar berukuran 24px, berwarna putih, dan tidak punya dekorasi teks underline.
- Sidebar punya padding 16px.
- Ada padding 48px di sekitar bagian 'cards'.
- Card disusun secara horizontal, tapi wrap ke beberapa baris ketika mereka kehabisan ruang di halaman.
