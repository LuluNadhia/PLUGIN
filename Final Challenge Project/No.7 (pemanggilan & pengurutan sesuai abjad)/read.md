PENJELASAN SOAL NO.7 

// penjalsan soal a 

Menambahkan array pada let sayuran = [ ]
untuk menambahkan array kita dapat menggunakan function unshift untuk mendapatkan sebuah output sebagi berikut :
[ 'Kangkung',
	'Bayam',
	'Buncis',
	'Kubis',
	'Timun',
	'Seledri',
	'Tauge' ]

untuk pengimplementasiannya seperti dibawah ini
let sayuran = [ ]; ==> variabel utama arraynya itu sayuran 

    sayuran.unshift([ 'Kangkung',    ==> penggunaan function unshif untuk meanpilkan output beberapa sayuran.
		  'Bayam',
		  'Buncis',
		  'Kubis',
		  'Timun',
		  'Seledri',
		  'Tauge' ]);
        console.log(sayuran); ==> untuk melakukan pemanggilannya

// penjelasan soal b 
urutkan sesuai dengan abjad isi array yang ada di variabel sayuran 
kita bisa menggunakan function sayuran.sort() untuk mengurutkan sayuran berdasarkan abjadnya. 

langkah awal kita deklarasikan variabelnya yang sudah berisikan array didalmmnya. 
let sayuran = [ 'Kangkung', ==> seperti contoh di samping ini 
		  'Bayam',
		  'Buncis',
		  'Kubis',
		  'Timun',
		  'Seledri',
		  'Tauge'];

sayuran.sort();  ==> lalu kita gunakan function sort untuk melakukan pengurutan sesuai abjad
console.log(sayuran); ==> untuk melakukan pemanggilan ulangnya. 
