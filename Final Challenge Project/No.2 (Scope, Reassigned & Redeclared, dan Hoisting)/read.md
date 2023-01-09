PENJELASNA SOAL NO.2 

## Scope, Reassigned dan Redeclared, dan Hoisting

1. Scope Adalah jangkauan kode program dimana perintah program masih bisa mengakses variabel. Jika kita mendefinisikan suatu variabel pada file PHP, maka variabel tersebut dapat diakses oleh seluruh kode program pada halaman yang sama. Sedangkan Scope di dalam JavaScript bisa dikatakan sebagai cakupan atau jangkauan program yang ditandai dengan tanda kurung kurawal atau curly brackets ({...}). Umumnya, variabel dalam scope akan dianggap sebagai local scope agar tidak bisa dibaca oleh scope lain. Tapi, jika kita menggunakan var, maka
variabel akan berubah menjadi global scope. Artinya, ia masih bisa diakses meski berada di dalam scope. Maka dari itu untuk memudahkannya digunakan lah variabel let. 

2. Redeclared berarti pendeklarasian variable dengan nama yang sama dalam scope yang sama. Jika kita menggunakan keyword var, maka hal ini diizinkan. Hal ini sangat berbahaya karena bisa menimbulkan bug di kemudian hari, terlebih jika terdapat lebih dari satu programmer yang mengerjakan codebase yang sama dan saling tidak aware terhadap nama variable yang digunakan masing-masing. Yang terjadi kemudian bisa ditebak, akan terjadi saling timpa variable di dalam codebase tersebut. Variabel var dapat di-update nilainya (reassigned) dan dapat di deklarasi ulang namanya (redeclared). 

3. Berbeda dengan var, yang akan “diangkat” ke bagian paling atas dalam scope dengan value “undefined”, pemanggilan variable let sebelum pendeklarasian akan menghasilkan error. Hoisting ini ibarat variabelnya “diangkat" atau “dipindahkan” ke atas. Maksudnya, gimana? Jika kita assign sebuah variabel var lebih dulu, JavaScript akan mendeklarasikan variabel tersebut ke atas atau mengangkatnya ke posisi atas di dalam scope. Hasilnya nggak akan error kok, tapi bakalan membuat kita bingung. Jadi, sebaiknya variabel dideklarasikan di awal sebelum di-assign. Untuk lebih jelasnya,coba perhatikan contoh di samping!

