PENJELAS SOAL NO.6 

Untuk menghilangkan tanda ! pada kalimat let kalimat = "Hello! Wo!rld!"
kita bisa menggunakan function remove digunakan untuk membuang item dari sebuah object.

function remove (x){ ==> seperti pada contoh disamping dimana function remove akan menghapus variable x

let kalimat = x.split('!') ==> nah disini, kita akan mengambil data atau memcahkan data dan akan di tampilkan pada output dengan menggunakan fungsi split. Diaman variabel x ini disi dengan '!'. Hasil dari split() mengandung array dimana dalam pemanggilannya dimulai dari nol (0).

return kalimat.join(''); ==> Method join() membuat dan mengembalikan string baru dengan menggabungkan semua elemen array dengan pemisah koma atau pemisah yang ditentukan. Nah kan seblumnya sudah melakukan remove variabel x yang dimana berisi ! maka kalimat yang tadinya 'Hello! Wo!rld!' jika sudah dilakukan metode spilt() maka akan di kembalikan dengan menggunakan fungsi join() menjadi 'Hello World'

console.log(remove('Hello! Wo!rld!')) ==> untuk mencetak ulang hasil remove maka kita dapat memanggilnya ulang dengan contoh dengan console.log untuk print ulang. 