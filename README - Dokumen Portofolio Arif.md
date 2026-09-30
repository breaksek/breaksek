# 🚀 Personal Portfolio Website - Arif

Selamat datang di repositori kode sumber untuk website portofolio pribadi **Arif** (Mobile & Web Developer). Website ini dirancang dengan tampilan modern bermutu tinggi (*Dark Mode Neon Glassmorphism*), responsif penuh, serta interaktif.

![Portfolio Preview](https://via.placeholder.com/1200x600/0b0f19/06b6d4?text=Arif+Developer+Portfolio+Preview)

---

## 📌 Ringkasan

Website portofolio ini dibangun untuk menampilkan profil profesional, daftar keahlian (*tech stack*), proyek-proyek unggulan, pengalaman pendidikan/KKN, serta menyediakan media komunikasi bagi calon klien maupun kolaborator.

---

## ✨ Fitur Utama

- **🎨 Modern Dark Mode & Glassmorphism UI:** Desain visual futuristik menggunakan aksen warna neon cyan, violet, dan *blur glassmorphism*.
- **📱 Fully Responsive:** Tampilan optimal di semua ukuran layar (Mobile, Tablet, Desktop).
- **🗂️ Interactive Project Filtering:** Penyaringan proyek interaktif berdasarkan kategori (*Mobile*, *Web*, *Backend*).
- **🔍 Project Detail Modal:** Jendela dialog interaktif untuk melihat rincian spesifikasi, fitur, dan teknologi tiap proyek.
- **⚡ Fast & Lightweight:** Dibuat menggunakan HTML5 murni dan Tailwind CSS via CDN tanpa dependensi *build-tool* yang berat.
- **📬 Dynamic Contact Form:** Formulir kontak interaktif siap guna.

---

## 🛠️ Tech Stack & Alat

* **Front-end Framework/Styling:** [Tailwind CSS v3](https://tailwindcss.com/)
* **Typography:** [Inter](https://fonts.google.com/specimen/Inter) & [Fira Code](https://fonts.google.com/specimen/Fira+Code) (Google Fonts)
* **Iconography:** [Font Awesome v6](https://fontawesome.com/)
* **Interactivity:** Vanilla JavaScript (ES6+)

---

## 📂 Struktur Repositori

```text
.
├── index.html          # File HTML utama (berisi UI, Styling Tailwind & Script)
└── README.md           # Dokumentasi repositori
```

---

## 🚀 Cara Menjalankan Secara Lokal

Repositori ini berjenis *Single File Static Website*, sehingga kamu tidak perlu menginstal `npm` atau *build tools* tambahan.

1. **Clone Repositori ini:**
   ```bash
   git clone https://github.com/username-kamu/portfolio-arif.git
   ```

2. **Masuk ke Direktori Proyek:**
   ```bash
   cd portfolio-arif
   ```

3. **Buka File `index.html`:**
   * Cukup klik dua kali pada file `index.html`, **atau**
   * Gunakan ekstensi **Live Server** di Visual Studio Code untuk mendapatkan fitur *hot-reload*.

---

## 🔧 Cara Kustomisasi

Beberapa bagian yang bisa kamu sesuaikan dengan kebutuhanmu:

1. **Mengubah Informasi Diri:**
   Buka `index.html` lalu ubah teks pada bagian `<section id="tentang">` dan objek JSON di kartu visual kanan (`arif.config.json`).
2. **Menambah/Mengedit Proyek:**
   * Tambahkan elemen HTML kartu proyek di bagian `<div id="projects-grid">`.
   * Perbarui/tambahkan objek detail proyek pada variabel `projectsData` di dalam tag `<script>`.
3. **Konfigurasi Formulir Kontak:**
   Bisa dihubungkan ke layanan gratis seperti [Formspree](https://formspree.io/) atau [EmailJS](https://www.emailjs.com/) dengan mengganti *action handler* pada `#contact-form`.

---

## 🌐 Deploy (Peluncuran Website)

Website ini sangat gampang diunggah secara gratis ke berbagai layanan hosting statis:

- **GitHub Pages:**
  1. Masuk ke *Settings* repositori GitHub kamu.
  2. Pilih menu **Pages**.
  3. Set cabang (*Branch*) ke `main` / `root`, lalu klik **Save**.
- **Vercel / Netlify:**
  Hubungkan repositori GitHub ini ke Vercel atau Netlify untuk *deployment* otomatis setiap kali kamu melakukan `git push`.

---

## 📝 Lisensi

Proyek ini terbuka di bawah lisensi [MIT License](LICENSE). Bebas digunakan, dimodifikasi, dan dikembangkan kembali.

---

<p center align="center">
  Dibuat dengan ❤️ oleh <b>Arif</b> — Mobile & Web Developer
</p>
```