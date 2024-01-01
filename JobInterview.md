## 1.1 Latar Belakang

Absensi adalah metode untuk mencatat berapa banyak mahasiswa tidak hadir disetiap mata kuliah. Absensi online ini adalah pencatatan kehadiran dengan sistem cloud yang terhubung dengan database secara realtime, ini akan menyimpan data absensi secara otomatis tanpa perlu melakukan rekapitulasi. Selain itu, data absensi yang telah masuk dapat diakses di mana pun dan kapan pun, dengan catatan harus tetap terhubung dengan jaringan internet. Kegunaan absensi ini terjadi pada pihak
pelajar dan pihak pengada proses belajar mengajar. Salah satu kegunaan absensi ini kepada pihak pelajar antara lain adalah dalam perhitungan kemungkinan pelajar untuk mengikuti ujian dan salah satu kegunaan informasi absensi ini kepada pihak pengada kegiatan belajar mengajar antara lain untuk melakukan evaluasi kepada kepuasaan pelajar terhadap suatu mata pelajaran dan pembuatan tolak ukur ke depan guna pemberian ilmu yang lebih baik. Pengambilan data absensi ini sendiri dilakukan secara manual memiliki banyak kekurangan, seperti data yang tidak valid ketika data yang masuk salah. Kekurangan lain dari pengambilan data secara manual adalah hilang atau rusaknya data yang ada. Kekurangan lain adalah kurangnya efisiensi dan efektifitas pada pengolahan data.


## 1.2. Deksripsi Teknologi Informasi
Roll Call adalah aplikasi yang bisa digunakan untuk mahasiswa dan dosen agar memudahkan absen secara jarak jauh, dengan ditambah fitur bisa mengirim permohonan izin jika memiliki halangan dan dapat mencatat kehadiran mahasiswa. Absen ini berfungsi untuk menggantikan absen secara manual yang biasanya dilakukan dengan mengisi daftar hadir dengan tulisan tangan, tentunya memudahkan proses absensi, dan meningkatkan efisiensi waktu.


## 1.3. Branding

Merk : Roll Call

Tagline : Absen mudah, simpel dan sederhana

Campaign : Membuat aplikasi sederhana dimana penggunanya dapat dengan mudah mengisi absensi secara online.

Target user :
•  Semua usia
•	Orang yang menyukai absen cepat mudah dan simpel
•	Seseorang yang ingin mendisiplinkan dirinya sendiri 
•	Absen dapat dilakukan dan diakses darimana saja hanya dengan menggunakan smartphone dan internet
•  Seorang Dosen atau guru yang menginginkan absen dengan cara cepat




User experience theme:
•	Mudah
•	Simpel
•	Sederhana
•	Bermanfaat
•  Warna : Hitam dan terang lilac, green dan tosca


   

## 2. User Story

sebagai | saya ingin bisa | sehingga | prioritas
---|---|---|---
Admin | Mengakses data user  | Bisa update data user dan menghapus data user | ⭐⭐⭐⭐⭐
Admin | Mengakses jumlah user  | Bisa melihat detail jumlah pengguna dan mengubah status pengguna | ⭐⭐⭐⭐⭐
Admin | Mengatur kebutuhan pengguna  | Mengubah biodata atau memberi akses menambah jadwal  | ⭐⭐⭐⭐⭐
Admin | Mengatur waktu | Kebijakan ketepatan waktu, keterlambatan, dan absensi yang disesuaikan dengan dosen |  ⭐⭐⭐⭐⭐
Pengguna | Edit Jadwal  | Bisa merubah jadwal, menambah, dan menghapus | ⭐⭐⭐⭐⭐
Pengguna | Mengakses siapa saja yang absen | Bisa mengetahui yang absen pada mata kuliah tertentu | ⭐⭐⭐⭐⭐
Pengguna | Melihat jumlah absen | Mengetahui seberapa banyak pengguna melewatkan kelas  | ⭐⭐⭐⭐
Pengguna | Melihat detail biodata | Bisa meliahat biodata lengkap pengguna  | ⭐⭐⭐⭐
Pengguna | Mengirim permohonan izin | Dapat mengirim permohonan izin kepada dosen  | ⭐⭐⭐⭐
Pengguna | Memilih jadwal kuliah | Bisa menyesuaikan dengan bulan dan hari yang akan di klik  | ⭐⭐⭐
Pengguna | Memrubah data | Bisa merubah data jika terjadi perubahan  | ⭐⭐⭐


## 3. Struktur Data

<img width="497" alt="Screenshot 2023-12-30 175028" src="https://github.com/aryantiina/aryantiina/assets/145460588/8a0e8558-9ef3-4f49-b196-925be2abd251">

