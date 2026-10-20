# Analisis Komparatif Platform

**Mata kuliah:** Pemrograman Berbasis Platform
**Nama:** Ayu Natasya
**NIM:** 240511018

## Bagian 2: Analisis Platform Web, Desktop, dan Mobile

**Platform web** adalah aplikasi yang dijalankan lewat browser dan terhubung ke server melalui internet. Pengguna tidak menyimpan aplikasinya di perangkat, mereka hanya membuka alamat (URL) lalu halamannya dimuat dari server.

**Platform desktop** adalah aplikasi yang dipasang dan dijalankan langsung di komputer atau laptop, baik Windows, macOS, maupun Linux. Aplikasinya hidup di komputer pengguna dan memakai sumber daya komputer itu secara langsung.

**Platform mobile** adalah aplikasi yang dibuat khusus untuk ponsel dan tablet, terutama Android dan iOS. Aplikasi dipasang dari toko aplikasi dan bisa memanfaatkan fitur bawaan ponsel seperti kamera, GPS, dan notifikasi.

### 1. Bahasa utama

**Web.** Pengembangan web biasanya dibagi dua sisi. Sisi client (front-end) berjalan di browser dan memakai tiga bahasa dasar: HTML untuk struktur halaman, CSS untuk tampilan, dan JavaScript untuk interaksi. Di atasnya sering dipakai library atau framework seperti React, Vue, atau Bootstrap supaya pengerjaan lebih cepat.

Sisi server (back-end) lebih bebas memilih bahasa. Beberapa yang umum adalah PHP (misalnya dengan framework Laravel), Python (Django atau Flask), JavaScript lewat Node.js, dan Java dengan Spring. Bahasa-bahasa ini bertugas memproses request, menjalankan logika aplikasi, dan berhubungan dengan database seperti MySQL atau PostgreSQL.

**Desktop.** Pilihan bahasanya lebih banyak mengikuti sistem operasi dan jenis aplikasinya. Untuk Windows, C# dengan WPF atau Windows Forms cukup populer, dan C++ dengan Win32 atau Qt dipakai untuk aplikasi yang butuh performa tinggi. Java bisa dipakai lewat JavaFX atau Swing, sedangkan Python bisa dipakai lewat Tkinter atau PyQt untuk aplikasi yang lebih sederhana.

Ada juga pendekatan lain, yaitu membuat aplikasi desktop dengan teknologi web memakai Electron. Dengan cara ini developer web bisa membuat aplikasi desktop memakai HTML, CSS, dan JavaScript.

**Mobile.** Untuk aplikasi native Android, bahasa utamanya Kotlin (yang sekarang paling disarankan) dan Java. Untuk iOS, bahasanya Swift. Karena membuat dua versi terpisah itu memakan waktu, banyak developer memilih framework lintas platform seperti Flutter yang memakai Dart, atau React Native yang memakai JavaScript, sehingga satu kode bisa dijalankan di Android dan iOS.

### 2. Arsitektur

**Web.** Aplikasi web memakai model client-server. Browser sebagai client mengirim request lewat protokol HTTP atau HTTPS, lalu server memproses request itu dan mengirim balik response, biasanya berupa halaman HTML atau data dalam format JSON.

Pada aplikasi yang lebih besar, struktur di server biasanya dipisah menjadi beberapa lapisan: tampilan, logika bisnis, dan data. Pola MVC (Model, View, Controller) yang dipakai Laravel adalah salah satu contohnya. Komunikasi antar bagian sering memakai REST API, sehingga bagian front-end dan back-end bisa dikembangkan terpisah.

**Desktop.** Aplikasi desktop berjalan langsung di sistem operasi, jadi memakai CPU, memori, dan penyimpanan komputer pengguna tanpa perantara browser. Bentuknya biasanya satu aplikasi utuh yang berisi tampilan sekaligus logika programnya.

Kalau aplikasinya perlu berbagi data antar pengguna, misalnya aplikasi kasir di toko dengan beberapa komputer, aplikasi desktop akan terhubung ke database di jaringan atau ke server lewat API. Jadi arsitekturnya bisa berupa aplikasi mandiri (standalone) atau client-server, tergantung kebutuhan.

**Mobile.** Aplikasi mobile berjalan di atas sistem operasi ponsel dan mengikuti aturan siklus hidup (lifecycle) yang ditentukan OS. Contohnya, saat pengguna pindah ke aplikasi lain atau layar terkunci, aplikasi bisa dijeda atau dihentikan oleh sistem untuk menghemat baterai dan memori, sehingga developer harus menyimpan kondisi aplikasi dengan benar.

