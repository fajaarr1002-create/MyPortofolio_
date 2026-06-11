<div align="center">

```
  ███████╗ █████╗      ██╗ █████╗ ██████╗
  ██╔════╝██╔══██╗     ██║██╔══██╗██╔══██╗
  █████╗  ███████║     ██║███████║██████╔╝
  ██╔══╝  ██╔══██║██   ██║██╔══██║██╔══██╗
  ██║     ██║  ██║╚█████╔╝██║  ██║██║  ██║
  ╚═╝     ╚═╝  ╚═╝ ╚════╝ ╚═╝  ╚═╝╚═╝  ╚═╝

  P H O T O G R A P H Y   P O R T F O L I O
        — Neo Brutalism Edition —
```

**Website portfolio fotografi personal. Playful, colorful, penuh karakter.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

![No Framework](https://img.shields.io/badge/Framework-NONE-f56fa1?style=flat-square)
![Vanilla](https://img.shields.io/badge/100%25-Vanilla-8bd61a?style=flat-square)
![Mobile First](https://img.shields.io/badge/Design-Mobile%20First-58d2cf?style=flat-square)
![Neo Brutalism](https://img.shields.io/badge/Style-Neo%20Brutalism-ffe600?style=flat-square)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-a55df6?style=flat-square)

*Belajar. Motret. Repeat.*

---

</div>

## Tentang Project

Website portfolio fotografi personal milik **Fajar** — pelajar SMP yang hobi mengabadikan momen lewat kamera **Canon SX410 IS** dan **Redmi 13**.

Dibangun dengan desain **Neo Brutalism**:

> Border tebal `4px` — Shadow brutal `6px 6px 0` — Warna playful — Sticker effect — Floating doodles — Retro internet vibes

Dan yang paling penting: **tanpa framework sama sekali**. Murni HTML + CSS + Vanilla JavaScript.

---

## Struktur Project

```
portfolio-fajar/
│
├── index.html ......... Struktur halaman (semantic & accessible)
├── style.css .......... Neo brutalism styling (mobile first)
├── script.js .......... Semua interaksi & animasi
└── README.md .......... Kamu lagi baca ini
```

**Tiga file. Itu saja.** Tidak ada `node_modules` seberat black hole.

---

## Fitur

| # | Fitur | Deskripsi |
|:-:|:------|:----------|
| 01 | **Loading Animation** | Loader playful dengan progress bar brutal |
| 02 | **Smooth Scroll** | Navigasi antar section mulus seperti gimbal |
| 03 | **Active Navbar** | Menu otomatis highlight sesuai posisi scroll |
| 04 | **Scroll Reveal** | Elemen muncul elegan saat di-scroll |
| 05 | **Gallery Modal** | Klik foto > fullscreen + prev/next + keyboard support |
| 06 | **Animated Counter** | Statistik menghitung naik saat terlihat |
| 07 | **Animated Progress Bar** | Skill bar mengisi dengan animasi smooth |
| 08 | **Floating Shapes** | Doodle melayang dengan efek parallax |
| 09 | **Back to Top** | Tombol kembali ke atas, muncul saat scroll |
| 10 | **Mobile Menu** | Hamburger menu responsive untuk layar kecil |
| 11 | **Contact to WhatsApp** | Form kontak langsung terhubung ke WhatsApp |
| 12 | **SVG Icon System** | Zero emoji — 30 custom inline SVG icons |

---

## Color Palette

| Warna | Hex | Preview |
|:------|:----|:--------|
| Cream | `#f3eedf` | ![#f3eedf](https://img.shields.io/badge/-%20%20%20%20%20%20-f3eedf?style=flat-square) |
| Dark Navy | `#171932` | ![#171932](https://img.shields.io/badge/-%20%20%20%20%20%20-171932?style=flat-square) |
| Pink | `#f56fa1` | ![#f56fa1](https://img.shields.io/badge/-%20%20%20%20%20%20-f56fa1?style=flat-square) |
| Cyan | `#58d2cf` | ![#58d2cf](https://img.shields.io/badge/-%20%20%20%20%20%20-58d2cf?style=flat-square) |
| Yellow | `#ffe600` | ![#ffe600](https://img.shields.io/badge/-%20%20%20%20%20%20-ffe600?style=flat-square) |
| Purple | `#a55df6` | ![#a55df6](https://img.shields.io/badge/-%20%20%20%20%20%20-a55df6?style=flat-square) |
| Orange | `#ff9800` | ![#ff9800](https://img.shields.io/badge/-%20%20%20%20%20%20-ff9800?style=flat-square) |
| Green | `#8bd61a` | ![#8bd61a](https://img.shields.io/badge/-%20%20%20%20%20%20-8bd61a?style=flat-square) |

**Design tokens:**

```css
--border:  4px solid #1e1e2f;   /* border tebal khas brutalism   */
--shadow:  6px 6px 0 #1e1e2f;   /* shadow keras tanpa blur       */
--radius:  18px;                /* rounded yang tetap friendly   */
```

**Typography:** [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) · [Poppins](https://fonts.google.com/specimen/Poppins) · [Space Mono](https://fonts.google.com/specimen/Space+Mono)

---

## Peta Halaman

```
┌──────────────────────────────────────────────────────┐
│  HERO ......... Intro + terminal mockup + counter    │
│  ABOUT ........ Siapa sih Fajar? + cards + quote     │
│  CAMERA ....... Canon SX410 IS, gear sederhana       │
│  GALLERY ...... 8 foto terbaik (klik = fullscreen)   │
│  PROJECTS ..... 4 project fotografi                  │
│  SKILLS ....... Progress bar animated                │
│  CONTACT ...... Form + info + social media           │
└──────────────────────────────────────────────────────┘
```

---

## Cara Menjalankan

Tidak perlu install apa-apa. Serius.

```bash
# 1. Clone repo ini
git clone https://github.com/username/portfolio-fajar.git

# 2. Masuk ke folder
cd portfolio-fajar

# 3. Buka index.html di browser — selesai.
```

Atau pakai local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

Lalu buka `http://localhost:8000`.

---

## Deploy

Website ini **100% static**, bisa di-deploy gratis ke mana saja:

| Platform | Cara |
|:---------|:-----|
| **GitHub Pages** | Settings > Pages > pilih branch `main` > done |
| **Netlify** | Drag & drop folder ke netlify.com/drop |
| **Vercel** | `npx vercel` > enter beberapa kali > live |
| **Cloudflare Pages** | Connect repo > deploy |

---

## Tech Stack

| Teknologi | Keterangan |
|:----------|:-----------|
| **HTML5** | Semantic markup, accessible |
| **CSS3** | Custom properties, grid, flexbox, clip-path, keyframes |
| **Vanilla JS** | IntersectionObserver, requestAnimationFrame, zero dependencies |
| **Google Fonts** | Space Grotesk, Poppins, Space Mono |
| **SVG Sprite** | 30 custom inline icons, tanpa library |

```
TIDAK DIPAKAI:  React · Vue · Angular · Next.js
                Bootstrap · Tailwind · TypeScript · jQuery
```

---

## Tentang Sang Fotografer

> *"Umur cuma angka. Yang penting **passion**, **konsistensi**, dan **keberanian** untuk terus belajar."*
> — Fajar

```
Lokasi ......... Jawa Timur, Indonesia
Status ......... Pelajar SMP
Gear ........... Canon SX410 IS + Redmi 13
Side quest ..... Vibecoding
Response ....... < 24 jam
Kolaborasi ..... OPEN
```

### Kontak

[![Instagram](https://img.shields.io/badge/@snapshot.by.jare-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/snapshot.by.jare)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6285708557587)
[![Email](https://img.shields.io/badge/fajaarr1001@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fajaarr1001@gmail.com)

---

## License

```
(c) 2026 Fajar. All rights reserved.

Foto-foto di website ini adalah karya pribadi.
Kode boleh dipelajari dan dijadikan referensi belajar.
```

---

<div align="center">

### Kalau project ini keren, kasih bintang ya!

```
┌─────────────────────────────────────────┐
│                                         │
│      Made with passion by F A J A R     │
│                                         │
│        Belajar · Motret · Repeat        │
│                                         │
└─────────────────────────────────────────┘
```

**[Kembali ke atas](#tentang-project)**

</div>