## 4. Arsitektur Sistem
<img width="464" alt="Screenshot 2023-12-26 032424" src="https://github.com/aryantiina/aryantiina/assets/145460588/f8f2be82-9b2b-4d35-bbf6-0020264300b7">

## 5. Teknologi, Library, dan Framework
- UI/UX Design : Canva
- Web Server   : Laravel
- Text Editor  : Vs Code 
- Database     : MySQL

# UI/UX Design : Canva
UI/UX adalah singkatan dari "User Interface" dan "User Experience":

UI (User Interface): Merujuk pada tampilan grafis dari suatu aplikasi atau situs web. Ini mencakup semua elemen visual yang dapat dilihat oleh pengguna, seperti tombol, ikon, gambar, teks, warna, tata letak, dan lainnya. Tujuannya adalah untuk menciptakan antarmuka yang intuitif, menarik, dan mudah digunakan oleh pengguna.

UX (User Experience): Mengacu pada keseluruhan pengalaman pengguna saat menggunakan produk atau layanan. Ini mencakup bagaimana pengguna merasa saat berinteraksi dengan antarmuka, bagaimana mereka menavigasi melalui fitur-fitur, dan apakah mereka merasa puas dengan hasil yang diperoleh. Tujuannya adalah untuk memastikan bahwa pengguna memiliki pengalaman yang menyenangkan, efisien, dan memuaskan saat menggunakan produk atau layanan.

Kedua aspek ini saling terkait dan penting dalam desain produk digital. Seorang desainer UI/UX bertanggung jawab untuk menciptakan antarmuka yang baik dan pengalaman pengguna yang positif untuk memastikan produk atau layanan dapat digunakan dengan mudah dan efektif oleh pengguna.

Canva adalah sebuah platform desain grafis online yang memungkinkan pengguna untuk membuat berbagai jenis desain, mulai dari poster, presentasi, media sosial, hingga grafik web dengan mudah dan cepat. Diluncurkan pertama kali pada tahun 2012 oleh Melanie Perkins, Cliff Obrecht, dan Cameron Adams, Canva telah menjadi salah satu alat desain paling populer di dunia dengan jutaan pengguna aktif.

# Web Server   : Laravel
web server adalah sebuah perangkat keras atau perangkat lunak yang menyimpan konten web seperti halaman web, gambar, video, atau konten lainnya, dan mengirimkannya ke pengguna yang mengaksesnya melalui Internet. Dengan kata lain, web server berfungsi sebagai "tuan rumah" yang menyimpan dan menyajikan halaman web kepada pengguna atau klien.

Laravel adalah salah satu framework aplikasi web berbasis PHP yang paling populer dan paling banyak digunakan di dunia. Dikembangkan pertama kali oleh Taylor Otwell pada tahun 2011, Laravel telah menjadi pilihan utama bagi banyak pengembang web karena kemudahan penggunaannya, struktur yang efisien, dan kumpulan fitur-fitur canggih yang disediakannya.

# Text Editor  : Vs Code 
Text editor adalah perangkat lunak yang digunakan untuk membuat, mengedit, dan memformat teks. Text editor memungkinkan pengguna untuk menulis kode, dokumen, atau teks biasa.

VS Code, atau Visual Studio Code, adalah editor kode sumber yang dikembangkan oleh Microsoft. VS Code dirancang untuk menjadi ringan, cepat, dan mendukung berbagai bahasa pemrograman dan kerangka kerja.

# Database     : MySQL
Database adalah kumpulan data yang disimpan secara terstruktur dan dapat diakses serta dikelola dengan menggunakan perangkat lunak tertentu. Dalam konteks teknologi informasi, database seringkali digunakan untuk menyimpan informasi yang dapat diolah dan dikelola dengan mudah. Database memungkinkan pengguna untuk menyimpan, mengambil, memperbarui, dan mengelola data dengan efisien.

MySQL adalah sebuah sistem manajemen basis data relasional (RDBMS) yang populer dan open-source. Ini berarti bahwa MySQL dapat digunakan, dimodifikasi, dan didistribusikan secara gratis. MySQL dikembangkan, didukung, dan didistribusikan oleh perusahaan Oracle.

## 6. Desain User Experience dan User Interface

Landing page

<img width="309" alt="Screenshot 2023-12-26 022110" src="https://github.com/aryantiina/aryantiina/assets/145460588/a3483c09-dbfe-46ed-baca-882db9bd93e3">

Details Page

