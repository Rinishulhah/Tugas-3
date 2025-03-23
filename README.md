# Tugas 3 - Web Client Development 
Proyek ini mencakup pembuatan aplikasi web sederhana yang menampilkan antarmuka bertema olahraga

## Contoh
![Image](https://github.com/user-attachments/assets/644cd3d9-ca77-4ec8-8ebb-2814c0aaf2f6)

### Fitur
- Navigasi Sederhana: Terdiri dari menu Home, About, dan Training.
- Hero Section: Menampilkan judul utama, deskripsi, dan tombol call-to-action yang mengarah ke WhatsApp.
- Ilustrasi Menarik: Gambar dekoratif untuk mempercantik tampilan dan meningkatkan pengalaman pengguna.
- Desain Responsif: Tampilan menyesuaikan dengan berbagai ukuran layar.

#### Teknologi yang Digunakan
- HTML
- CSS
- Google Fonts 

### Peran HTML , CSS, dan Google Fonts dalam Proyek Ini
#### 1. HTML (HyperText Markup Language)
HTML digunakan untuk membuat struktur dasar halaman web. Dalam proyek ini, HTML berfungsi untuk:
- Membuat struktur halaman web seperti header, main content, dan footer.
- Menampilkan elemen-elemen penting seperti judul, paragraf, gambar, tombol, dan navigasi.
- Menautkan halaman dan sumber daya eksternal seperti file CSS dan Google Fonts.
  
#### Elemen Penting dalam HTML Ini:
- <nav>: Menampilkan navigasi dengan menu Home, About, dan Training.
- <main>: Bagian utama yang berisi judul, deskripsi layanan, tombol WhatsApp, dan ilustrasi.
- <footer>: Menyediakan kontak melalui email.
- <button>: Tombol yang mengarah ke WhatsApp untuk memulai sesi workout.
  
#### 2. CSS (Cascading Style Sheets)
CSS digunakan untuk mengatur tampilan dan gaya dari elemen-elemen HTML. Dalam proyek ini, CSS bertanggung jawab untuk:
- Membuat tampilan lebih menarik dengan font khusus dari Google Fonts.
- Menyesuaikan warna, ukuran, dan tata letak agar lebih user-friendly.
- Membuat halaman lebih responsif agar tampilannya tetap baik di berbagai perangkat.
  
Menata elemen-elemen seperti:
- Header dan navigasi dengan tampilan yang rapi.
- Teks utama agar lebih menarik dan mudah dibaca.
- Gambar dan ilustrasi untuk mendukung informasi yang diberikan.
- Tombol WhatsApp dengan ikon dan warna yang sesuai.
  
  #### Cara CSS Bekerja di Proyek Ini:
- File CSS terhubung melalui
   <link rel="stylesheet" href="./style.css">.
- Font dari Google Fonts digunakan untuk memberikan tampilan teks yang lebih profesional.
- Gaya elemen seperti h1, p, button diatur untuk meningkatkan estetika dan keterbacaan.

#### 3. Google Fonts di Proyek ini: 
Google Fonts digunakan dalam proyek ini untuk memberikan tampilan teks yang lebih menarik dan profesional. Font yang digunakan dalam kode ini adalah Mulish dan Open Sans yang diimpor melalui tag berikut:
<link href="https://fonts.googleapis.com/css2?family=Mulish:wght@400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">

#### Mengapa Menggunakan Google Fonts?
1. Meningkatkan Estetika Teks
- Font default pada browser sering kali terlihat standar dan kurang menarik.
- Dengan Google Fonts, kita bisa memilih font yang lebih stylish dan sesuai dengan tema desain.
2. Konsistensi Tampilan di Semua Perangkat
- Google Fonts memastikan font yang digunakan tetap konsisten, baik di komputer, tablet, maupun smartphone.
3. Mudah Digunakan 
- Cukup menambahkan link ke dalam <head> HTML, lalu memanggilnya di CSS, misalnya:
body {
  font-family: 'Mulish', sans-serif;
}
4. Optimasi Performa
- Font dari Google Fonts telah dioptimalkan agar bisa dimuat dengan cepat, sehingga tidak memperlambat loading website.
  
#### Bagaimana Google Fonts Bekerja di Proyek Ini?
- Font "Mulish" dan "Open Sans" digunakan untuk teks utama agar tampilan lebih modern dan mudah dibaca.
- Pengaturan bobot font (400 dan 700) memungkinkan kita menggunakan teks dengan ketebalan yang berbeda, misalnya:
font-weight: 400; → Teks normal
font-weight: 700; → Teks tebal (bold)

### Input dan Output dalam Kode HTML
#### 1. Input (Masukan dari Pengguna)
Input dalam halaman ini adalah interaksi yang bisa dilakukan pengguna, yaitu:
- Klik pada menu navigasi: Home, About, dan Training.
- Klik pada tombol "Start now": Mengarahkan pengguna ke WhatsApp untuk memulai sesi latihan.
- Klik pada logo "workoutaja": Biasanya mengarah ke halaman utama.
- Klik pada email di footer: Membuka aplikasi email untuk mengirim pesan ke WorkoutAja.
  
#### 2. Output (Tampilan yang Dihasilkan)
Setelah halaman ini dimuat, output yang dihasilkan adalah:
- Judul utama: "WORKOUTS MADE EXCLUSIVE FOR YOU!" dengan desain menarik.
- Deskripsi singkat: Tentang layanan workout yang ditawarkan.
- Tombol interaktif "Start now": Dengan ikon WhatsApp untuk kemudahan akses.
- Ilustrasi wanita berolahraga: Sebagai elemen visual utama.
- Navigasi sederhana: Memungkinkan pengguna berpindah ke halaman lain.
- Footer dengan kontak: Menampilkan email untuk menghubungi WorkoutAja.
  
#### 3. Proses (Bagaimana Input Berubah Menjadi Output)
Ketika pengguna membuka halaman
1. HTML dan CSS akan dirender oleh browser untuk menampilkan tampilan website.
Saat pengguna mengklik navigasi
2. Halaman akan mengarahkan ke bagian atau halaman terkait.
Saat pengguna mengklik tombol "Start now"
3. Akan membuka WhatsApp dengan link yang dituju.
Saat pengguna mengklik email di footer
4. Akan membuka aplikasi email default pengguna.

#### Cara Menggunakan Google Fonts dalam CSS
1. Import Langsung di HTML
Tambahkan tag <link> di bagian <head>:
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;700&display=swap" rel="stylesheet">

2. Gunakan dalam CSS
Setelah diimpor, font bisa digunakan dalam CSS:
body {
  font-family: 'Open Sans', sans-serif;
}

3. Menggunakan @import dalam CSS
Alternatifnya, bisa juga dengan @import di dalam file CSS:
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;700&display=swap');
body {
  font-family: 'Open Sans', sans-serif;
}
