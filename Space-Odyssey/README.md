# 🚀 Space Odyssey

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Space Odyssey** adalah sebuah game *2D side-scrolling space shooter* interaktif berbasis web. Pemain akan mengendalikan pesawat ruang angkasa untuk bertahan hidup, menghindari rintangan, dan bertempur di galaksi yang luas.

---

## 🎮 Fitur Utama

- **Side-Scrolling Action:** Mekanik pertempuran klasik dengan *scrolling* dinamis yang responsif.
- **Dynamic Ship Animation:** Animasi pergerakan pesawat yang mendetail, termasuk perubahan *sprite* visual ketika pesawat miring ke kiri dan ke kanan saat melakukan manuver.
- **High-Quality Assets:** Menggunakan aset grafis berukuran besar (disimpan dalam folder `IMG/` dan dioptimalkan pengunggahannya dengan Git LFS) untuk memberikan pengalaman visual yang maksimal.
- **Responsive Controls:** Sistem kontrol berbasis *keyboard* yang dioptimalkan untuk pergerakan mulus dan presisi.

## 📂 Struktur Direktori

- `index.html` — Berkas utama (*entry point*) untuk menjalankan game.
- `IMG/` — Direktori khusus penyimpanan seluruh aset gambar, *sprite* karakter/pesawat, dan latar belakang.
- *File CSS & JS* — Mengatur tata letak antarmuka, *hitbox*, dan *core logic* dari game.

## 🛠️ Teknologi Pendukung

Proyek ini dibangun dari awal (tanpa bantuan *game engine* instan) untuk mengeksplorasi fondasi logika pemrograman komputasi dan manipulasi DOM secara langsung:

* **HTML5:** Digunakan untuk merancang struktur kanvas (*canvas area*) utama.
* **CSS3:** Menangani elemen *styling* dan *layouting* antarmuka pengguna.
* **Vanilla JavaScript:** Menjadi otak di balik keseluruhan game, mencakup fisika pergerakan, deteksi tabrakan (*collision detection*), sinkronisasi animasi, dan eksekusi *game loop*.

## 🚀 Cara Menjalankan Game

1. **Persiapan:**
   Repositori ini memuat aset resolusi tinggi menggunakan **Git LFS**. Pastikan kamu sudah menginstal Git LFS di komputermu, lalu jalankan perintah:
   ```bash
   git lfs install

2. **Clone Repository:**
   ```bash
   git clone [https://github.com/Bluwww/Space-Odyysey.git](https://github.com/Bluwww/Space-Odyysey.git)

3. **Buka Folder Game:**
   Arahkan terminal ke dalam direktori game yang baru saja diunduh:
   ```bash
   cd Space-Odyysey/Space-Odyssey

4. **Mainkan:**
   Klik ganda pada file index.html untuk menjalankannya secara lokal di browser (Chrome, Brave, Firefox, atau Edge). Tidak membutuhkan instalasi server atau
   dependensi tambahan!