<img width="309" alt="Screenshot 2023-12-26 075102" src="https://github.com/aryantiina/aryantiina/assets/145460588/4e74aeb9-1649-4022-8d34-e390b47a0e5f">

Succsess Page

<img width="307" alt="Screenshot 2023-12-26 022603" src="https://github.com/aryantiina/aryantiina/assets/145460588/3ebf2561-16fb-4fb4-af61-0ed0e860d114">

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Mesin komputasi (hardware) dan sistem operasi (operating system) adalah dua komponen kunci dalam produk teknologi informasi. Keduanya bekerja bersama-sama untuk memastikan bahwa perangkat lunak (software) dapat berjalan dengan efisien dan sesuai dengan kebutuhan pengguna. Berikut adalah peran masing-masing dalam produk teknologi informasi:

1. Mesin Komputasi (Hardware):

   -Pengolahan Data: Mesin komputasi bertanggung jawab untuk memproses data dan menjalankan instruksi yang diberikan oleh 
    perangkat lunak.
   -Penyimpanan Data: Hardware menyediakan kapasitas penyimpanan seperti hard drive, SSD, dan RAM untuk menyimpan data dan 
    program yang sedang berjalan.
   -Komunikasi: Hardware juga memungkinkan komunikasi antara perangkat, baik itu melalui jaringan kabel maupun nirkabel.
   -Interaksi Pengguna: Perangkat keras seperti monitor, keyboard, dan mouse memungkinkan pengguna untuk berinteraksi 
    dengan sistem.

2. Sistem Operasi (Operating System):

   -Manajemen Sumber Daya: Sistem operasi mengatur dan mengalokasikan sumber daya komputasi, seperti CPU, memori, dan 
    perangkat keras lainnya, untuk memastikan bahwa berbagai tugas dapat dijalankan dengan efisien.
   -Antarmuka Pengguna: Sistem operasi menyediakan antarmuka yang memungkinkan pengguna untuk berinteraksi dengan perangkat 
    keras dan perangkat lunak. Ini bisa berupa antarmuka teks, grafis, atau bahkan suara.
   -Manajemen File: Sistem operasi mengatur bagaimana data disimpan, diakses, dan dikelola pada perangkat penyimpanan.
   -Keamanan: Melalui sistem hak akses dan mekanisme keamanan lainnya, sistem operasi memastikan bahwa data dan sumber daya 
    sistem dilindungi dari akses yang tidak sah.
   -Manajemen Proses: Sistem operasi mengatur eksekusi program dan tugas yang berjalan pada komputer, serta mengelola 
    komunikasi antara proses yang berbeda.

Dengan bekerja bersama-sama, mesin komputasi dan sistem operasi memastikan bahwa produk teknologi informasi dapat berfungsi dengan optimal, memberikan kinerja yang cepat, handal, dan aman bagi pengguna.

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Algoritma, struktur data, dan bahasa pemrograman adalah komponen kunci dalam pengembangan produk teknologi informasi. Setiap elemen memiliki peran penting dalam memastikan bahwa solusi teknologi informasi yang dibuat efisien, efektif, dan dapat diandalkan. Berikut adalah peran masing-masing elemen tersebut:

1. Algoritma:

   • Deskripsi: Algoritma adalah urutan instruksi langkah demi langkah untuk menyelesaikan masalah atau melakukan tugas 
     tertentu.
   • Peran:
      • Menentukan bagaimana data diproses.
      • Menyediakan struktur logis untuk implementasi.
      • Memastikan efisiensi dan kinerja yang optimal dari solusi.

2. Struktur Data:

   • Deskripsi: Struktur data adalah cara data disimpan, diorganisir, dan diakses dalam memori komputer.
   • Peran:
      • Mempengaruhi efisiensi operasi dan operasi data.
      • Mendukung kebutuhan penyimpanan dan akses data.
      • Memfasilitasi operasi seperti pencarian, pengurutan, dan manipulasi data.

3. Bahasa Pemrograman:

   • Deskripsi: Bahasa pemrograman adalah bahasa formal yang digunakan untuk menulis instruksi yang dapat dieksekusi oleh 
     komputer.
   • Peran:
      • Menyediakan alat untuk mengimplementasikan algoritma.
      • Menyediakan struktur dan sintaks untuk mendefinisikan dan mengoperasikan struktur data.
      • Memungkinkan pengembang untuk membangun, menguji, dan memelihara solusi teknologi informasi.
      • Memfasilitasi kolaborasi dan standarisasi dalam pengembangan software.
   