Untuk data yang berasal dari internet, aplikasi mobile biasanya memanggil back-end lewat REST API. Artinya, satu layanan bisa punya satu back-end yang sama dan dipakai oleh versi web, versi mobile, bahkan versi desktop sekaligus.

### 3. Cara distribusi

**Web.** Aplikasi di-deploy ke server atau layanan hosting, lalu diberi alamat domain. Pengguna cukup membuka alamat itu di browser tanpa memasang apa pun. Kalau ada perbaikan atau fitur baru, developer hanya memperbarui di server dan semua pengguna langsung memakai versi terbarunya. Hal ini membuat proses distribusi web menjadi yang paling sederhana dibanding dua platform lain.

**Desktop.** Distribusi biasanya lewat file installer, misalnya .exe atau .msi di Windows, .dmg di macOS, dan .deb di beberapa distribusi Linux. File ini diunduh dari situs resmi pembuatnya. Selain itu, ada juga toko aplikasi seperti Microsoft Store atau Mac App Store.

Pembaruan dilakukan dengan menjalankan installer versi baru atau lewat fitur pembaruan otomatis (auto-update) yang dibuat di dalam aplikasinya. Supaya tidak dianggap berbahaya oleh sistem, installer yang dibagikan sebaiknya ditandatangani secara digital (code signing).

**Mobile.** Aplikasi didistribusikan lewat toko resmi, yaitu Google Play Store untuk Android dan App Store untuk iOS. Developer harus mendaftar akun developer, mengunggah aplikasi, lalu menunggu proses review dari pengelola toko sebelum aplikasi bisa diunduh publik.

Di Android, aplikasi juga bisa dibagikan sebagai file APK dan dipasang langsung, tetapi pengguna harus mengizinkan pemasangan dari sumber di luar toko. Di iOS cara seperti ini jauh lebih terbatas.

### 4. Keunggulan

**Web.**
- Bisa dibuka dari perangkat apa saja yang punya browser dan koneksi internet, baik laptop, komputer kampus, maupun ponsel.
- Pengguna tidak perlu memasang aplikasi, jadi hambatan untuk mulai memakai sangat kecil.
- Pembaruan cukup dilakukan di satu tempat, jadi semua pengguna selalu memakai versi yang sama.
- Mudah dibagikan hanya dengan mengirim link.
- Cocok untuk aplikasi yang datanya dipakai banyak orang secara bersamaan, seperti sistem informasi, toko online, dan portal.

**Desktop.**
- Performanya umumnya paling baik karena langsung memakai sumber daya komputer.
- Punya akses yang luas ke file, printer, USB, dan perangkat keras lain.
- Banyak aplikasi desktop tetap bisa dipakai tanpa internet.
- Cocok untuk pekerjaan berat seperti editing video, desain grafis, pemrograman, dan pengolahan data besar.
- Antarmukanya bisa dibuat kaya fitur, misalnya banyak jendela, pintasan keyboard, dan menu yang kompleks.

**Mobile.**
- Bisa memakai fitur ponsel seperti kamera, GPS, sensor, sidik jari, dan notifikasi push.
- Ponsel selalu dibawa pengguna sehingga aplikasinya bisa dipakai kapan saja dan di mana saja.
- Jumlah pengguna ponsel sangat besar, jadi jangkauan pasarnya luas.
- Dengan Flutter atau React Native, satu kode bisa dipakai untuk Android dan iOS sehingga lebih hemat waktu dan biaya.

### 5. Keterbatasan

**Web.**
- Hampir selalu butuh koneksi internet, dan kalau koneksi lambat pengalaman pengguna ikut terganggu.
- Akses ke perangkat keras dibatasi oleh browser demi keamanan.
- Tampilan dan perilaku bisa sedikit berbeda antar browser sehingga perlu diuji di beberapa browser.
- Performanya umumnya di bawah aplikasi native, terutama untuk proses yang berat.
- Server harus dijaga keamanannya dan harus kuat menghadapi banyak pengguna sekaligus.

**Desktop.**
- Harus dipasang di setiap komputer dan diperbarui satu per satu.
- Aplikasi native biasanya hanya untuk satu sistem operasi, jadi kalau mau jalan di Windows, macOS, dan Linux perlu versi yang berbeda atau framework lintas platform.
- Tidak bisa dibuka dari perangkat yang belum terpasang aplikasinya.
- Aplikasi berbasis Electron cenderung memakai memori yang cukup besar.
- Pengguna harus mengunduh dari sumber yang tepercaya, karena risiko file berbahaya lebih besar dibanding web.

