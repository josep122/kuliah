PENJELASAN

Source 1 :
Cara kerja CPU dalam melaksanakan pernyataan if adalah; pertama CPU masuk dan mengevaluasi ekspresi yang tertera pada kondisi pernyataan if, jika bernilai benar (true) maka pernyataan-pernyataan di dalam pernyataan if akan dijalankan, setelah dijalankan maka CPU akan keluar dari keseluruhan pernyataan if. Jika salah (false) dan disertakan pernyataan else if maka CPU akan mengevaluasi ekspresi pada else if, jika bernilai benar (true) maka akan dijalankan, jika salah (false) akan beralih ke-lainnya, hal itu terjadi berulang-ulang hingga menemukan kondisi yang bernilai benar. jika dari semua pilihan tersebut tidak ada yang memiliki nilai benar (true) maka pernyataan secara keseluruhan if akan diabaikan atau menjalankan pernyataan else jika disertakan.

Source 2 :
Membuat daftar perkalian 3 dari 1 - 10, Tentu	saja	perkalian tersebut 	bisa	dihasilkan	dengan	membuat	perintah printf sebanyak	10	kali, namun	hal	itu	tidak	efisien.	Hasil	di	atas	harus	dibuat	menggunakan	perulangan FOR. Disini	 saya	 menggunakan	 sebuah	 perulangan	 FOR.	 Perulangan	 mulai	 dari	 variabel counter i = 1 sampai i <= 10.	Sepanjang	perulangan,	tampilkan	hasil dari printf(“3 * %i = %i\n”,i,3*i). Yang akan secara otomatis akan menghasilkan output baris pada perkalian 3 dari 1 - 10 ini.