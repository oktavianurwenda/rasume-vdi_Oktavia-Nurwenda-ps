> **Making** **data** **visulization** **more** **at** **financial**
> **and** **effective** **a** **Survey**

**1.** **Pendahuluan**

Visualisasi data, yang mengubah data abstrak menjadi visi fisik
(misalnya, Panjang, Posisi, Bentuk, warna, dan sebagainy)a merupakan
Jcara ampuh untuk menyajikan kisah data yang menarik bagi manusia yang
lebih berorientasi visual.

**Perkembangan** **visualisasi** **data** Tidak diragukan lagi
visualisasi data telah membuat langkah besar di banyakbidangdisumbangkan
olehbanyakkomunitas komunitasgrafis komputertelahsecara signifikan
memajukan teknologi rendering visualisasi yang indah namun dapat
direpresentasikan sendiri menggunakan misalnya D3

komunitas visualisasi memudahkan pengguna untuk menentukan dan
berinteraksi dengan visualisasi data seperti D3 Vega Lite fish Il
tableus dan Microsoft power BI

Komunitas basis data telah meningkatkan pengalaman penggunaan dalam
melihat dan berinteraksi dengan visualisasi data secara Real Time,
bahkan untuk data besar (misalnya Misalnya untuk jutaan atau miliaran
catatan). misalnya hyper DB \[6-8 \] adalah mesin back-end untuk
mendukung Tableau dan proyek Falcon (tersedia di github)

Alur visualisasi data alur visualisasi data iteratif yang umum satu
ditunjukkan

1\. impor data Adalah mengambil data yang diperlukan dari sumber data
yang diinginkan.

2.persiapan data adalah mempersiapkan data yang diimpor untuk
visualisasi misalnya dengan menormalkan nilai mengkoreksi entri yang
salah dan menginterpolasi nilai yang hilang.

3.manipulasi data adalah memilih data yang akan divisualisasikan alias
menyaring dari komunitas visualisasi dan mungkin dengan operasi umum
lainnya seperti penggabungan dan pengelompokan.

4.pemetaan adalah memetakan data yang diperoleh dari proses di atas ke
primitif geometris (misalnya warna posisi dan ukuran) .

5 rendering adalah mengubah data geometri di atas menjadi representasi
visual.

Mengidentifikasi tiga arah yang membuat visualisasi data lebih efisien
dan efektif, namun tetap relevan dengan penelitian basis data.

1\. Spesifikasi visualisasi

2\. pendekatan efisien untuk visualisasi data

3\. rekomendasi visualisasi data

4\. survei terkait

2.Spesifikasi visualisasi

2.1 spesifikasi visualisasi data

secara umum bahasa visualisasi terdiri dari tiga bagian: data, tanda
(atau isyarat visual) dan pemetaan di antara keduanya.

**-** **Data**

\- Catatan: data yang perlu di visualisasikan

\- Transformasi: operasi seperti grup,bin, filter, dan sortir digunakan
untuk mengubah rekaman data yang ditentukan.

**-Tanda** (atau isyarat visual )

-Jenis: representasi visual untuk catatan data, seperti batang, garis,
atau titik.

-Ukuran: lebar tinggi visualisasi.

\- Lain-lain: properti lainnya, seperti lebar dan warna batangan

**-** **Pemetaan:** memetakan data ke tanda yang sesuai

**2.2** **kategorisasi** **bahasa** **visualisasi** **data**

\-**Bahasa** **tingkat** **rendah** kami menyebut bahasa tingkat rendah
sebagai bahasa yang mengharuskan pengguna menentukan semua elemen
pemetaan

**-** **bahasa** **tingkat** **tinggi** merangkum detail konstruksi
visualisasi seperti fungsi pemetaan, serta beberapa properti untuk tanda
seperti ukuran kanvas Legenda, dan properti lainnya.

**2.3** **operasi** **visual** **berbasis** **GUI**

**Visualisasi** **data** **interaktif** rasionalitas di balik
visualisasi data interaktif adalah banyak kasus, visualisasi data adalah
proses eksplorasi di mana pengguna perlu menjaga penyempurnaan
spesifikasi (misalnya menambahkan/menghapus/mengubah atribut, mengubah
jenis bagan) visualisasi yang sedang dieksplorasi hingga mendapatkan
visualisasi yang diinginkan dengan proses eksplorasi.

**2.4** **spesifikasi** **yang** **kurang** **jelas**

Visualisasi tidak ada artinya jika tidak dapat memberikan wawasan
tentang data. namun dalam banyak kasus penggunaan tidak benar-benar
mengetahui semua aspek data yang ada karena data tersebut mungkin besar
dan data tersebut dapat sering diperbarui Oleh karena itu diperlukan
dukungan spesifikasi yang kurang spesifik.

**3.** **Pendekatan** **efisien** **untuk** **visualisasi** **data**

**3.1** **visualisasi** **data** **yang** **tepat**

banyak sistem visualisasi data membaca data dari basis data sistem ini
juga dapat memanipulasi data dengan pernyataan SQL dan kemudian
menggunakan alat visualisasi untuk menampilkan visualisasi.

