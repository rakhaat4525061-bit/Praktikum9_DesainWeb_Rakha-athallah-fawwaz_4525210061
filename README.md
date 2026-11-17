Ringkasan Pengerjaan Website Selaras Coffee

Website one-page Selaras Coffee dibuat dari nol dengan Bootstrap 5 dalam dua file, index.html dan style.css. Semua komponen wajib sudah ada: navbar responsif, hero section, tiga card produk, alert promo, modal, form kontak, footer, dan custom CSS. Saya juga menambahkan bagian Tentang, Keunggulan, dan tombol kembali ke atas.

Masalah utama adalah tampilan Bootstrap bawaan yang terlihat generik. Solusinya, variabel warna dan font Bootstrap ditimpa lewat :root dengan palet espresso, krim, terakota, dan hijau sage, serta font Playfair Display untuk judul. Tombol, card, modal, dan hero juga diberi gaya khusus sebagai identitas brand.

Masalah kedua, belum ada foto produk. Sebagai gantinya dipakai emoji dan gradasi warna, yang bisa diganti gambar asli nanti.

Ketiga, tiga produk membutuhkan modal detail. Daripada membuat tiga modal, saya memakai satu modal yang isinya diisi JavaScript dari atribut data-* pada tombol.

Keempat, navbar fixed-top bisa menutupi judul section saat menu diklik. Ini diatasi dengan scroll-margin-top dan padding atas pada hero.

Terakhir, form kontak diberi validasi bawaan Bootstrap dan alert sukses. Form ini belum mengirim data ke server.

Saya belum menguji website ini di browser, jadi hasil akhirnya perlu dicek langsung, terutama tampilan di layar HP.