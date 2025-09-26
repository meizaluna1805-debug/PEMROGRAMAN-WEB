# Laporan Praktikum  
Pembuatan Website dengan Menggunakan HTML Semantic Layout

---

## Dosen Pengampu
Ir. Gede Humaswara Prathama, S.T., M.T.

## Disusun Oleh
- Ni Made Dina Ayu Purnami — 42430004  
- Ni Komang Ria Asrini — 424300  
- Meizaluna Aurelia Frakasa — 424300  
- Indriani Asten — 42430010  

## Institusi
Program Studi Teknologi Informasi  
Fakultas Teknik dan Informatika  
Universitas Pendidikan Nasional  
2025  

---

## 1. Pendahuluan
Rendang merupakan salah satu kuliner tradisional Indonesia yang berasal dari Minangkabau, Sumatera Barat.  
Hidangan ini tidak hanya terkenal karena cita rasanya yang kaya akan rempah, tetapi juga karena nilai budaya dan filosofi yang terkandung di dalamnya. Bahkan, rendang pernah dinobatkan sebagai salah satu makanan terlezat di dunia dan menjadi simbol penting dari kearifan lokal masyarakat Minangkabau.  

Keistimewaan ini menjadikan rendang sebagai topik yang menarik untuk diangkat dalam sebuah media informasi berbasis digital, yaitu website.  
Dalam era digital saat ini, website menjadi sarana yang efektif untuk menyampaikan informasi kepada masyarakat luas. Melalui pembuatan website sederhana bertema Sejarah Rendang, mahasiswa diajak untuk memadukan pemahaman tentang teknologi web dengan upaya pelestarian budaya.  

Website ini berisi informasi tentang asal-usul rendang, perjalanan sejarahnya, nilai-nilai yang terkandung di dalamnya, serta resep tradisional yang masih dijaga hingga kini. Dengan demikian, selain mengasah kemampuan teknis, praktikum ini juga mengajarkan pentingnya peran teknologi dalam mendukung pelestarian budaya bangsa.  

Pada praktiknya, pembuatan website dilakukan menggunakan HTML sebagai fondasi utama dalam membangun struktur halaman web. Elemen-elemen dasar seperti `<header>` untuk judul, `<nav>` untuk navigasi, `<main>` dan `<section>` untuk konten utama, `<article>` untuk informasi spesifik, hingga `<footer>` untuk bagian penutup, dipelajari dan diterapkan secara langsung.  

Penggunaan struktur yang rapi dan sesuai standar membuat website lebih mudah dipahami, baik oleh pengguna maupun oleh mesin pencari.  
Melalui pembelajaran ini, mahasiswa tidak hanya memahami aspek teknis dari pembuatan web, tetapi juga dilatih untuk berpikir kritis tentang bagaimana menyajikan informasi dengan baik. Harapannya, hasil dari praktikum ini tidak hanya sebatas latihan akademik, tetapi juga dapat menjadi contoh nyata bagaimana teknologi dapat dimanfaatkan untuk mengenalkan dan melestarikan warisan budaya Indonesia, khususnya rendang, kepada generasi sekarang maupun mendatang.  

---

## 2. Tujuan
1. Memberikan informasi tentang sejarah dan asal-usul rendang sebagai makanan tradisional khas Minangkabau.  
2. Menyajikan filosofi dan nilai budaya yang terkandung dalam rendang agar lebih dikenal masyarakat luas.  
3. Menampilkan resep rendang tradisional sehingga bisa dipelajari dan dipraktikkan oleh siapa saja.  
4. Menjadi media digital untuk melestarikan budaya kuliner Indonesia, khususnya rendang, agar tetap dikenal oleh generasi sekarang dan mendatang.  
5. Melatih kemampuan pembuatan website sederhana sebagai sarana belajar HTML sekaligus mengenalkan kearifan lokal melalui teknologi.  

# LAPORAN PRAKTIKUM  
**PEMBUATAN WEBSITE DENGAN MENGGUNAKAN HTML SEMANTIC LAYOUT**

**Dosen Pengampu:** Ir. Gede Humaswara Prathama, S.T., M.T.  
**Program Studi:** Teknologi Informasi — Fakultas Teknik dan Informatika  
**Universitas Pendidikan Nasional — 2025**

**Disusun Oleh:**  
- Ni Made Dina Ayu Purnami — 42430004  
- Ni Komang Ria Asrini — 424300..  
- Meizaluna Aurelia Frakasa — 424300..  
- Indriani Asten — 42430010


## 2. Pembahasan 

### 2.1 Struktur Dasar Dokumen
<img src="DOCTYPE.png" width="450"> <br>
- `<!DOCTYPE html>`  
  Menandakan dokumen menggunakan standar HTML5 sehingga browser merender dalam mode standar.

- `<html lang="id">`  
  Elemen akar dokumen. Atribut `lang="id"` memberi tahu mesin pencari dan pembaca layar bahwa bahasa utama adalah Bahasa Indonesia.

