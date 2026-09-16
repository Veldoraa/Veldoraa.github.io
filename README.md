# Personal Portfolio — Astro + Tailwind

Starter website portfolio personal yang dibuat dengan Astro, Tailwind CSS v4, dan JavaScript.

## Requirements

Gunakan Node.js 22.12+ sesuai dokumentasi Astro saat ini.

## Install

```bash
npm install
```

## Development

```bash
npm run dev
```

Buka URL yang muncul di terminal, biasanya `http://localhost:4321`.

## Build production

```bash
npm run build
npm run preview
```

## Yang perlu diganti

Edit `src/pages/index.astro`:

- `Your Name`
- role/tagline
- About
- Skills
- Projects
- Experience
- email
- social media
- lokasi
- tahun

Untuk foto profil, tambahkan file ke `public/images/` lalu ubah blok visual di bagian Hero.

## Struktur

```text
src/
├── components/
│   ├── Navbar.astro
│   ├── ProjectCard.astro
│   └── SectionTitle.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```
