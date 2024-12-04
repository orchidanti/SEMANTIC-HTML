Nama   : Orchidanti Izza R <br>
NIM    : 2205101024 <br>
Kelas  : 5B TIF <br>

# SEMANTIC-HTML
Latihan Praktikum 1 Semantic HTML

### 1. Penambahan Tag HTML dan Body

- **Sebelum Revisi:**
  - Struktur HTML tidak lengkap karena tidak ada tag `<html>` dan `<body>`.
  - HTML langsung dimulai dengan elemen-elemen seperti `<header>`, `<nav>`, `<section>`, dan `<footer>`, yang kurang terstruktur sesuai dengan standar HTML5.

- **Setelah Revisi:**
  - Ditambahkan tag `<html>` yang membuka seluruh dokumen HTML, yang merupakan struktur yang benar dalam HTML5.
  - Ditambahkan tag `<body>` yang membungkus semua konten yang terlihat oleh pengguna, memastikan bahwa struktur HTML sesuai dengan standar dan lebih mudah dipahami oleh browser.

### **2. Penambahan Tag `<head>`**

- **Sebelum Revisi:**
  - Tidak ada tag `<head>`. Biasanya, bagian ini berisi informasi tentang dokumen HTML, seperti metadata, judul, dan file CSS atau JavaScript eksternal.

- **Setelah Revisi:**
  - Ditambahkan tag `<head>` yang berfungsi untuk memuat elemen-elemen metadata, seperti pengaturan charset dan viewport, yang sangat penting untuk pengaturan teks dan tampilan di perangkat seluler.
  - Di dalam `<head>`, terdapat juga tag `<title>` yang memberikan nama pada halaman web yang ditampilkan di tab browser.
  - Ditambahkan `<link>` untuk memuat file CSS eksternal, yang bertujuan untuk memisahkan gaya dari konten dan memberikan kontrol yang lebih baik terhadap desain halaman.

### **3. Perbaikan Penulisan Meta Viewport**

- **Sebelum Revisi:**
  - Penulisan tag `<meta name="viewport">` salah, yaitu `devide-width`, yang seharusnya adalah `device-width`. Hal ini dapat menyebabkan halaman tidak sepenuhnya responsif pada perangkat seluler.

- **Setelah Revisi:**
  - Penulisan tag viewport diperbaiki menjadi `device-width`. Ini memastikan bahwa tampilan halaman web akan sesuai dengan lebar layar perangkat pengguna, memungkinkan desain responsif dan tampilan yang baik di berbagai ukuran layar.

### **4. Struktur Link CSS Eksternal**

- **Sebelum Revisi:**
  - Tidak ada referensi ke file CSS eksternal, yang berarti halaman web mungkin hanya mengandalkan pengaturan gaya default dari browser.

- **Setelah Revisi:**
  - Ditambahkan tag `<link rel="stylesheet" href="./assets/styles/styles.css">` di dalam `<head>`, yang merujuk ke file CSS eksternal. Ini memungkinkan halaman untuk mendapatkan gaya yang telah ditentukan dalam file `styles.css`, memisahkan presentasi (gaya) dari struktur HTML, dan meningkatkan pemeliharaan kode.

### **5. Penambahan Tag Pembuka dan Penutup HTML**

- **Sebelum Revisi:**
  - Tidak ada tag pembuka dan penutup `<html>`, yang mana meskipun tidak selalu mengganggu, bisa menyebabkan masalah kompatibilitas atau pemahaman dalam pengkodean yang lebih kompleks.

- **Setelah Revisi:**
  - Ditambahkan tag `<html lang="en">`, yang secara eksplisit menyatakan bahasa dokumen HTML adalah Bahasa Inggris (`en`). Ini bermanfaat untuk SEO dan aksesibilitas.
  - Penutupan elemen `<html>` di akhir kode, memastikan seluruh dokumen HTML terstruktur dengan benar.

### **6. Penyusunan Kode yang Lebih Rapi dan Terstruktur**

- **Sebelum Revisi:**
  - Kode HTML tidak sepenuhnya terstruktur, karena beberapa elemen penting tidak ada (seperti tag `<html>`, `<head>`, dan pengaturan `meta`).
  - Struktur halaman tampak kurang jelas dan tidak sesuai standar HTML5.

- **Setelah Revisi:**
  - Struktur kode diperbaiki dengan mengikuti standar HTML5 yang lebih baik, yang mengoptimalkan fungsionalitas dan aksesibilitas halaman.
  - Kode sekarang lebih terorganisir, dengan bagian `<head>` dan `<body>` yang jelas, serta pengaturan CSS eksternal yang memungkinkan modifikasi gaya lebih mudah.
