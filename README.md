# RumahHijau
Website Edukasi Lingkungan dan Hemat Energi

Tema: Energi Terbarukan dan Penghematan Energi

SDGs: SDG 7 (Energi Bersih dan Terjangkau) dan SDG 13 (Penanganan Perubahan Iklim)

# Anggota Kelompok
1. Kadek Ayu Pariyastini (2515091042)
2. Ni Luh Kadek Kinasih Nareswari (2515091140)
3. Kadek Desvitha Dwi Cendani (2515091047)
4. Melinda Oktavio Dina Patricia (2515091143)

# Deskripsi Website
Rumah Hijau merupakan website edukasi yang membahas pentingnya menjaga lingkungan melalui penggunaan energi secara bijak dan pemanfaatan energi terbarukan. Website ini bertujuan untuk memberikan informasi kepada pengguna mengenai penghematan energi, jenis-jenis energi terbarukan, manfaatnya, serta penerapannya dalam kehidupan sehari-hari.

Website ini ditujukan kepada masyarakat umum, khususnya keluarga dan rumah tangga, agar dapat memahami dan menerapkan kebiasaan hemat energi untuk mengurangi pemborosan listrik serta mendukung kelestarian lingkungan.

# Halaman Website
Website Rumah Hijau terdiri dari lima halaman utama, yaitu:

- Beranda (index.html)
Halaman utama yang memperkenalkan website Rumah Hijau, menjelaskan tema yang diangkat, dan menyediakan navigasi menuju halaman lainnya.

- Edukasi (edukasi.html)
Halaman yang berisi informasi edukatif mengenai energi, lingkungan, dan pentingnya penggunaan energi secara bijak.

- Tips Hemat Energi (tips hemat energi.html)
Halaman yang memberikan tips sederhana untuk menghemat energi dalam kehidupan sehari-hari.

- Artikel (artikel.html)
Halaman yang menyajikan artikel informatif mengenai energi terbarukan, manfaatnya, dan pemanfaatannya di Indonesia.

- Tentang (tentang.html)
Halaman yang menjelaskan tujuan pembuatan website Rumah Hijau serta informasi dan referensi yang digunakan.

# Teknologi
Teknologi yang digunakan dalam pengembangan website Rumah Hijau meliputi:

- HTML5: Membuat struktur dan konten halaman website.
  
- CSS3: Mengatur tampilan, warna, tipografi, jarak, dan tata letak website.

- Flexbox dan CSS Grid: Mengatur susunan elemen agar tampilan lebih terstruktur.

- CSS Media Queries: Menyesuaikan tampilan website dengan ukuran layar perangkat yang berbeda.

# Penjelasan Implementasi
## 1. Navigasi & Tata Letak (Flexbox)
- *Struktur Header*: Menggunakan elemen semantik <header> dan <nav> untuk membungkus logo serta link navigasi antarahalaman.
- *Penerapan Flexbox*: Pada kelas .nav-header, properti display: flex dan justify-content: space-between digunakan untuk memisahkan posisi logo di sebelah kiri dan menu navigasi di sebelah kanan secara sejajar.
- *Konsistensi Navigasi*: Menu ditaruh konsisten di seluruh 5 halaman HTML (index.html, edukasi.html, tips.html, artikel.html, dan tentang.html) dengan indikator halaman aktif.

## 2. Tata Layout Utama (CSS Grid)
- *Pengaturan Kartu Konten*: Bagian fitur utama dan kartu artikel memanfaatkan display: grid untuk membagi area menjadi beberapa kolom secara rapi.
- *Pembagian Kolom Desktop*: Menggunakan grid-template-columns: repeat(3, 1fr) dengan gap: 20px pada tampilan desktop agar 3 kartu informasi tampil sejajar dalam 1 baris dengan jarak seimbang.
- *Section Khusus*: Pada halaman tentang.html, grid 2 kolom (grid-template-columns: 320px 1fr) digunakan untuk merapatkan gambar rumah dengan teks deskripsi Tujuan Rumah Hijau.

## 3. Desain Responsif (CSS Media Queries)
- *Breakpoint Tablet (@media (max-width: 768px))*:
  - Mengubah tampilan grid kartu dari 3 kolom menjadi 2 kolom (grid-template-columns: repeat(2, 1fr)).
  - Mengurangi padding container dan menyesuaikan ukuran judul agar tidak memakan banyak ruang.
- *Breakpoint Smartphone (@media (max-width: 550px))*:
  - Mengubah seluruh layout grid menjadi 1 kolom penuh (grid-template-columns: 1fr) sehingga elemen tertumpuk secara vertikal.
  - Mengatur ukuran font (font-size) agar lebih fleksibel di layar kecil serta memastikan tidak ada scroll horizontal (overflow-x).

## 4. Manajemen Gambar & Elemen UI
- *Penerapan object-fit: contain: Digunakan pada bingkai gambar hero agar foto rumah dan lampu tampil utuh 100% dari ujung ke ujung tanpa terpotong (*crop).
- *Pembatasan Ukuran Foto*: Properti max-width dan max-height diterapkan pada gambar hero untuk menjaga rasio lanskap yang ideal di layar desktop.
- *Border Radius*: Menggunakan border-radius: 16px hingga 24px pada kartu informasi dan container gambar untuk memberikan tampilan antarmuka yang modern dan halus.

# Struktur Folder
Website Rumah Hijau terdiri dari beberapa file HTML, CSS, dan aset gambar yang digunakan untuk membangun halaman website. Setiap file memiliki fungsi masing-masing dalam menampilkan informasi dan mengatur tampilan website.
Struktur folder RumahHijau sebagai berikut:
- css
- images
- README.md
- artikel-efisiensi-energi.html
- artikel-emisi-karbon.html
- artikel-energi-terbarukan.html
- artikel-rumah-ramah-lingkungan.html
- artikel.html
- edukasi.html
- index.html
- tentang.html
- tips hemat energi.html

# Website dan Repository
- URL Github Pages : https://kinannyaw.github.io/RumahHijau/
- URL Repository : https://github.com/kinannyaw/RumahHijau.git

# Referensi 
- https://www.bmkg.go.id/artikel/gas-rumah-kaca
- https://www.esdm.go.id/id/media-center/arsip-berita/beri-kemudahan-pemilihan-alat-elektronik-pemerintah-terapkan-standar-label-hemat-energi-sejak-2015
- https://wwf.id/id/blog/mengembangkan-energi-terbarukan
- https://www.cnnindonesia.com/edukasi/20240123172422-569-1053383/pengertian-dan-contoh-hemat-energi-dalam-kehidupan-sehari-hari
- https://lestari.kompas.com/read/2023/05/12/080813786/mengenal-tujuan-7-sdgs-energi-bersih-dan-terjangkau
- https://sustainability.ui.ac.id/wp-content/uploads/2024/11/SDGs-13-SDGs-UI-2023.pdf
- https://www.msig.co.id/id/article/rayakan-hari-bumi-5-kebiasaan-hemat-energi-ini-bisa-buat-rumah-lebih-terlindungi
