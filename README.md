<div align="center">

<img src="https://marzuqnx.com/logo-marzuqnx.webp" width="80" alt="MarzuQNX Logo" />

# MarzuQNX

**ONE OS · MANY PROCESSES**

Platform engineering oleh [Mohammad Bany](https://marzuqnx.com) — Jakarta, Indonesia

[![Website](https://img.shields.io/badge/Website-marzuqnx.com-0a0a0a?style=flat-square&logo=google-chrome&logoColor=white)](https://marzuqnx.com)
[![Email](https://img.shields.io/badge/Email-kotaksurat%40marzuqnx.com-0a0a0a?style=flat-square&logo=gmail&logoColor=white)](mailto:kotaksurat@marzuqnx.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohammadbany-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dbanie/)
[![Spotify](https://img.shields.io/badge/Spotify-dbanie-1DB954?style=flat-square&logo=spotify&logoColor=white)](https://open.spotify.com/intl-id/artist/5FnrbxU9tLlU4bKBQTC0YI)

</div>

---

## Tentang

**MarzuQNX** adalah platform engineering personal yang dibangun dan dioperasikan oleh **Mohammad Bany** — seorang *infrastructure engineer*, *web developer*, *game designer*, dan *music artist* yang berbasis di **Jakarta, Indonesia**.

Nama MarzuQNX berasal dari dua akar:
- **Marzuqi** — kata Arab bermakna *rizki yang diberikan* (divine provision)
- **NX** — terinspirasi dari arsitektur Unix/POSIX

Situs ini menggunakan metafora **sistem operasi desktop** — setiap layanan adalah proses, setiap proyek adalah thread yang sedang berjalan.

> **Stack:** React · TypeScript · Vite · Three.js · Supabase · Cloudflare
>
> **Live:** [https://marzuqnx.com](https://marzuqnx.com)

---

## Layanan

MarzuQNX menyediakan empat layanan utama untuk klien bisnis (B2B) di Indonesia:

### Server & Infrastruktur Linux

Manajemen server Linux dan Windows — cloud maupun on-premise. Mulai dari setup VPS, konfigurasi Nginx, Docker containerization, Cloudflare DNS management, hingga maintenance harian.

**Teknologi:** Linux · Docker · Nginx · Cloudflare · Fail2ban · ISPConfig

*Cocok untuk bisnis yang butuh server stabil tanpa harus mengerti detail teknis.*

---

### Email Hosting & Manajemen Bisnis

Setup dan kelola **email profesional berbasis domain sendiri** untuk bisnis — lengkap dengan konfigurasi SPF, DKIM, dan DMARC agar email tidak masuk spam.

Saat ini mengelola **12 domain** dan **83 akun email bisnis** sejak 2019.

**Teknologi:** Postfix · Dovecot · SPF · DKIM · DMARC · ISPConfig

*Layanan email hosting bisnis Indonesia yang terpercaya dan terpantau.*

---

### Pengembangan Web Custom

Website dan sistem operasional bisnis yang dibuat dari nol — dari *company profile* modern hingga sistem manajemen internal yang menggantikan spreadsheet.

**Teknologi:** React · Next.js · Laravel · Filament · WordPress · REST API · MySQL · Supabase

*Jasa web development Jakarta untuk bisnis B2B — profesional, cepat, terstruktur.*

---

### Konsultasi IT

Audit infrastruktur dan rekomendasi teknis sebelum bisnis salah investasi di tools yang tidak diperlukan. *Booking only.*

**Fokus:** Architecture review · Cloud planning · Stack optimization · Security audit

---

## Produk

### Word Striker

*Cross-platform word battle game* — menggabungkan eksplorasi kosakata, gameplay strategis, dan boss battles.

- **Platform:** Android (Google Play)
- **Stack:** Flutter · Flame Engine · Supabase · Firebase · SQLite
- **Status:** Internal Testing

[![Google Play](https://img.shields.io/badge/Google_Play-Word_Striker-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.dbanie.wordstriker)

---

### TBSmart

Platform operasional koperasi modern — integrasi simpan-pinjam, distribusi produk, bagi hasil, inventaris, laporan keuangan, dan dashboard administrasi.

- **Stack:** Laravel · Filament · Flutter · REST API · MySQL
- **Status:** Development

---

## Portfolio

| Proyek | Tahun | Peran | Stack |
|--------|-------|-------|-------|
| [Tabira Petro Energi](https://marzuqnx.com/works) | 2026 | Infrastructure Engineer | Linux · Docker · Nginx · Next.js |
| [YPPAI Foundation](https://marzuqnx.com/works) | 2026 | Technical Advisor | Laravel · Linux · YouTube API |
| [PT Juan Kargo Tama](https://marzuqnx.com/works) | 2026 | Web Developer | WordPress · Nginx · Cloudflare |
| [Jessica Dora Couture](https://marzuqnx.com/works) | 2025 | Web Developer | WordPress · PHP · MySQL |
| [BTS8 Group](https://marzuqnx.com/works) | 2025 | Web Developer | Zyro · WooCommerce · WordPress |
| [Tekindo Energi & Gunung Mas Group](https://marzuqnx.com/works) | 2025–kini | Infrastructure Engineer | ISPConfig · Jitsi · Samba AD DC |
| [dbanie / Marz Qnx](https://open.spotify.com/intl-id/artist/5FnrbxU9tLlU4bKBQTC0YI) | 2025–kini | Artist & Lyricist | Spotify · YouTube Music |
| [PT Sepertiga Malam Sinergi](https://marzuqnx.com/works) | 2022 | Web Developer | WordPress |
| Email Hosting Infrastructure | 2019–kini | System Administrator | Postfix · Dovecot · SPF/DKIM |

---

## Tech Stack

```
Infrastructure
├── Linux (Debian, Ubuntu)
├── Docker & Docker Compose
├── Nginx (reverse proxy, load balancer)
├── Cloudflare (DNS, CDN, WAF)
├── Postfix + Dovecot (mail server)
├── ISPConfig (web & email panel)
├── Fail2ban (security)
└── Jitsi Meet, Samba AD DC, Lancache

Web Development
├── React + TypeScript + Vite
├── Next.js (SSR/SSG)
├── Laravel + Filament (PHP)
├── WordPress
├── Three.js + WebGL
└── Supabase + Firebase + MySQL

Mobile
├── Flutter
├── Flame Engine
└── Android (Google Play)

DevOps
├── Docker
├── Git
├── Cloudflare Workers
└── Nginx
```

---

## Arsitektur Situs

Website MarzuQNX menggunakan arsitektur **SPA** dengan metafora desktop OS:

- **Framework:** React 19 + TypeScript + Vite 8
- **Animation:** Framer Motion + GSAP
- **3D:** Three.js (GPU particle nebula system)
- **Backend:** Supabase (real-time geolocation widget)
- **Styling:** Vanilla CSS (dark mode native)
- **Hosting:** Cloudflare (CDN + WAF)
- **i18n:** i18next (Bahasa Indonesia + English)

Fitur utama:
- Desktop OS metaphor dengan terminal dialog system
- Particle field background reaktif terhadap state konten
- Music player dengan integrasi YouTube
- Real-time geolocation widget (GeoTrace)
- Dark mode / light mode toggle
- Bilingual support (ID/EN)

**[Lihat langsung di marzuqnx.com](https://marzuqnx.com)**

---

## Kontak

Butuh **web developer Jakarta freelance**, **email hosting bisnis Indonesia**, **Linux server management**, atau **IT consulting**?

| Channel | Link |
|---------|------|
| Website | [marzuqnx.com](https://marzuqnx.com) |
| Email | [kotaksurat@marzuqnx.com](mailto:kotaksurat@marzuqnx.com) |
| LinkedIn | [linkedin.com/in/mohammadbany](https://www.linkedin.com/in/dbanie) |
| GitHub | [github.com/marzuqnx](https://github.com/marzuqnx) |
| Spotify (dbanie) | [dbanie on Spotify](https://open.spotify.com/intl-id/artist/5FnrbxU9tLlU4bKBQTC0YI) |
| Spotify (Marz Qnx) | [Marz Qnx on Spotify](https://open.spotify.com/intl-id/artist/6aVp1BB01F3ufkspBDM4rt) |

---

<div align="center">

**[marzuqnx.com](https://marzuqnx.com)** · Jakarta, Indonesia · © 2019–2026 Mohammad Bany

*Infrastructure Engineer · Web Developer · Game Designer · Music Artist*

</div>
