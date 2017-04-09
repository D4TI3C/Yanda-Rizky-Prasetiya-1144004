RESUME PERTEMUAN 4 KECERDASAN BUATAN

<p align="center">
  <img src="../../img/3.jpg" width="400px">

**LATAR BELAKANG**

1. Apa yang dimaksud dengan Ruang keadaan?
2. Apa saja cara untuk mempresentasikan ruang keadaan dan jelaskan masing-masing cara tersebut
3. Contoh kasus ruang keadaan

**ISI**

**Ruang Keadaan adalah cara mendefinisikan permasalahan ke dalam bentuk representasi algoritma.**

**Cara mempresentasikan ruang keadaan:**

- Graph keadaan terdiri dari node-node yang dihubungkan dengan arc (busur) yang diberi panah untuk menunjukkan arah keadaan awal dan keadaan baru yang akan dicapai berikutnya.
- Pohon pelacakan digunakan untuk menggambarkan keadaan secara hirarkis, sehingga mencegah node yang berulang.
- Pohon AND/OR merupakan struktur pohon Untuk menyelesaikan suatu masalah menggunakan 3 kemungkinan, misalnya a,b,c, yang artinya masalah bisa diselesaikan jika salah satu dari kemungkinan tersebut tidak terpecahkan.

**Contoh :**

**Permasalahan :   Petani, Sayur, Kambing dan  Harimau yang menyebrang**

Contoh kasusnya adalah permasalahan petani, harimau, ayam, dan gabah. Petani ingin memindahkan dirinya sendiri, harimau, ayam, dan gabah menyebrangi sungai. Tapi perahunya hanya bisa membawa petani dan satu penumpang lainnya. Petani juga tidak bisa meninggalkan harimau dan ayam dalam satu tempat karena harimau akan memangsa ayam, dan petani juga tidak bisa meninggalkan ayam dengan gabah dalam satu tempat.

Penyelesaian :

Identifikasi ruang keadaan

  Permasalahan ini dapat dilambangkan dengan:

(kambing, harimau, Sayuran, Boat).

Keadaan Awal

- Daerah asal: (1,1,1,1)
- Daerah seberang: (0,0,0,0)

Tujuan

- Daerah asal: (0,0,0,0)
- Daerah seberang: (1,1,1,1)

Aturan

| Aturan Ke- | Aturan |
| --- | --- |
| 1 | Kambing Menyebrang |
| 2 | Sayur Menyebrang |
| 3 | Harimau Menyebrang |
| 4 | Kambing Kembali |
| 5 | Sayuran Kembali |
| 6 | Harimau Kembali |
| 7 | Boat Kembali |

Penyelesaian

| **Daerah Asal** | **Daerah Tujuan** | **Aturan Yang Digunakan** |
| --- | --- | --- |
| (1,1,1,1) | (0,0,0,0) | 1 |
| (0,1,1,0) | (1,0,0,1) | 7 |
| (0,1,1,1) | (1,0,0,0) | 3 |
| (0,0,1,0) | (1,1,0,1) | 4 |
| (1,0,1,1) | (0,1,0,0) | 2 |
| (1,0,0,0) | (0,1,1,1) | 7 |
| (1,0,0,1) | (0,1,1,0) | 1 |

**PENUTUP**

**KESIMPULAN**

Ruang Keadaan adalah cara mendefinisikan permasalahan ke dalam bentuk representasi algoritma.Terdapat cara-cara untuk mempresentasikan ruang keadaan Graf Keadaan, Pohon Keadaan, dan Pohon AND/OR.

**Saran**

Saran yang dapat diberikan yaitu agar mempelajari lebih dalam lagi mengenai materi ruang keadaan ini supaya dapat lebih paham lagi.

link github: https://github.com/D4TI3C/Yanda-Rizky-Prasetiya-1144004

Nama : yanda rizky prasetiya
   
NPM : 1144004

Kelas : 3C

Prodi : D4 Teknik Informatika

Mata Kuliah : Kecerdasan Buatan

link mata kuliah: http://kampus.awangga.net/home/kelassistemmultimediadankecerdasanbuatan2017

referensi: 1. http://aih1008.blogspot.co.id/2010/06/masalah-ruang-keadaan-dan-pencarian.html 

Scan plagiarisme :

1. https://drive.google.com/open?id=0ByZqhNt9UFJ2ZW1PcnZNRFRDVEk

2. https://drive.google.com/open?id=0ByZqhNt9UFJ2Zy1SU1lpODZjeDg