**2.2** **visualisasi** **data** **perkiraan**

Berbasis AQP cara mudah untuk menghasilkan visualisasi perkiraan dalam
waktu interaktif adalah memanfaatkan teknik AQP. Menggunakan subset
representatif dari data dapat memberikan pengguna visualisasi perkiraan
untuk interaksi online dengan mengorbankan kualitas. berbasis

\- Pengambilan sampel inkremental

\- Berbasis Persepsi manusia

\- pengelompokan berbasis rentang

\- pengelompokan berbasis rentang dan konten

**3.3** **Visualisasi** **data** **progresif**

-Gambaran umum solusi

\- memangkas visualisasi yang tidak berarti

**4.** **Rekomendasi** **visualisasi**

**4.1** **rekomendasi** **berbasis** **spesifikasi**

> **4.1.1** **spesifikasi** **tidak** **lengkap**

sistem rekomendasi visualisasi dengan spesifikasi kosong untuk
memerlukan input pengguna, sedangkan sistem rekomendasi dengan
spesifikasi parsial menerima input spesifikasi elemen visualisasi
parsial pengguna untuk visualisasi yang diinginkan.

-Pemangkas visualisasi yang tidak berarti

-Peringkat visualisasi berbasis aturan

-Aturan perseptual

Pemeringkatan visualisasi berbasis pembelajaran mesin

-Belajar dengan kendala lunak

-Belajar dengan contoh

**4.1.2** **spesifikasi** **berbasis** **referensi**

Beberapa sistem rekomendasi visualisasi mereka menjelaskan visualisasi
berdasarkan data referensi atau visualisasi referensi biasanya sistem
akan merekomendasikan visualisasi yang mirip atau berbeda dari yang
diberikan referensi dalam aspek tertentu.

-seeDB berbasis deviasi

\- propeller berbasis anomali

-Zenvisage berbasis kesamaan atau jarak

**4.2** **Rekomendasi** **berbasis** **perilaku**

HARVEST adalah sistem rekomendasi visualisasi berbasis perilaku sistem
ini Merekomendasikan visualisasi berdasarkan tugas pengguna yang
disimpulkan dari perilaku mereka karena sulit bagi pengguna untuk
menjelaskan maksudnya dengan jelas dan tugas pengguna berkembang seiring
proses eksplorasi HARVEST menebak maksud pengguna berdasarkan perilaku
mereka.

**4.3** **Rekomendasi** **yang** **di** **personalisasi**

sistem rekomendasi yang dipersonalisasi menangkap perilaku historis
pengguna sebagai masukan untuk merekomendasikan visualisasi menarik yang
dipersonalisasi.

\- Model linier memberikan hasil rekomendasi visualisasi yang
dipersonalisasi dengan melatih model linear untuk setiap pengguna
menggunakan perilaku historis mereka.

\- penyaringan kolaboratif Ada banyak teknik lain dalam sistem
rekomendasi yang dipersonalisasi misalnya, kolaboratif penyaringan
Adalah algoritma rekomendasi pribadi yang banyak digunakan.

**4.4** **ringkasan**

**5** **Arah** **penelitian** **lainnya**

**5.1** **Persiapan** **data** **untuk** **visualisasi** **data**

-What-ifAnalysis for Outliers

-Evaluasi visualisasi dengan data yang hilang

\- Mendeteksi visualisasi yang bias

\- pembersihan data yang memperhatikan tugas

**5.2** **Tolak** **ukur** **visualisasi** **data**

Tolak ukur harus sesuai dengan tugas analisis visual menyediakan jejak
dan data yang dapat digunakan kembali dan dalam hal rekomendasi memiliki
cakupan dan kualitas label yang tinggi.

Terdapat fokus baru dalam pengembangan tolak ukur untuk pengukuran
kinerja.

\- Sebuah karya penelitian vizNet.

\- kategorisasi visualisasi

\- data pelatihan

> **5.3** **visualisasi** **data** **untuk** **aplikasi** **terkait**
> **database**

\- Visualisasi data untuk penemuan data

\- visualisasi data untuk debugging data

**6.** **Kesimpulan**

visualisasi data adalah bidang yang berkembang pesat dengan banyak
sekali hasil penelitian baru dan sistem baru yang dikembangkan baru-baru
ini penelitian dan praktisi dari berbagai bidang telah berkontribusi
pada keberhasilan luar biasa visualisasi data yang didorong oleh
sebagian besar jika tidak semua domain dan aplikasi.

artikel ini terutama mensurvei karya visualisasi data terkini dari
perspektif manajemen data. secara khusus, kami telah menjelaskan secara
komprehensif karya-karya dalam spesifikasi visualisasi, metode yang
efisien untuk visualisasi data, dan rekomendasi visualisasi. sebagian Ko
hal spesifik. namun, banyakpraktisi masihmengalamimasalah di efisiensi
dan rekomendasi sistem ini. olehkarenaitu,kami juga membahas beberapa
masalah terbuka yang dapat diberikan kontribusi signifikan oleh peneliti
data untuk memajukan bidang visualisasi data.
