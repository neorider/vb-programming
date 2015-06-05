# Introduction #

<a href='http://fusion.google.com/ig/sharetab?source=atgt&atr=RSS%20Feed%202.0&n_32=url%3Dhttp%253A//feeds2.feedburner.com/VisualBasicWongCerbon%26row%3D1%26sect%3D1&n_32=url%3Dhttp%253A//www.podnova.com/add.srf%253Furl%253Dhttp%253A//feeds2.feedburner.com/VisualBasicWongCerbon%26row%3D1%26sect%3D2&n_32=url%3Dhttp%253A//fusion.google.com/add%253Ffeedurl%253Dhttp%253A//feeds2.feedburner.com/VisualBasicWongCerbon%26row%3D1%26sect%3D3'><img src='http://buttons.googlesyndication.com/fusion/add.gif' alt='Add to Google' border='0'><br />Komunitas Google<br>
<br>
Unknown end tag for </a><br>
<br>
<br>
<br>
<h1>Details</h1>

Untuk membangun sebuah Program Aplikasi pada Visual Basic 6.0 ada beberapa tahapan yang harus diketahui, hal ini untuk memudahkan kita dalam menganalisa, menyusun dan membuat aplikasi tersebut menjadi lebih mudah dikerjakan dan teratur sesuai dengan fungsinya. Tahapan tahapan tersebut yang pertama adalah mengumpulkan data yang akan di jadikan sebagai bahan dasar dan yang kedua adalah membuat prosedur alur program.<br>
Saya akan memberikan salah satu cara membangun program dengan satu kasus dalam divisi keuangan di suatu perusahaan, dimulai dari data dikumpulkan, membuat database, user interface, transaksi sampai dengan hasil akhir berupa laporan / report<br>
<br>
1.1	Data Mentah<br>
Data mentah yang dimaksud adalah data dasar yang dibutuhkan dalam membuat sebuah Program Aplikasi, dalam kasus tersebut diatas saya mendapatkan data data secara garis besar sebagai berikut :<br>
Printout Transaksi<br>
Tanggal	Keterangan	Debet	Kredit	Saldo<br>
1 Desember 2008	Beli ATK	0	50,000	(50,000)<br>
2 Desember 2008	Pendapatan Usaha	100,000	0	50,000<br>
3 Desember 2008	Transfer Bpk. Fany	0	10,000	40,000<br>
<br>
.<br>
<blockquote>Printout Buku Besar Kas<br>
Tanggal	Keterangan	Debet	Kredit	Saldo<br>
2008 Des<br>
</blockquote><ol><li>50,000	(50,000)<br>
</li></ol><blockquote>2		100,000		50,000<br>
3			10,000	40,000</blockquote>

1.2	Prosedur Program Aplikasi<br>
Setelah data terkumpul dan untuk tahapan selanjutnya adalah membuat prosedur program aplikasi, tahapan ini dimaksudkan agar Anda dapat dengan mudah merancang dan membangun sebuah system kerja, disamping itu program yang dihasilkan akan menjadi lebih baik dan terarah sehingga dapat menjadi sebuah system yang bisa dihandalkan.<br>
Sebagai contoh :<br>
Untuk membuat prosedur pengolahan data Akuntansi sebagai berikut :<br>
a.	Database, membuat database sebagai sumber informasi serta menganalisa dan merancang table yang akan digunakan sehingga sumber data dapat terhindar dari redundancy atau penggandaan file, struktur table dapat menentukan kinerja program yang akan dibuat.<br>
Struktur table yang baik adalah setiap table dapat berhubungan / relasi dengan table yang lainya sehingga mempermudah system dalam menggabungkan informasi dari table yang berbeda, disamping itu juga dalam menentukan type data dari sebuah field harus sesuai dengan kebutuhan informasi dan hindari nama field yang berulang ulang tetapi fungsi dan kebutuhanya sama.<br>
b.	Membuat Rancangan User Interface, membuat rancangan design untuk interaksi user dengan system agar mempermudah user dalam melakukan pengolahan data, diantaranya adalah sebagai berikut :<br>
1.	Membuat rancangan hak akses user, melindungi sistem dari tangan yang tidak bertanggung jawab, artinya program yang akan dibuat tidak sembarang user dapat menggunakannya dan masing masing user mendapatkan hak akses yang berbeda sesuai dengan tanggung jawab yang didapatkanya, hak akses tersebut yaitu :<br>
Administrator, memiliki hak akses  penuh terhadap sistem..<br>
Presdir/Manager Keuangan, memiliki hak akses untuk menampilkan laporan yang sudah terbentuk secara otomatis seperti Laporan Laba/Rugi, Neraca, Kas Kecil, Kas Bank, hutang dan piutang usaha<br>
Kas Kecil, memiliki hak akses untuk melakukan transaksi pada kas kecil<br>
Kas Besar, memiliki hak akses untuk melakukan transaksi pada kas Besar<br>
Kas Bank, memiliki hak akses untuk melakukan transaksi pada kas Bank<br>
Hutang Usaha, memiliki hak akses untuk melakukan transaksi pada Hutang Usaha seperti pengakuan dan pembayaran atas hutang usaha.<br>
Piutang Usaha, memiliki hak akses untuk melakukan transaksi pada Piutang Usaha seperti pengakuan dan penerimaan pembayaran atas piutang usaha.<br>
2.	Membuat Menu dan Sub Menu, dimaksudkan untuk mempermudah Anda dalam menentukan isi dari sebuah system, disamping itu Anda dapat mengintegrasikan Aplikasi menjadi kesatuan yang saling berhubungan<br>
3.	Membuat Laporan, merancang dan membuat Laporan sesuai dengan Informasi / hasil dari pengolahan data yang akan dibutuhkan, ini merupakan tahap akhir dari membangun sebuah system Program Aplikasi.