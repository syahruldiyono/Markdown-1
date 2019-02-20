<b>
<h1>
<i>Software Required Speciifcation (SRS)</i>
</h1>

<ol>
	<li>Pendahuluan</li>
		<ol>
			 1.1 Tujuan<br>
			 1.2 Lingkup<br> 
			 1.3 Definisi, akronim, singkatan<br>
			 1.4 Referensi<br>
			 1.5 Overview<br>
		</ol>
	<li>Gambaran Umum</li>
		<ol>
			2.1 Perspektif<br>
			<ol>
				2.1.1 Antarmuka sistem<br>
				2.1.2 Antarmuka pengguna<br>
				2.1.3 Antarmuka perangkat keras<br>
				2.1.4 Antarmuka perangkat lunak<br>
				2.1.5 Antarmuka komunikasi<br>
				2.1.6 Batasan-batasan memori<br>
				2.1.7 Operasi-operasi<br>
				2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi<br></ol>
			2.2 Fungsi-fungsi produk<br>
			2.3 Karakteristik pengguna<br>
			2.4 Batasan-batasan<br>
			2.5 Asumsi-asumsi dan ketergantungan<br>
			2.6 Kebutuhan-kebutuhan penyeimbang
		</ol>
	<li>Kebutuhan lain yang spesifik</li>
	<li>Informasi pendukung</li>
</ol></b>
<ol>
<b> <li> Pendahuluan</li> </b>

<b>1.1	Tujuan<br></b>
	<ol>Dokumen ini berisi Spesifikasi Kebutuhan Perangkat Lunak (SKPL) atau Software Requirement Spesification (SRS)  untuk Sistem Penjualan Aksesoris dan Sparepart Handphone.Tujuan dari penulisan dokumen ini adalah untuk memberikan penjelasan mengenai perangkat lunak yang akan dibangun baik berupa gambaran umum maupun penjelasan detil dan menyeluruh.</ol><br>
	<ol>Pengguna dari dokumen ini adalah pengembang perangkat lunak sistem Penjualan Aksesoris dan Sparepart Handphone pengguna (user) dari perangkat lunak atau personil-personil yang terlibat dalam sistem.Dokumen ini akan digunakan sebagai bahan acuan dalam proses pengembangan dan sebagai bahan evaluasi pada saat proses pengembangan  perangkat lunak maupun di akhir pengembangannya. Dengan adanya dokumen SKPL ini diharapkan pengembangan perangkat lunak akan lebih terarah dan lebih terfokus serta tidak menimbulkan ambiguitas terutama bagi pengembang perangkat lunak Penjualan Aksesoris dan Sparepart Handphone.</ol><br>
<b>1.2	Lingkup Masalah<br></b>
	<ol>Perangkat lunak yang akan dikembangkan adalah perangkat lunak Penjualan Aksesoris dan Sparepart Handphone, yaitu merupakan perangkat lunak yang digunakan untuk mempermudah proses administrasi dan penjualan Aksesoris dan Sparepart Handphone. Aplikasi Aksesoris dan Sparepart Handphone ini dapat melakukan hal-hal berikut ini :</ol><br>
<ol>
1.2.1 Fasilitas Login untuk admin, dan karyawan/kasir untuk menghindari penyalahgunaan hak akses.<br>
1.2.2 Menampilkan daftar Aksesoris dan Sparepart Handphone yang tersedia.<br>
1.2.3 Melayani penjualan Aksesoris dan Sparepart Handphone secara onlineberbasis web dan wap, dan  juga  transaksi dapat dilakukan dari manapun dan kapanpun.<br>
1.2.4 Admin dan karyawan dapat melihat rekapitulasi hasil penjualan
Dengan adanya Aplikasi ini.<br>
</ol><br>
<b>1.3	Definisi, Akronim dan Singkatan</b><br>

   <ol>Istilah, Akronim dan Singkatan beserta Keterangannya :</ol><br>
 	<ol>
 	1. Admin Merupakan seseorang yang bertanggungjawab untuk perawatan sistem dan  serta bertanggungjawab terhadap operasional sistem.<br>
 	2. User merupakan Karyawan/kasir.<br>
 	3. Pembeli Merupakan orang yang akan membeli. <br>
 	4. web adalah halaman informasi yang disediakan melalui jalur internet sehingga bisa diakses di seluruh dunia selama terkoneksi dengan internet.<br>
 	5. wap adalah standar internasional terbuka untuk aplikasi yang menggunakan komunikasi nirkabel. Tujuan utamanya untuk membangun aplikasi yang dapat mengakses internet dari telepon genggam atau PDA.<br>
 	6. Transaction report merupakan Laporan rekapitulasi transaksi per satu transaksi.<br>
 	7. Monthly report merupakan Laporan rekapitulasi transaksi per satu bulan.<br>
 	</ol><br>
<b>1.4	Referensi</b><br>
	<ol>Dokumen-dokumen yang digunakan sebagai referensi dalam pembuatan SKPL ini adalah sebagai berikut:</ol><br>
	<ol>
    1.4.1 DOKUMEN1: menjelaskan tentang database system dan database pelanggan.<br> 
    1.4.2 DOKUMEN2: daftar barang, deskripsi barang, Jumlah barang.<br>
    1.4.3 DOKUMEN3: format keluhan standar.<br>
    </ol><br>

<b>1.5	Deskripsi Umum Dokumen</b><br>
	<ol>Dokumen ini secara garis besar terdiri dari tiga bab dengan perincian sebagai berikut:</ol><br>
	<ol>
	1.5.1 Bab 1 Pendahuluan, merupakan pengantar dokumen  SKPL yang brisi tujuan penulisan dokumen, lingkup masalah pengembangan perangkat lunak, juga memuat definisi, akronim dan istilah yang digunakan  serta deskripsi umum dokumen yang merupakan ikhtisar dokumen SKPL.<br>
	1.5.2 Bab 2 Deskripsi Global Perangkat Lunak, mendefinisikan perspektif produk perangkat lunak serta asumsi dan ketergantungan yang digunakan dalam pengembangan aplikasi penjualan Aksesoris dan Sparepart Handphone.<br>
	</ol><br>
</ol>
