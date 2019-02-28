<b>
<h1>
<i>SOFTWARE DESIGN DOCUMENT (SDD)</i>
</h1>
<ol>
<li>Pendahuluan</li>
	<ol>
	1.1. Tujuan<br>
	1.2. Lingkup<br>
	1.3. Definisi, akronim, dan singkatan<br>
	</ol>
<li>Referensi</li>
<li>Penjelasan Dekomposisi</li>
	<ol>
	3.1. Dekomposisi modul<br>
		<ol>
		3.1.1. Deskripsi modul 1<br>
		3.1.2. Deskripsi modul 2<br>
		</ol>
	3.2. Dekomposisi prosis konkuren<br>
		<ol>
		3.2.1. Deskripsi proses 1<br>
		3.2.2. Deskripsi proses 2<br>
		</ol>
	3.3. Dekomposisi data<br>
		<ol>
		3.3.1. Deskripsi entri data 1<br>
		3.3.2. Deskripsi entri data 2<br>
		</ol>
	</ol>
<li>Deskripsi Ketergantungan/Keterkaitan</li>
	<ol>
	4.1. Keterkaitan inter modul<br>
	4.2. Keterkaitan inter proses<br>
	4.3. Keterkaitan data<br>
	</ol>
<li>Deskripsi Antarmuka</li>
	<ol>
	5.1. Antarmuka modul<br>
		<ol>
		5.1.1. Deskripsi modul 1<br>
		5.1.2. Deskripsi modul 2<br>
		</ol>
	5.2. Antarmuka proses<br>
		<ol>
		5.2.1. Deskripsi proses 1<br>
		5.2.2. Deskripsi proses 2<br>
		</ol>
	</ol>
<li>Desain Detail/Rinci</li>
	<ol>
	6.1. Rinci modul<br>
		<ol>
		6.1.1. Rinci modul 1<br>
		6.1.2. Rinci modul 2<br>
		</ol>
	6.2. Desain data secara rinci<br>
		<ol>
		6.2.1. Rinci entiti data 1<br>
		6.2.2. Rinci entiti data 2<br>
		</ol>
</ol>
</ol>
</b>

<ol>
	<b>
	<li>Pendahuluan</li>
	</b>
		<ol>
			 <b>III.1.1 Tujuan</b><br>
			 <ol>
			 	Tujuan dalam membuat dokumen SSD(Software Design Description) ini adalah untuk menjelaskan langkh-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada aplikasi simulasi management proyek RPL dan juga memberi definisi kebutuhan untuk sistem spesifikasi kebutuhan fungsional.<br>
			 </ol>
			 <b>III.1.2 Ruang Lingkup</b><br>
			 <ol>
			 	Ruang lingkup SDD ini adalah penjelasan mengenai aplikasi simulasi management proyek RPL berbasis dekstop, ruang lingkup system ini mencakup informasi mengenai antarmuka dari system tersebut.<br>
			 </ol>
			 <b>III.1.3 Definisi, Akronim, dan Singkatan</b><br>
			 <ol>
			 	 Dalam penulisan dokumen pembuatan projek ini yang mungkin akan sulit di pahami berikut ini:<br>
			 	 SSD artinya Software Design Description<br>
			 	 OOP artinya Object Oriented Programmung<br>
			 	 User artinya untuk pengguna system<br>
			 </ol>
	<b>
	<li>Referensi</li>
	</b>
	<ol>
		a. Modul KULIAH RPL 7 DOKUMEN SDD <br>
		b. Contoh Software Design Document (SDD) Moch. Bambang Sulistio<br>
	</ol>
	<b>
	<li>Deskripsi Dekomposisi</li>
	</b>
	<ol>
		<b>III.3.1 Dekomposisi Modul<b><br>
		<ol>
			Kebutuhan fungsional (Functional Requirements) ini adalah kebutuhan utama yang diharapkan dari sistem ini, yang terkait langsung dengan sistem ini. Kebutuhan fungsional dari sistem ini adalah sebagai berikut: <br>
			<li>Pencatatan Hak Akses</li>
			<li>Pencatatan Nama aplikasi , Nama Kategori dan Nama Client </li>
			<li>Pencatatan Target Waktu , Jumlah Orang dan Biaya Aplikasi</li>
			Spesifikasi yang diharapkan pada Pencatatan Hak Akses:<br>
			<ul>Membedakan antara user dan admin dalam hak ases</ul>
			<ul>Sistem dapat memproses secara otomatis jika kita terdaftar dalam admin memiliki hak ases penuh dan sebaliknya juka terdaftar dalam user tidak memiliki hak ases penuh</ul>
			Spesifikasi yang diharapkan pada Pencatatan Target Waktu , Jumlah Orang dan Biaya Aplikasi :<br>
			<ul>Sistem dapat memproses secara otomatis target waktu aplikasi yang akan di buat dalam sebuah project</ul>
			<ul>Sistem dapat memproses secara otomatis jumlah orang dalam sebuah project</ul>
			<ul>Sistem dapat memproses secara otomatis biaya dalam sebuah aplikasi yang akan di buat</ul>
		</ol>
	</ol>
</ol>

