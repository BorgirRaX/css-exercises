# Gaya 'modal' yang umum
Ini adalah pola lain yang sangat umum di web. Solusi untuk yang ini _sederhana_... tapi mungkin tidak langsung terlihat jelas untuk lo. Lo perlu mengedit HTML sedikit untuk menempatkan semuanya di tempat yang seharusnya.

### Petunjuk
Tergantung bagaimana lo mendekati yang ini, lo mungkin perlu mengunjungi kembali properti `flex-shrink` untuk menjaga agar flex item tidak terjepit. Selain itu, perhatikan struktur html, khususnya pertimbangkan untuk menambahkan container tambahan yang mengelilingi div header, button, main text, cancel, dan continue; dan pertimbangkan untuk memindahkan div header agar mencakup button juga.

## Hasil yang diinginkan

![desired outcome](./desired-outcome.png)

### Self Check

- Ikon biru disejajarkan ke kiri.
- Ada ruang yang sama di kedua sisi ikon (jarak antara ikon dan tepi card, dan ikon dengan teks, adalah sama).
- Ada padding di sekitar tepi modal.
- Header, teks, dan button disejajarkan satu sama lain.
- Header bold dan ukuran teks sedikit lebih besar dari teks biasa.
- Tombol close disejajarkan secara vertikal dengan header, dan disejajarkan di pojok kanan atas card.
