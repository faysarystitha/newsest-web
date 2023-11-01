# Newsest 📃
Sebuah website yang menyatukan dan menampilkan berita terkini dari portal-portal berita di Indonesia.

## Features ✨

- Menampilkan berita terkini secara real-time dari portal-portal berita Indonesia
- Di beberapa portal berita juga menampilkan berita secara kategori
- Terdapat embed link di setiap berita yang mengarahkan ke website portal berita aslinya untuk membaca berita lebih lengkap
- Tampilan bahwa pengguna dapat menyukai maupun menyimpan berita

## Development 👩🏻‍💻
Newsest dibangun dengan menggunakan HTML, CSS, serta bahasa pemrograman JavaScript. HTML untuk membangun kerangka websitenya, CSS untuk styling tampilan, dan JavaScript untuk proses memanggil dan mengolah data untuk ditampilkan. Adapun data beritanya berasal dari [Berita Indonesia API](https://github.com/satyawikananda/berita-indo-api). Beberapa icons yang berasal dari plugin Figma juga dipakai dalam website ini.

## How to Use❓
- Pastikan browser Anda menyalakan Cross-Origin Resource Sharing (CORS) agar pemanggilan data dari API berjalan lancar.
- Pastikan juga Anda memiliki jaringan internet.
- Buka website Newsest melalui [link ini](https://faysarystitha.github.io/newsest-web/).
- Jika website berhasil terbuka, Anda bisa melihat bagian navbar terdapat list dari portal berita Indonesia. Navbar ini akan mengarahkan ke bagian tampilan berita terkini sesuai dengan nama portal beritanya.
- Pada bagian atas navbar sebelah kanan, terdapat ikon profil yang menggambarkan sebuah akun dari pengguna. Ketika ikonnya di-hover, maka akan tertampilkan bagian nama akun, berita yang disukai, dan berita yang disimpan oleh pengguna.
- Terkhusus untuk portal berita Tribun News dan Zetizen JawaPos News, berita terkini ditampilkan dengan cara dikategorikan karena API tidak menyediakan berita terkini secara keseluruhan.