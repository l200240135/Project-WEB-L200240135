# LAPORAN — Tugas #1: Website Personal

## Deskripsi Proyek

Website personal statis yang dibangun menggunakan HTML semantik dan CSS eksternal murni. Website ini dirancang dengan tema **Biru muda & kuning Elegant** — memadukan palet warna biru dan kuning yang indah, tipografi display serif, dan animasi CSS yang halus.

**Tujuan:** Membangun WEB portofolio digital yang mencerminkan identitas dan kemampuan teknis saya sebagai mahasiswa Informatika.

**Fitur utama:**
- 3 halaman penuh: Home, Portfolio, Kontak
- Desain responsif (mobile & desktop)
- Animasi scroll-reveal dan hover
- Formulir kontak dengan umpan balik visual
- Favicon ico
- Aksesibilitas keyboard dan atribut `alt` pada semua gambar
- Tampilan Dark Mode

**Teknologi yang digunakan:** HTML5, CSS3 (Flexbox + Grid + Custom Properties), JavaScript, Google Fonts, Font Awesome 6

---

## Struktur Folder dan File

```
personal-website/
├── index.html         
├── portfolio.html      
├── contact.html        
├── style/
│   └── main.css        
├── assets/ 
│   ├── favicon.ico     
│   ├── main.js         
│   └── run.jpeg        
│          ├──images                           
│               ├── ssh.png
│               ├── validasi-contact.png
│               ├── validasi-css.png
│               ├── validasi-index.png
│               └── validasi-portfolio.png
└── LAPORAN.md          
```

---

## Link Website yang Sudah Di-host

> 🌐 **[https://l200240135.github.io/Project-WEB-L200240135/]**


---

## Bukti SSH Berhasil Dikonfigurasi
```
Hi l200240135! You've successfully authenticated, but GitHub does not provide shell access.
```
> 📸 [ssh]*(assets/images/ssh.png)*

---

## Hasil Validasi W3C

### HTML Validator — `index.html`
> 📸 [Validasi index]*(assets/images/validasi-index.png)*

### HTML Validator — `portfolio.html`
> 📸 [Validasi portfolio]*(assets/images/validasi-portfolio.png)*

### HTML Validator — `contact.html`
> 📸 [Validasi contact]*(assets/images/validasi-contact.png)*

### CSS Validator — `style/main.css`
> 📸 [Validasi css]*(assets/images/validasi-css.png)*

---

## Hasil Lighthouse (Bonus)

> 📸 [Lighthouse Mobile & Dekstop]*(assets/images/mobile.png)*
> *(assets/images/dekstop.png)*

---

## Catatan Pengembangan

- **Responsivitas:** Menggunakan 2 breakpoint — `max-width: 900px` (desktop) dan `max-width: 600px` (mobile).
- **Aksesibilitas:** Semua `<img>` memiliki atribut `alt` deskriptif. Navigasi dapat diakses dengan keyboard (Tab). Kontras warna text primary (`#e8e4dc`) terhadap background (`#0a0a0c`) memenuhi rasio WCAG AA (>4.5:1).
- **CSS Variables:** Semua warna, font, spacing, dan transisi menggunakan CSS custom properties agar mudah diubah.
- **Tanpa inline style** pada elemen konten — semua gaya ada di `style/main.css`.

---

*Tugas #1 Pemrograman Web — Universitas Muhammadiyah Surakarta 2026*
