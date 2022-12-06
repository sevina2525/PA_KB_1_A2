## PROYEK AKHIR KECERDASAN BUATAN
## DETEKSI HIJAB DAN NON HIJAB👧🧕🏻

### Nama Anggota Kelompok :
1. Erman Parni Simanjuntak (2009106046)
2. Sevina Afi Amalia (2009106042)
3. Cantika Fitri Ayu Darmayanti (2009106045)

---------------------------------------------------------------------------------------------
#### - Erman Parni Simanjuntak
* Ketua Kelompok
* Membuat dan mengatur bagian visualisasi dan evaluate

#### - Sevina Afi Amalia
* Membuat data visualisasi dan analisis

#### - Cantika Fitri Ayu Darmayanti
* Membuat data collecting dan data preprocessing

---------------------------------------------------------------------------------------------
### Deskripsi
Kelompok kami membuat program deteksi untuk mengenali hijab dan non hijab menggunakan image processing dan menerapkan algoritma Convolutional Neural Network (CNN) pada Deep Learning.

---------------------------------------------------------------------------------------------
### Penjelasan Dataset
https://drive.google.com/file/d/1prMOX0cUo1w8Ifn_Rw3cE0nWO72pDQN1/view?usp=share_link 

Terdapat beberapa foto berbagai wanita dengan jenis hijab dan tidak berhijab. Selain itu, terdapat juga foto laki-laki dan masih banyak lagi untuk pembelajaran program dalam mengidentifikasi.

---------------------------------------------------------------------------------------------
### Penjelasan Data Collecting
Pada bagian data collecting, kami membagi data menjadi 3 bagian yaitu data train, data val, dan data test dengan rasio 0.7, 0.2, 0.1.

---------------------------------------------------------------------------------------------
### Penjelasan Data Preprocessing
Pada data preprocessing, kami menggunakan brightness untuk membuat beberapa foto memiliki kecerahan yang berbeda sehingga program dapat mempelajari gambar dengan beda tingkat kecerahan dan kegelapan yang berbeda. Selain itu, kami menggunakan flip untuk mengenali gambar mirror dan gambar yang tidak mirror(terbalik). Dan terakhir ada resize untuk mengecilkan ukuran dari gambar dataset.

-------------------------------------------------------------------------------------------
### Penjelasan Visualisasi Data
Pada visualisasi data, kami membedakan output hijab dan non hijab dengan label. Setelah itu, kami visualisasikan dengan grafik batang
<p align="center">
  <img src="https://github.com/sevina2525/PA_KB_1_A2/blob/main/image%20model/jumlah%20data%20pada%20path.png"/>
</p>

-------------------------------------------------------------------------------------------
### Penjelasan Data Modelling
Pada bagian data modelling, kami membagi menjadi 3 layer dan mengimplementasikan CNN. Pada output layer, kami menggunakan aktivasi sigmoid karena hanya membedakan 2 gambar yaitu hijab dan non hijab.

-------------------------------------------------------------------------------------------
### Penjelasan Evaluasi
Pada hasil evaluasi, kami mendapatkan loss = 0.12481957674026489 dan accuracy = 0.9760000109672546. Kami mencoba test model dengan real foto dan berhasil menghasilkan output yang sesuai. Selain itu, untuk membandingkan prediksi yang benar dan prediksi yag salah, kami mengaplikasikannya pada grafik heatmap.
<p align="center">
  <img src="https://github.com/sevina2525/PA_KB_1_A2/blob/main/image%20model/confussion%20matrix.png"/>
</p>
