// PENJELASAN SOAL NO.8 

mengambil tiap index dalam kalimat string disamping : "I am going to be React JS Developer".

console.log("First word : " + str[0]); ==> kita dapat melaukan pemanggilannya dengan menggunakan  console.log 
                                    ==> untuk menambahkan bebrapa kata di depanya "First word : " kemudian untuk menjadikan satunya dengan + pemanggilan kata pertamnya dengan nama variabelnya yaitu str[] di isi indeks urutan hurunya str[0] 'I' 

console.log("Second word : " + str.substring(2,4)); ==> ini juga sama seperti contoh yang pertama namun bedanya 
                                                        meminta menampilkan kata yang ke dua 'am' ang berisikan dua huruf. maka kita dapat memuli perhitungan hurufnya yg dimulai dari 0 dan spasi kata dihitung 1 namun untuk kata yang terakhir itu di + 1.  dari kata 'i am' -> huruf a itu berada pada urut ke 2 yg dimuli dari 0 dan m berada di urut ke 3 dan rumusnya itu di +1 menjadi 4. mana pemanggilannyan
                                                        str.substring(2,4)) -> terdapat penambahn substring (suatu kata atau karakter atau kalimat yang merupakan bagian dari sebuah String). bengitu pun untuk melakukan pemanggilan pada kata selajutnya dapat melakukan perhitungan urutan hurufnya terlebuh dulu. 
console.log("Third word : " + str.substring(5,11));
console.log("Fourth word : " + str.substring(11,13));
console.log("Fifth word : " + str.substring(13,17));
console.log("Sixth word : " + str.substring(17,23));
console.log("Seventh word : " + str.substring(23,25));
console.log("Eighth word : " + str.substring(25,35));