# Pertemuan 1: Bio Link Sederhana (Linktree Clone)

Projek ini adalah halaman website personal Bio Link sederhana yang terinspirasi dari Linktree. Dibuat khusus untuk tugas pembelajaran dasar HTML & CSS.

## 🚀 Fitur Utama
* **Desain Premium**: Menggunakan tema gelap modern (*dark mode*) dengan efek kaca transparan (*glassmorphism*).
* **Avatar & Profil**: Menampilkan foto profil bulat dengan border gradien yang menyala (*glowing ring*).
* **Link Interaktif**: 4 tombol tautan interaktif dengan ikon SVG yang responsif ketika disentuh/diarahkan cursor.
* **Semantic HTML**: Menggunakan struktur tag HTML5 standar industri (`<header>`, `<main>`, `<nav>`, `<footer>`).
* **Responsif**: Tampilan otomatis menyesuaikan dengan layar HP/mobile maupun monitor Desktop.

---

## 🛠️ Cara Deploy ke GitHub Pages

Agar halaman web ini bisa diakses oleh siapa saja di internet (online secara gratis), ikuti langkah-langkah mudah berikut ini:

### Langkah 1: Hubungkan & Push ke GitHub
Buka terminal (Git Bash, Command Prompt, atau Terminal di VS Code) pada folder projek ini, lalu jalankan perintah berikut:

1. **Staging perubahan file:**
   ```bash
   git add .
   ```
2. **Membuat commit:**
   ```bash
   git commit -m "feat: membuat halaman bio link dan menambahkan avatar"
   ```
3. **Mengunggah kode ke GitHub:**
   ```bash
   git push origin main
   ```

### Langkah 2: Mengaktifkan GitHub Pages di Repository
Setelah berhasil melakukan push ke GitHub, ikuti langkah ini di browser Anda:

1. Buka browser dan pergi ke halaman repository GitHub Anda: `https://github.com/risyanisa/pertemuan-1-web-dev-surosowancyber`
2. Klik tab **Settings** (ikon gerigi) di bagian atas menu repository.
3. Di menu sidebar sebelah kiri, klik menu **Pages** (di bawah kategori *Code and automation*).
4. Pada bagian **Build and deployment**:
   * Di dropdown **Source**, pastikan terpilih **Deploy from a branch**.
   * Di bawah menu **Branch**, ubah dropdown pertama dari `None` menjadi **`main`**.
   * Dropdown kedua biarkan tetap **`/ (root)`**.
5. Klik tombol **Save**.
6. Tunggu sekitar 1 - 2 menit, lalu segarkan (refresh) halaman Settings tersebut.
7. Di bagian atas halaman **Pages**, akan muncul link halaman web Anda seperti:
   👉 `https://risyanisa.github.io/pertemuan-1-web-dev-surosowancyber/`

---

## 📝 Catatan Belajar HTML & CSS dalam Projek Ini
* **Tag Semantik**:
  * `<header>`: Digunakan untuk membungkus elemen kepala website (avatar, nama, bio).
  * `<main>`: Digunakan untuk area konten utama (tombol navigasi link).
  * `<nav>`: Digunakan untuk membungkus menu navigasi link.
  * `<footer>`: Digunakan untuk bagian kaki halaman / hak cipta.
* **CSS Flexbox**: Digunakan untuk menyusun layout secara vertikal (`flex-direction: column`) dan memposisikan seluruh halaman tepat di tengah layar (`justify-content: center`, `align-items: center`).
* **Glassmorphism**: Efek transparan mewah yang dihasilkan dari `background: rgba(...)` dikombinasikan dengan efek blur `backdrop-filter: blur(20px)`.
