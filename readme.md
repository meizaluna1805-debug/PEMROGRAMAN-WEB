###  Laporan Praktikum
**MEMBANGUN HALAMAN WEB CURRICULUM VITAE DENGAN HTML DAN CSS**

---

###  Dosen Pengampu
Ir. Gede Humaswara Prathama, S.T., M.T.

###  Disusun Oleh
- Meizaluna Aurelia Frakasa — 42430045  

###  Institusi
Program Studi Teknologi Informasi  
Fakultas Teknik dan Informatika  
Universitas Pendidikan Nasional  
2025  

# Penjelasan Struktur HTML – Curriculum Vitae

## Deklarasi & Head
<img src="1.png"  width="350">

- `<!DOCTYPE html>` → menentukan dokumen sebagai HTML5.  
- `<html lang="en">` → bahasa utama halaman adalah Inggris.  
- `<meta charset="UTF-8">` → mendukung karakter internasional.  
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` → membuat halaman responsif di layar mobile.  
- `<title>` → judul halaman di tab browser.  
- `<link rel="stylesheet" href="style.css">` → menghubungkan file CSS eksternal.  

---

## Header
<img src="2.png"  width="350">

- `<header>` berisi nama dan profesi.  
- `<h1>` untuk nama utama → teks terbesar.  
- `<p>` untuk deskripsi singkat profesi (Web Developer | Graphic Designer).  

---

## Navigasi (Menu)
<img src="3.png"  width="350">

- `<nav>` berisi daftar tautan `<ul> <li> <a>`.  
- Terdapat 3 menu: **Biodata, Pendidikan, Skills**.  
- Link memakai anchor `href="#id"` untuk menuju ke bagian terkait di halaman.  

---

## Section Biodata
<img src="4.png"  width="350">

- `<section id="biodata">` → menampung informasi pribadi.  
- `<h2>` sebagai judul sub-bagian.  
- Isi berupa detail biodata: nama, alamat, telepon, email.  

---

## Section Pendidikan
<img src="5.png"  width="350">

- `<section id="pendidikan">` dengan judul `<h2>`.  
- Menggunakan `<ul>` untuk daftar jenjang sekolah hingga universitas.  

---

## Section Skills
<img src="6.png"  width="200">

- `<section id="skills">` dengan judul `<h2>`.  
- `<ul>` berisi daftar kemampuan: HTML, CSS, JavaScript, Photoshop, Illustrator.  

---

## Footer (Bagian Bawah)
<img src="7.png"  width="700">

- `<footer>` berisi teks dan link sosial media.  
- Tautan menuju Instagram dan TikTok.  
- Ditulis dalam satu paragraf agar ringkas: “Ikuti saya di social media: Instagram, TikTok”.  


# Penjelasan CSS

---

**Global Styling – Body**

<img src="8.png"  width="250">

- Selector body → menarget seluruh halaman.  
- Mengatur font dasar: Arial, fallback ke sans-serif.  
- Semua teks otomatis pakai font ini.  

---

**Header Sederhana**  

<img src="9.png"  width="250">

- background-color: Pink muda.  
- padding: 20px ruang dalam.  
- text-align: Isi header rata tengah.  
- Header jadi area pembuka yang rapi.  

---

**Navigasi – Daftar Utama**  

<img src="10.png"  width="200">

- Hilangkan bullet default.  
- Hapus padding bawaan.  
- Semua item rata tengah.  

---

**Navigasi – Item** 

<img src="11.png"  width="200"> 

- Item tampil berjejer horizontal.  
- Jarak antar item: 20px.  

---

**Navigasi – Link Dasar**  

<img src="12.png"  width="200"> 

- Link tanpa garis bawah.  
- Warna teks pink gelap.  

---

**Hover Link Umum**  

<img src="13.png"  width="250"> 

- Saat mouse melayang → link diberi garis bawah.  

---

**Konten Section (Box Model Dasar)**  

<img src="14.png"  width="250"> 

- Spasi luar 20px atas-bawah.  
- Garis tipis pink.  
- Ruang dalam 15px.  
- Bayangan lembut.  

---

**Footer Sederhana**  

<img src="15.png"  width="250"> 

- Latar belakang pink muda.  
- Isi footer rata tengah.  

---

**Universal Reset**  

<img src="16.png"  width="250"> 

- Ukuran elemen lebih mudah dikontrol (padding & border ikut dihitung).  

---

**Body Versi Lengkap**  

<img src="17.png"  width="250"> 

- Maksimal lebar halaman: 700px.  
- Konten di tengah (margin: 0 auto).  
- Background pink sangat muda.  

---

**Main Content**  

<img src="18.png"  width="150"> 

- Ruang samping dalam 15px → teks tidak menempel ke tepi.  

---

**Header Lengkap**  

<img src="19.png"  width="200"> 

- Tambahan border tebal 3px & radius 10px.  
- Margin bawah 30px.  
- Header jadi lebih elegan dengan bingkai melengkung.  

---

**Judul Utama**  

<img src="20.png"  width="200"> 

- ID #judul-utama → spesifik.  
- Warna teks gelap & tanpa margin bawaan.  

---

**Navigasi Box**

<img src="21.png"  width="200"> 

- Menu diberi kotak border + background pink.  
- Jarak bawah 25px.  

---

**Link Navigasi Versi Tombol** 

<img src="22.png"  width="200"> 

- Tambah padding supaya area klik lebih luas.  
- Border transparan → saat hover tidak menggeser layout.  
- Sudut membulat, tampil seperti tombol.  

---

**Kotak Informasi**  

<img src="23.png"  width="200"> 

- Kotak responsif (maks 650px).  
- Latar putih + border pink.  
- Pusat halaman dengan margin auto.  

---

**Penanda Section**  

<img src="24.png"  width="200"> 

- Setiap bagian punya garis kiri dengan warna berbeda.  

---

**Highlight Penting**  

<img src="25.png"  width="200"> 

- Blok khusus untuk info penting.  
- Garis tebal di kiri + latar pink lembut.  
- Teks tebal berwarna kontras.  

---

**Teks Skill**  

<img src="26.png"  width="200"> 

- Border dashed pink.  
- Latar pink muda.  
- Teks tebal → menonjolkan daftar skill.  

---

**Footer Lengkap**  

<img src="27.png"  width="200"> 

- Lebih elegan dengan border & radius.  
- Font lebih besar, warna teks pink gelap.  

---

**Link Sosial Media**

<img src="28.png"  width="200"> 

- Link otomatis diwarnai sesuai kata di URL.  
- Instagram → pink cerah, TikTok → ungu tua.  

---

**Hover Link Kedua**  

<img src="29.png"  width="200"> 

- Tambahan efek: warna berubah pink terang saat hover.  

---

**Hover Tombol Menu** 

<img src="30.png"  width="200"> 

- Border muncul saat hover.  
- Background jadi putih → tombol lebih interaktif.  

---

**Hover Kotak Info**

<img src="31.png"  width="200"> 

- Kotak berubah pink muda saat disentuh mouse.  

---

**Pseudo-element Heading** 

<img src="32.png"  width="200"> 

- Tambahkan bullet pink sebelum setiap judul H2 di dalam .kotak-info.  

---

**Responsif Tablet** 

<img src="33.png"  width="200"> 

- Layout jadi lebih ringkas.  
- Menu berubah vertikal.  
- Kotak info lebar penuh.  

---

**Responsif Mobile** 

<img src="34.png"  width="200"> 

- Judul & teks mengecil.  
- Menu lebih kecil → pas untuk layar HP.  