**Mobile.**
- Harus lolos review toko aplikasi dan mengikuti aturan yang berlaku, sehingga rilis versi baru kadang tidak instan.
- Ukuran layar dan versi sistem operasi sangat beragam, terutama di Android, sehingga perlu banyak pengujian.
- Baterai, memori, dan penyimpanan ponsel terbatas.
- Pengembangan aplikasi iOS memerlukan perangkat Apple (macOS) dengan Xcode.
- Kalau membuat versi native, Android dan iOS ditulis terpisah sehingga biaya dan waktunya lebih besar.

### 6. Contoh aplikasi

**Web.**
- Tokopedia (situs web) untuk belanja online.
- Wikipedia sebagai ensiklopedia daring.
- Google Docs untuk mengetik dokumen bersama-sama lewat browser.
- Canva versi web untuk desain grafis.
- Portal akademik kampus untuk melihat jadwal dan nilai.

**Desktop.**
- Microsoft Word untuk mengetik dokumen.
- Visual Studio Code sebagai editor kode (dibuat dengan teknologi Electron).
- Adobe Photoshop untuk mengolah gambar.
- Aplikasi kasir (POS) yang dipasang di komputer toko.

**Mobile.**
- WhatsApp untuk berkirim pesan.
- Gojek untuk transportasi dan layanan antar.
- Instagram untuk media sosial.
- Traveloka untuk pesan tiket dan hotel.
- Aplikasi mobile banking untuk transaksi perbankan.

### Perbandingan singkat

Kalau dilihat dari sisi kemudahan akses, web paling unggul karena cukup dibuka lewat browser. Dari sisi performa dan kebebasan memakai perangkat keras, desktop paling kuat. Dari sisi kedekatan dengan pengguna sehari-hari dan fitur ponsel, mobile paling unggul.

Ketiga platform ini sebenarnya tidak berdiri sendiri-sendiri. Banyak layanan yang punya versi web, desktop, dan mobile sekaligus, misalnya WhatsApp dan Spotify, dan sering kali ketiganya memakai satu back-end yang sama. Teknologi web juga makin sering dipakai untuk platform lain, misalnya Electron untuk desktop dan React Native untuk mobile.

### Kapan memilih platform tertentu

- Pilih **web** kalau aplikasi perlu diakses banyak orang dari berbagai perangkat tanpa instalasi, misalnya sistem informasi kampus atau toko online.
- Pilih **desktop** kalau aplikasi butuh performa tinggi, bekerja dengan file besar, atau harus bisa dipakai tanpa internet, misalnya editor video atau aplikasi kasir.
- Pilih **mobile** kalau fitur utamanya bergantung pada ponsel, misalnya kamera, lokasi, atau notifikasi, seperti aplikasi transportasi online atau mobile banking.

## Referensi

1. Aalto University. *Architecture: Client-server Model*. FITech101. https://fitech101.aalto.fi/web-software-development/2-internet-and-http/4-architecture-client-server-model (diakses 20 Oktober 2026)
2. Mozilla Developer Network. *Learn web development*. https://developer.mozilla.org/en-US/docs/Learn (diakses 20 Oktober 2026)
3. Microsoft. *Build desktop apps for Windows*. Microsoft Learn. https://learn.microsoft.com/windows/apps/desktop (diakses 20 Oktober 2026)
4. Google. *Android Developers: App fundamentals*. https://developer.android.com/guide (diakses 20 Oktober 2026)

---

## Bagian 3: Refleksi

Menurut saya platform yang paling menarik untuk dipelajari adalah web. Saya sudah beberapa kali membuat aplikasi web dengan Laravel, jadi rasanya lebih nyambung dan tidak mulai dari nol. Web juga enak karena hasilnya langsung bisa dilihat di browser, dan kalau ada perubahan cukup refresh halaman. Selain itu, ilmu web bisa dipakai di platform lain, misalnya Electron untuk desktop atau React Native untuk mobile.

Tantangan terbesar saat setup environment menurut saya ada di instalasi dan konfigurasi tools. Git, Node.js, dan JDK harus terbaca di terminal, dan kalau PATH-nya belum benar perintahnya tidak dikenali. Versi tools juga bisa jadi masalah karena tidak semua cocok satu sama lain. Kadang saya juga hanya mengikuti langkah di tutorial tanpa benar-benar paham fungsi tiap tools.

Untuk mengatasinya, saya akan mengikuti panduan di situs resmi dan mengecek hasil instalasi dengan `git --version`, `node -v`, dan `java -version`. Kalau ada error, saya baca dulu pesan errornya, lalu cari solusinya di dokumentasi atau forum. Saya juga akan mencatat langkah-langkah yang sudah dicoba supaya kalau harus mengulang tidak bingung, dan bertanya ke dosen atau teman kalau masih buntu.