Dalam konteks pengembangan produk teknologi informasi, ketiga elemen tersebut bekerja secara sinergis. Sebagai contoh, ketika mengembangkan sebuah aplikasi web e-commerce, seorang pengembang mungkin menggunakan algoritma untuk menentukan logika bisnis (seperti proses checkout atau rekomendasi produk), memilih struktur data yang tepat untuk menyimpan informasi pelanggan dan produk, dan menggunakan bahasa pemrograman tertentu (seperti Python, Java, atau JavaScript) untuk mengimplementasikan solusi secara efektif.

Dengan memahami dan memanfaatkan algoritma, struktur data, dan bahasa pemrograman dengan benar, pengembang dapat menciptakan solusi teknologi informasi yang handal, efisien, dan sesuai dengan kebutuhan bisnis atau pengguna.


## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Software Development Life Cycle (SDLC) atau siklus hidup pengembangan perangkat lunak adalah serangkaian tahapan yang digunakan untuk mengembangkan perangkat lunak dari awal hingga selesai. Metode SDLC memastikan bahwa perangkat lunak yang dikembangkan memenuhi kebutuhan bisnis atau pengguna dan diproduksi dengan standar kualitas yang tinggi. Berikut adalah peran metode SDLC dalam pengembangan produk teknologi informasi:

1. Pengidentifikasian Kebutuhan:
   -Tahap awal dari SDLC adalah mengidentifikasi kebutuhan pengguna dan bisnis. Ini membantu tim pengembangan memahami apa 
    yang diharapkan dari perangkat lunak dan bagaimana perangkat lunak tersebut akan digunakan.

2. Perencanaan:
   -Dalam tahap ini, perencanaan proyek dilakukan, termasuk estimasi biaya, waktu, dan sumber daya yang dibutuhkan. Rencana 
    ini mencakup jadwal pengembangan, alokasi sumber daya, dan risiko yang mungkin muncul.

3. Desain:
   -Desain perangkat lunak dibuat berdasarkan kebutuhan yang telah diidentifikasi. Ini mencakup desain arsitektur sistem, 
    desain antarmuka pengguna, dan spesifikasi teknis lainnya.

4. Pembangunan (Pengkodean):
   -Dalam tahap ini, perangkat lunak dikodekan berdasarkan desain yang telah dibuat. Kode sumber diterjemahkan menjadi 
    program komputer yang dapat dijalankan.

5. Pengujian:
   -Setelah perangkat lunak dibangun, tahap pengujian dilakukan untuk memastikan bahwa perangkat lunak berfungsi sesuai 
    dengan kebutuhan dan tidak ada bug atau kesalahan yang signifikan.

6. Implementasi:
   -Setelah berhasil diuji, perangkat lunak siap untuk diimplementasikan. Ini melibatkan penerapan perangkat lunak ke dalam 
    lingkungan produksi dan pelatihan pengguna jika diperlukan.

7. Pemeliharaan:
   -Setelah implementasi, perangkat lunak mungkin memerlukan pemeliharaan untuk memperbaiki bug, menambah fitur baru, atau 
    melakukan penyesuaian lainnya berdasarkan umpan balik pengguna.

Metode SDLC membantu dalam memastikan bahwa perangkat lunak dikembangkan dengan pendekatan yang terstruktur dan terorganisir. Hal ini meminimalkan risiko kesalahan, memastikan kualitas produk, dan memastikan bahwa perangkat lunak memenuhi ekspektasi pengguna dan bisnis. Dengan demikian, metode SDLC berperan penting dalam menciptakan produk teknologi informasi yang berkualitas dan dapat diandalkan.

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Database—sistem yang mengatur dan menyimpan data-membentuk fondasi dari setiap strategi analitik. Mendapatkan struktur dan arsitektur dasar sistem database Anda dengan benar dapat membedakan antara struktur yang didukung dengan baik yang memberikan nilai yang baik dan yang runtuh karena bebannya sendiri.

Database biasanya berperan pada tahap kedua dari pipeline data: pemrosesan data (tahap "mempersiapkan dan menyimpan"). Aplikasi dan platform analitik menggunakan informasi yang terkandung dalam database untuk membantu organisasi memahami masa lalu dan memprediksi masa depan.

Bagi organisasi yang memilih perangkat lunak dan sistem basis data, sangatlah penting untuk memilih teknologi yang bekerja secara efektif untuk masalah yang sedang dipecahkan.

Memiliki infrastruktur yang tepat - termasuk berbagai jenis komputasi (CPU, FPGA, dan akselerator), penyimpanan, memori, jaringan, pustaka perangkat lunak, dan pengoptimalan Java - dapat mendorong peningkatan performa database dan pengelolaan database yang lebih mudah.
