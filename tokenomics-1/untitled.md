---
description: Tokenomics
---

# Cara Kerja Gyro

**Cara Kerja Gyro:**

Setiap token GYRO didasarkan oleh 1 USD (misalnya USDT, DAI, BUSD, USDC) di treasury.

Kami awalnya akan memulai dengan USDT sebagai aset treasury. Setelah peluncuran, kami akan menambahkan stablecoin lainnya untuk menyeimbangkan treasury, yang  akan mencakup DAI, BUSD, USDC, dll.

Token tidak dapat dicetak atau dibakar oleh siapa pun kecuali oleh protokol.

Protokol hanya akan mencetak atau membakar token sebagai respons terhadap harga.

GYRO tidak melakukan rebase. Sebaliknya, pasokan baru dibuat melalui penjualan langsung ke pasar dan dibakar melalui pembelian langsung dari pasar. Dengan cara ini, GYRO tetap didasarkan oleh aset riil di treasury, yakni USD.

Hal ini pada dasarnya bisa diartikan menjadi:

Pada saat GYRO diperdagangkan ↓ 1 USDT, protokol akan membelinya kembali dan membakar GYRO.

Pada saat GYRO diperdagangkan  ↑1 USDT, protokol akan mencetak dan menjual GYRO baru.

Hal ini dikarenakan treasury harus memegang setidaknya 1 USDT dan hanya membutuhkan 1 USDT untuk tiap GYRO pada saat dibeli atau dijual sehingga menghasilkan keuntungan. Berarti protokol akan mendapatkan lebih dari 1 USDT dari sisi penjualan atau menjual kurang dari 1 USDT dari sisi pembelian.

Mengingat fakta bahwa protokol memegang USDT untuk setiap token memungkinkan kami untuk menjamin bahwa GYRO tidak akan diperdagangkan di bawah nilai intrinsiknya dalam jangka panjang.

Investasi kemudian dapat dilakukan dengan risiko yang pasti karena 1 USDT adalah jaminan harga dasar dalam jangka panjang. Oleh karena itu, protokol dapat dan akan membeli tanpa batas di bawah 1 USDT sampai tidak ada penjual yang tersisa, bahkan jika pasokannya dikurangi menjadi 0. Pada event tersebut akan memberikan hadiah besar kepada mereka yang tidak menjual tokennya karena akan berakhir dengan sepotong dari setiap token yang dibakar!

Memegang stablecoin sebagai basis token juga menciptakan peluang menghasilkan yield.

Mengunci stablecoin di vault tentu saja akan percuma, mengingat bahwa protokol tidak pernah membutuhkan lebih dari beberapa persen cadangan, bahkan pada saat penurunan harga besar-besaran, kamu bebas menggunakan sisanya untuk dihubungkan ke yield aggregator dan menambahkan hasil tersebut kedalam keuntungan dari membeli dan menjual GYRO.

**Distribusi keuntungan awal Gyro**

90% untuk para staker

10% untuk organisasi otonom terdesentralisasi atau DAO (alokasi ini akan diubah jika perlu, tergantung bagaimana keputusan DAO).

Semua bonus dibayarkan dalam bentuk GYRO yang didasarkan oleh stablecoin.

Sistem ini akan mempertahankan nilai intrinsik yang stabil dan mengurangi peran insentif dari apresiasi yang mendukung akumulasi. Seperti halnya mata uang, kamu tentu akan mencoba mengumpulkan lebih banyak dolar dan tidak perlu berharap bahwa dolar menjadi lebih berharga. Meskipun keduanya bisa saja terjadi.

**Staking dan Rebasing**

Protokol mendistribusikan token dengan mengirimkannya ke kontrak staking tanpa meminta sGYRO kembali. Hal ini meningkatkan rasio GYRO yang distake terhadap sGYRO yang beredar. Dengan demikian, rebase dihasilkan untuk memperbaiki untuk memperbaiki perbedaan nilai.

Misalnya: ada 500 ribu GYRO yang distake dan 500 ribu sGYRO yang beredar. Protokol menghasilkan keuntungan sebesar $5 ribu pada hari tersebut yang digunakan untuk mencetak dan mendasarkan sejumlah 5 ribu GYRO. Kemudian GYRO tersebut dikirimkan ke kontrak staking; saat ini menjadi total 505 ribu GYRO yang distake dan 500 ribu sGYRO yang beredar. Oleh karena itu, pasokan sGYRO perlu ditingkatkan sebesar 5 ribu, atau 1%, untuk kembali seimbang. Jadi, sGYRO di-rebase sebesar 1% . Satu-satunya hal yang perlu diingat adalah bahwa rebase terjadi secara retroaktif. Misalnya pada akhir epoch 100 memicu rebase keuntungan dari epoch 99. Penundaan ini memungkinkan kamu melihat apa yang hilang jika kamu ingin untuk unstake atau apa yang akan didapatkan jika kamu ingin untuk stake.

