# Portfolio Website - Zyrus Alfredo
**Nama: Zyrus Alfredo Randan Malinggato**\
**NIM: 2409116120**\
Website portofolio statis yang dibuat sebagai tugas praktikum untuk menampilkan Profil, Pengalaman, Keahlian, dan Sertifikat.\
**📍Go To Website: https://zyrusalfredo.vercel.app/**

---

# Tampilan Website💻
<img width="1920" height="3950" alt="127 0 0 1_5500_index html(Laptop)" src="https://github.com/user-attachments/assets/b6614ba6-2f31-47b8-9057-a8b8fd73a468" />

# Teknologi yang Digunakan⚙️
* **HTML** - Struktur dasar halaman web.
* **CSS** - Styling kustom (Glow effects, Glassmorphism, Responsive design).
* **Bootstrap 5** - Framework CSS untuk sistem grid (Layouting) dan komponen UI (Navbar, Progress Bar, Cards).
* **Vue JS** - Framework JavaScript untuk manajemen data statis yang interaktif menggunakan *Data Binding* dan *Directives*.

---

# 📸 Tampilan Fitur & Section

1. **Halaman Beranda**
   - Perkenalan singkat dengan efek teks bercahaya.
   - Tombol sosial media (LinkedIn & Instagram) dengan efek hover glow dan transisi mengambang.

<img width="1899" height="946" alt="image" src="https://github.com/user-attachments/assets/2ecc39e2-ef9b-404e-b8e5-adcd6cbe45e8" />

---
2. **Halaman Tentang (Pengalaman & Keahlian)**
   - Deskripsi diri yang ringkas.
   - Daftar pengalaman dan organisasi dalam bentuk kartu (cards) yang interaktif.
   - Visualisasi keahlian menggunakan Bootstrap Progress Bar dengan gradasi warna cyan.
  
<img width="1920" height="2303" alt="Tentang" src="https://github.com/user-attachments/assets/636dcdb4-8fd3-4f17-8f3c-754df93f02bb" />

---
3. **Certificates Section (Sertifikat)**
   - Layout grid yang menampilkan sertifikat dalam rasio gambar yang konsisten.
  
<img width="1920" height="592" alt="Sertifikat" src="https://github.com/user-attachments/assets/b7ba9986-7c7a-4765-a14d-e09d386cfac2" />

---
4. **Responsif Mode ke Mobile Device**
   - Tampilan yang responsif saat pindah ke perangkat mobile
  
<img width="577" height="932" alt="image" src="https://github.com/user-attachments/assets/8e9f32d6-e26f-4720-a6a2-ebbdcc04f356" />

---

# 🛠️ Penjelasan Kode (Technical Overview)
1. **Reactivity dengan Vue JS**: Data keahlian dan sertifikat disimpan dalam objek data() di Vue instance. Hal ini memungkinkan perubahan data di satu tempat tanpa harus mengubah struktur HTML berulang kali.
<img width="891" height="829" alt="image" src="https://github.com/user-attachments/assets/459ab207-5d57-4858-bb8f-a0d6cd8aa590" />

---
2. **Grid System**: Menggunakan kombinasi container, row, dan col-lg-X dari Bootstrap untuk memastikan elemen tersusun rapi di layar desktop maupun smartphone.
<img width="692" height="214" alt="image" src="https://github.com/user-attachments/assets/f24ef986-e42a-4bd7-b7dc-b44b73a01dea" />\
`Contoh salah satu section yang menggunakan kombinasi container, row, dan col-lg-X dari Bootstrap`

---
3. **Custom Styling**: 
  - .img-glow-wrapper: Menggunakan radial gradient untuk memberikan efek pendaran di belakang foto profil.
<img width="807" height="367" alt="image" src="https://github.com/user-attachments/assets/d90dbe21-e160-48a3-8830-d0a8b7b55a37" />

  - @media (max-width: 768px): Digunakan untuk menyesuaikan ukuran font dan tata letak tombol saat dibuka melalui perangkat mobile agar tetap proporsional.
<img width="403" height="689" alt="image" src="https://github.com/user-attachments/assets/a8066074-815d-4c1f-9262-16bf81459575" />

---
4. **Interactive UI**: Penggunaan CSS transition dan transform: translateY() pada setiap kartu dan tombol untuk memberikan pengalaman pengguna yang lebih dinamis.
<img width="1067" height="187" alt="image" src="https://github.com/user-attachments/assets/45623399-4956-458a-95e1-5272f353a27d" />

---
© 2026 Zyrus Alfredo - Mahasiswa Sistem Informasi 2024
