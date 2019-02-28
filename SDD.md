<ol>
	<b>III.3.2 Dekomposisi Proses Konkuren</b><br> 
	<ol> Konkurensi adalah proses-proses (lebih dari satu proses) yang terjadi pada saat bersamaan. Konkurensi merupakan landasan umum perancangan sistem operasi. 
	Proses-proses disebut konkuren jika proses-proses berada pada saat yang sama. Pada proses-proses konkuren yang berinteraksi mempunyai beberapa masalah yang harus diselesaikan:<br></ol>
	  <ol> 
		<li>Mutual Exclusion</li> 
		<li>Sinkronisasi</li> 
		<li>Deadlock</li> 
		<li>Startvation</li>
	  </ol> 
 	Pada sistem dengan banyak proses (kongkuren), terdapat 2 katagori interaksi, yaitu:<br> 
		<li>Proses-proses Saling Tidak Peduli (Independen). 
		Proses-proses ini tidak dimaksudkan untuk bekerja untukmencapai tujuan tertentu. Pada multiprogramming dengan proses-proses independen, dapat berupa batch atau sesi interaktif, atau campuran keduanya.</li>
		<li>Proses-proses Saling Mempedulikan Secara Tidak Langsung. Proses-proses tidak perlu saling mempedulikan identitas proses-proses lain, tapi sama-sama mengakses objek tertentu, seperti buffer masukan/keluaran. Proses-proses itu perlu bekerja sama (cooperation) dalam memakai bersama objek tertentu.<li><br> 
		<li>Proses-proses konkuren mengharuskan beberapa hal yang harus ditangani, antara lain:<br></li> 
		  <ol>
			a. Sistem operasi harus mengetahui proses-proses yang aktif<br>
			b. Sistem operasi harus mengalokasikan dan mendealokasikan beragam sumber daya untuk tiap proses aktif. Sumber daya yang harus dikelola, 
			antara lain:<br>
			  <ol>
				<li>Waktu pemroses.</li>
				<li>Memori.</li> 
				<li>Berkas-berkas.</li> 
				<li>Perangkat I/O</li>
			  </ol>
			c. Sistem operasi harus memproteksi data dan sumber daya fisik masingmasing proses dari gangguan proses-proses lain.<br>
			d. Hasil-hasil proses harus independen terhadap kecepatan relatif prosesproses lain dimana eksekusi dilakukan.<br>
		  </ol>
</ol>
 