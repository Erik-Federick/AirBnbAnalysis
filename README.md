# AirBnbAnalysis

Summary :

Repositori ini berisi wawasan dan analisis data terkait listing properti Airbnb di Bangkok. Informasi yang disajikan mencakup berbagai aspek, termasuk distribusi listing di berbagai wilayah, daerah populer, jenis kamar, tren harga, dan ulasan pengguna. Analisis ini bertujuan untuk memberikan wawasan berharga bagi pemilik properti, bisnis, dan pemangku kepentingan dalam industri perhotelan di Bangkok.

Link Dataset: https://drive.google.com/drive/folders/1A_KBMRFTS5Mthpp46nulso679ML4ZwTF

Pernyataan Masalah :
1. Karakteristik Properti Airbnb di Setiap Wilayah:
    -  Bagaimana karakteristik utama properti Airbnb bervariasi di wilayah Central Bangkok, South Bangkok, North Bangkok, North Thonburi, East Bangkok, dan South Thonburi?
    - Apakah terdapat preferensi khusus atau tren tertentu dalam fasilitas atau tipe properti di setiap wilayah?

2. Tipe Properti yang Paling Diminati:
    - Apa tipe properti (Entire home/apt, Private room, Hotel room, Shared room) yang paling diminati oleh penyewa Airbnb di Bangkok?
    - Adakah perbedaan signifikan dalam permintaan untuk tipe properti tertentu di berbagai wilayah?

3. Perbedaan Harga Properti di Berbagai Wilayah:
    - Bagaimana perbedaan harga properti Airbnb di wilayah Central Bangkok, South Bangkok, North Bangkok, North Thonburi, East Bangkok, dan South Thonburi?
    - Apakah terdapat faktor tertentu yang secara signifikan mempengaruhi harga properti di setiap wilayah?
  
## Goals

1. Mengidentifikasi Karakteristik Utama Properti:
    - Menentukan karakteristik utama properti Airbnb yang paling dominan di masing-masing wilayah di Bangkok.
    - Menganalisis fasilitas dan fitur properti yang paling diunggulkan oleh pemilik dan diminati oleh penyewa di setiap wilayah.

2. Menganalisis Tren Permintaan Tipe Properti:
    - Mengidentifikasi tipe properti yang paling diminati oleh penyewa Airbnb di Bangkok secara keseluruhan.
    - Menilai apakah ada perbedaan signifikan dalam preferensi tipe properti di berbagai wilayah, memberikan wawasan kepada pemilik properti untuk penyesuaian strategis.

3. Menilai Perbedaan Harga Properti:
    - Menganalisis perbedaan harga properti Airbnb antara wilayah Central Bangkok, South Bangkok, North Bangkok, North Thonburi, East Bangkok, dan South Thonburi.
    - Mengidentifikasi faktor-faktor yang mungkin memengaruhi variasi harga dan memberikan panduan kepada pemilik properti dalam menentukan harga yang kompetitif dan sesuai dengan pasar.

4. Memberikan Rekomendasi Peningkatan Properti:
    - Menyusun rekomendasi berdasarkan analisis untuk pemilik properti, seperti peningkatan fasilitas atau strategi pemasaran berdasarkan karakteristik wilayah dan tren permintaan.
    - Memberikan panduan kepada pemilik properti untuk menyesuaikan harga agar lebih bersaing dan meningkatkan daya tarik properti mereka.

**About Dataset**

Dataset ini berisi informasi mengenai daftar-daftar Airbnb, tuan rumah, serta beberapa metrik penting. Ada 17 kolom di dalam dataset Airbnb, yaitu:

- **Unnamed: 0** : index dari dataset

- **id** : Nomor identifikasi unik untuk Airbnb

- **name** : Nama dari listing

- **host_id** : Nomor identifikasi unik Airbnb untuk tuan rumah/pemilik

- **host_name** : Nama pemilik, biasanya nama depan

- **neighbourhood** : Lingkungan/wilayah tempat listing berada berdasarkan latitude dan longitude

- **latitude** : Menggunakan proyeksi World Geodetic System (WGS84) untuk koordinat lintang

- **longitude** : Menggunakan proyeksi World Geodetic System (WGS84) untuk koordinat bujur

- **room_type** : [Seluruh rumah/apartemen | Kamar pribadi | Kamar bersama | Hotel]
Semua rumah dikelompokkan ke dalam tiga jenis kamar berikut:

    - "Entire place": Ini merujuk pada penyewaan seluruh unit rumah atau apartemen. Tamu memiliki akses eksklusif ke seluruh ruangan dan fasilitas yang ada di tempat tersebut. Tidak ada orang lain yang tinggal di unit tersebut selama masa menginap tamu.

    - "Private rooms": Kamar pribadi mengacu pada penyewaan satu atau beberapa kamar di dalam suatu unit, tetapi tamu harus berbagi fasilitas umum seperti dapur, ruang tamu, atau kamar mandi dengan pemilik rumah atau mungkin tamu lainnya.

    - "Shared rooms": Kamar bersama berarti tamu akan berbagi ruangan tidur atau ruangan lain dengan tamu lain yang mungkin tidak dikenal sebelumnya. Biasanya, ini adalah pilihan yang lebih ekonomis, dan fasilitas lain seperti kamar mandi dan dapur kemungkinan besar juga bersifat bersama.

    - "Hotel" :mencakup kamar hotel tradisional dengan fasilitas dan layanan hotel standar, suite atau unit yang menyediakan layanan tambahan seperti layanan kamar, serta properti berdesain unik atau tematik yang menawarkan pengalaman menginap yang berbeda. 

- **price** : Harga sewa listing dalam mata uang lokal (baht)

- **minimum_nights** : Jumlah minimum masa sewa untuk listing permalam

- **number_of_reviews** : Jumlah ulasan listing, kolom ini juga dapat diasumsikan sebagai jumlah penyewa pada sebuah listing

- **last_review** : Tanggal ulasan terakhir/terbaru

- **reviews_per_month** : Jumlah rata-rata ulasan yang diterima perbulan berdasarkan terakhir mendapat review

- **calculated_host_listings_count** : Jumlah listing yang dimiliki oleh pemilik

- **availability_365** : Ketersediaan listing dalam 365 hari ke depan

- **number_of_reviews_ltm** : Jumlah ulasan yang diterima listing dalam 12 bulan terakhir, kolom ini dapat diasumsikan sebagai jumlah penyewa pada sebuah listing
