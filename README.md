
# Alur Penelitian
Diagram alur penelitian dapat dilihat pada **Diagram Alur Penelitian.png**

Berikut adalah tahapan dalam penelitian ini :

## Perancangan Visualisasi Data  
 Alur diawali dengan perancangan visualisasi data. Dalam tahap ini penulis membuat sketsa dashboard yang akan dibangun. 
 
 **Sketsa Awal : Sketsa awal rancangan dashboard.pdf**
 
 Dalam sketsa awal, digunakan 3 teknik visualisasi data yaitu : Bar chart, Tree Map , dan Parallel Coordinates. Gambar yang digunakan pada sketsa awal bersumber dari Google. Selain merancang tampilan dashboard ditentukan pula data yang akan digunakan serta fitur interaktif yang akan diterapkan. Selain itu, ditentukan nantinya akan menggunakan color blind safe color dalam visualisasi data.
 
## Data Preparation
  Pada tahap ini, dilakukan pengambilan dan pemilihan data yang akan digunakan yang sesuai dengan kebutuhan data yang akan dilakukan visualisasi.Setelah dipilih data akan di-input dalam dataset dengan format data berupa Microsoft Excel. Beberapa data sudah tersedia di web BPS sehingga data akan diunduh dan beberapa lainnya belum sehingga dilakukan input manual ke Microsoft Excel. Oleh karena itu ,akan dilakukan penggabungan antara data yang sudah tersedia dan data hasil input manual. Setelah itu akan dilakukan pengecekan ulang data untuk memastikan tidak ada yang salah input.

Berikut adalah data yang digunakan (dataset) :

+ Jumlah kejahatan
+	Persentase Penduduk Korban Kejahatan yang Melaporkan ke Polisi
+	Persentase Penduduk Korban Kejahatan
+	Persentase Penyelesaian Kejahatan
+	Risiko Penduduk Terkena Kejahatan per 100.000 Penduduk
+	Jumlah Kejahatan yang Diselesaikan
+	Selang Waktu Terjadinya Kejahatan
+	Karakteristik Penduduk Korban Kejahatan Berdasarkan Jenis Kelamin (Laki-laki dan perempuan)
+	Karakteristik Penduduk Korban Kejahatan Berdasarkan Kelompok umur (Anak dan dewasa)
+	Jumlah Kejahatan Menurut Kelompok Jenis Kejahatan (Top 10)
+	Persentase Korban Kejahatan Berdasarkan Jenis Kejahatan yang di Alami

**Dataset : Data Kejahatan.xlsx**

*Data untuk setiap provinsi dan Indonesia selama periode 2019-2020 (_Kecuali: data Jumlah Kejahatan yang Diselesaikan, data Jumlah Kejahatan Menurut Kelompok Jenis Kejahatan (Top 10) ,dan Persentase Korban Kejahatan Berdasarkan Jenis Kejahatan yang di Alami hanya tersedia data untuk Indonesia_)

_Dataset terdiri dari 71 baris dan 18 kolom. Dalam dataset terdapat missing values. Namun ini dapat diabaikan karena dalam pengerjaannya di Tableau data NULL dapat diabaikan_

## Pembangunan Dashboard
  Pembangunan dashboard dilakukan dengan menggunakan alat Tableau. Setelah visualisasi data selesai, dashboard akan di-publish di Tableau Public agar dapat diakses publik. 
  
  Pada tahap ini dilakukan juga revisi sketsa awal perancangan visualisasi data. Dimana teknik visualisasi datanya bertambah satu yaitu Pie Chart. Tata letak grafik juga mengalami perubahan dari sketsa awal. Selanjutnya dilakukan pembangunan dashboard dengan mempertimbangkan berbagai komponen antara lain warna, ukuran font, jenis font, tata letak font, background , dll. Hingga terbentuklah dashboard dengan 4 teknik visualisasi data yaitu : Tree Map, Bar Chart, Pie Chart dan Parallel Coordinates serta visualisasi tambahan yang hanya menunjukkan nilai dari suatu variabel. Visualisasi tambahan ini bertujuan hanya untuk memperlihatkan nilai dari tiap indikator kriminalitas Indonesia. Visualiasi tambahan ini menggunakan gambar agar terlihat menarik. Gambar merupakan gambar yang diudnuh dari powerpoint template https://slidesgo.com/ .
  
  Selain itu diimplementasikan juga visualisasi data interaktif dengan fitur filter, selection, dan detail on demand. Fitur filter diterapkan untuk semua jenis visualisasi data.Fitur filter dengan bentuk dropdown menu ini untuk melakukan filter pada visualisasi data berdasarkan kategori tahun. Terdapat dua pilihan tahun yaitu, 2019 dan 2020. Maka, dashboard ini dapat menampilkan visualisasi data pada periode 2019 atau 2020. Selain itu, diterapkan juga fitur interaktif selection. Fitur ini hanya tersedia pada visualisasi data parallel coordinates. Fitur selection digunakan dengan cara menekan salah satu line pada plot yang merupakan profil dari suatu provinsi. Dengan menekan salah satu line, deskripsi yang berada tepat diatas plot akan berubah menyesuaikan provinsi yang dipilih dan line  yang tidak dipilih akan berwarna pudar, sedangkan line yang dipilih akan berwarna biru dan menonjol.Fitur interaktif selanjutnya adalah detail on demand.Fitur ini digunakan untuk menampilkan detail data dari salah satu variabel berdasarkan keinginan pengguna dengan cara menyorot variabel tersebut menggunakan kursor. Fitur ini diterapkan  pada visualisasi data Tree Map, Bar Chart, Pie Chart.
  
  Proses pembangunan dashboard lengkapnya dapat dilihat pada tableau workbook. Dimana terlihat sebelum membuat dashboard dibuat terlebih dahulu visualisasi data nya pada worksheet. Selanjutnya, tiap grafik pada worksheet akan disusun pada dashboard.

**Workbook Tableau : Dashboard.twb**

  Setelah dashboard sudah jadi. Selanjutnya, dashboard di-publish di Tableau Public agar dapat dikases publik. Berikut link tableau :
 
https://public.tableau.com/views/Dashboard_16555376991020/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