- `<head>`  
  Berisi metadata:  
  - `<meta charset="UTF-8">` → set encoding (UTF-8) untuk dukungan karakter.  
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` → memastikan halaman responsif pada perangkat mobile.  
  - `<title>` → judul yang muncul di tab browser.

- `<body>`  
  Semua konten visual ditaruh di dalam `<body>`.

---

### 2.2 Header
<img src="HEADER.png" width="450"> <br>
- Tag yang digunakan: `<header>`, `<h1>`, `<p>`.  
- Fungsi: menampilkan identitas situs (judul utama) dan tagline. `<h1>` hanya satu per halaman dan menjadi judul utama yang penting untuk struktur dokumen dan SEO.

---

### 2.3 Navigasi
<img src="NAVIGASI.png" width="450"> <br>
- Tag: `<nav>`, `<ul>`, `<li>`, `<a href="#...">`.  
- Fungsi: menyediakan tautan internal (fragment link) ke section lain (`#home`, `#sejarah`, `#resep`). Baik untuk single-page layout; teks tautan harus deskriptif untuk aksesibilitas dan SEO.

---

### 2.4 Section: Beranda (`<section id="home">`)
<img src="HOME.png" width="450"> <br>
- Struktur:
  - `<h2>` sebagai judul section.
  - Dua `<article>`:
    1. **Apa itu Rendang?** — `<h3>` + paragraf (`<p>`) yang menjelaskan definisi dan karakter rasa.  
    2. **Keunikan Rendang** — `<h3>` + paragraf yang menjelaskan daya tahan dan fungsi rempah; disertai gambar:
       - `<img src="Rendang.jpg" width="300" alt="Rendang Tradisional Minangkabau">`
- Catatan:
  - `alt` harus deskriptif untuk pembaca layar.
  - `width` di HTML bersifat presentasional; pertimbangkan CSS (`max-width:100%`) untuk responsivitas nanti.
  - Pertimbangkan penggunaan `<figure>` dan `<figcaption>` bila ada keterangan gambar.

---

### 2.5 Section: Sejarah (`<section id="sejarah">`)
<img src="SEJARAH.png" width="450"> <br>
- Struktur:
  - `<h2>` judul section.
  - `<article>` pertama: narasi asal-usul (paragraf) + gambar (`<img src="Rendang2.png" ...>`).
  - `<article>` kedua: **Timeline Sejarah** berupa tabel:
    - `<table>` dengan:
      - `<caption>`: judul tabel — membantu konteks dan aksesibilitas.
      - `<thead>`: baris header kolom (`<th>Tahun</th>`, `<th>Peristiwa</th>`). Tambahkan `scope="col"` pada `<th>` untuk pembaca layar.
      - `<tbody>`: baris data (`<tr>`) berisi `<td>` (tahun & peristiwa, contoh: Abad ke-16, 1800an, 2011, 2018).
- Catatan:
  - Gunakan nama file gambar tanpa spasi (mis. `rendang2.png`) agar url/hosting lebih konsisten.
  - Tabel cenderung tidak responsif: untuk mobile, pertimbangkan teknik seperti overflow-x (horizontal scroll), konversi ke list untuk layar sempit, atau responsif CSS table.

---

### 2.6 Section: Resep (`<section id="resep">`)
<img src="RESEP.png" width="450"> <br>
- Struktur:
  - `<h2>` judul section.
  - `<article>` bahan:
    - `<h3>Bahan-bahan</h3>` → dua subbagian:
      - `<h4>Bahan Utama:</h4>` + `<ul>` berisi `<li>` untuk bahan utama.
      - `<h4>Bumbu Halus:</h4>` + `<ul>` berisi `<li>` untuk bumbu.
  - `<article>` cara memasak:
    - `<h3>Cara Memasak</h3>` + `<ol>` berisi langkah (`<li>`), karena urutan penting.
    - Gambar proses: `<img src="Masakan.jpg" width="300" alt="Proses memasak rendang">`.
  - `<aside>` di dalam section: form komentar (input nama, textarea komentar, tombol submit).
- Formulir (catatan teknis):
  - Saat ini `form` tidak memiliki atribut `action`/`method` sehingga bersifat statis. Untuk menyimpan atau memproses komentar, perlu backend atau layanan pihak ketiga (Formspree, Netlify Forms) atau set `action` ke endpoint server.
  - Pastikan `label for="id"` terhubung dengan `input id="..."` untuk aksesibilitas.
  - Validasi: tambahkan `required` di input yang wajib, dan lakukan sanitasi/validasi di server untuk keamanan.

---

### 2.8 Form Komentar (Section Resep)

<img src="FORM.png" width="450"> <br>

Pada bagian resep terdapat sebuah form sederhana di dalam `<aside>`. Form ini terdiri dari input teks untuk nama, textarea untuk komentar, dan tombol submit. Label dihubungkan dengan input melalui atribut `for` dan `id`, sehingga mendukung aksesibilitas.  

Fungsinya adalah memberi ruang interaksi bagi pengguna untuk menuliskan pengalaman atau pendapat mereka. Namun, karena belum memiliki atribut `action` dan `method`, form ini bersifat statis dan tidak mengirim data ke server. Agar benar-benar berfungsi, perlu ditambahkan pengaturan backend atau layanan pihak ketiga serta validasi input.  


---

### 2.9 Aside (sidebar informasi tambahan)
<img src="ASIDE.png" width="450"> <br>
- Elemen: `<aside>` di luar `<main>` berisi fakta singkat dan daftar jenis rendang (`<ul>`).  
- Fungsi: menampung konten sekunder yang relevan tapi tidak bagian inti alur baca.

---

### 3 Footer
<img src="FOOTER.png" width="450"> <br>
- Elemen: `<footer>` berisi kontak dan hak cipta.  
  - Gunakan `<a href="mailto:...">` untuk email dan `<a href="tel:...">` untuk nomor telepon agar klik-to-action berfungsi pada perangkat mobile.
  - Gunakan `&copy;` untuk simbol hak cipta.

---