Staking merupakan cara memperoleh keuntungan yang didistribusikan secara adil kepada para pengguna. Melalui sGYRO, setiap orang akan mendapatkan persentase keuntungan yang sama untuk setiap epoch. Oleh karena itu, rebasing juga memberi kita kesempatan untuk mengumpulkan hasil tanpa harus memanen atau melakukan apa pun selain holding.

**Bonding**

Bonding merupakan proses trading pembagian LP dengan protokol untuk GYRO. Protokol akan memberikan data jumlah GYRO dan periode vesting untuk trade. Penting untuk diketahui: **Pada saat kamu membuat bond, kamu berarti menyerahkan bagian LP kepada protokol**. Kemudian Protokol memberikan kompensasi dengan lebih banyak GYRO daripada yang kamu dapatkan di market, tetapi aset kamu sekarang menjadi GYRO sepenuhnya dan tidak lagi dalam bentuk GYRO-USDT LP.&#x20;

_Perlu diperhatikan bahwa sGYRO merupakan token perolehan keuntungan protokol karena bonder mendapatkan GYRO (bukan sGYRO), sedangkan para staker mendapatkan 100% dari keuntungan protokol (dikurangi potongan dari DAO)._

**Mengapa saya membutuhkan Bond?**

Karena kamu berkesempatan untuk membeli GYRO dengan biaya lebih rendah. Sebagai keuntungan dari menjual LP, protokol akan menjual GYRO kepada kamu dengan harga diskon.

**Dinamika mengenai Bond**

Protokol memberikan data harga bond berdasarkan protokol nilai bebas risiko (RFV). Bond Premium merupakan suatu kebijakan yang diatur protokol dalam mengontrol premi yang dibebankan untuk bond. Premi yang lebih rendah berarti diskon yang lebih tinggi dan insentif yang lebih tinggi untuk bond.

_Harga Eksekusi = RFV / Premi {Premi 1}_

Premi ditentukan oleh jumlah hutang sistem serta variabel penskalaan. Hal ini menentukan harga bond sesuai dengan jumlah bond yang beredar; semakin sedikit bond yang beredar, semakin rendah premi dan semakin tinggi diskon.

Premi = 1 + (Rasio Hutang \* BCV) Rasio Hutang = Peredaran Bond / Pasokan GYRO

Nilai bebas risiko dari pembagian LP untuk protokol adalah titik dimana pool setara (1 GYRO = 1 USDT). Ketika protokol harus melindungi pendasaran GYRO, maka hal ini menjadi harga terendah yang dapat diberlakukan; atau hal terburuknya dapat dikembalikan setiap 2 GYRO yang didasarkan oleh 1 USDT dan 1 GYRO. Di atas titik ekuilibrium ini, ada kelebihan USDT. Sedangkan di bawah ekuilibrium, ada kelebihan GYRO. Keduanya sebenarnya dapat digunakan dan akan selalu mecukupi.

_Nilai Bebas Risiko = (LP / Total LP) \* 2sqrt(Produk Konstan)_&#x20;

Hal ini berarti setiap bonder pada umumnya akan menjual LP mereka di bawah nilai pasar. Namun, hal ini bisa dibatalkan oleh protokol yang membuat bonding GYRO di bawah nilai pasar.

**Skala linear**

Peningkatan eksponensial nilai bond GYRO tergantung nilai LP yang diperkirakan akan membuat peningkatan permintaan bond dengan harga yang lebih tinggi. Fenomena ini merupakan dinamika yang sangat menguntungkan; karena semakin tinggi harga (dan semakin banyak protokol yang dijual sebagai respon), maka semakin banyak likuiditas yang tersedia. Bonders dapat melakukan trade ini, terlepas dari risiko waktu, karena breakeven point mereka telah berkurang. Semakin tinggi harganya, maka semakin besar paddingnya.

**Kesimpulan**&#x20;

Tujuan Gyro adalah untuk menawarkan token aset kelas baru yang dapat menjadi bagian dari portfolio apapun. Gyro dapat digunakan untuk melindungi aset berisiko disamping menawarkan insentif yang lebih aman dan lebih baik daripada stablecoin.
