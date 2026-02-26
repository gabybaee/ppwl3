# ppwl3

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.8. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.

---
## Praktikum 2 Perbedaan Utama Tailwind CSS v3 vs v4

1. **Konfigurasi dan Setup Berubah**
   - Di **Tailwind v3**, kita biasanya memakai file `tailwind.config.js` untuk mengatur tema, konten, plugin, dll.
   - Di **Tailwind v4**, konfigurasi beralih ke **CSS-first** (tidak wajib pakai file JavaScript), dengan `@import "tailwindcss"` dan `@theme` di CSS, membuat setup lebih sederhana dan modern. :contentReference[oaicite:0]{index=0}

2. **Build Engine dan Kinerja**
   - **Tailwind v4** memakai mesin baru berbasiskan **Rust** (Oxide engine) yang jauh lebih cepat dalam mengompilasi CSS dan mendeteksi kelas secara otomatis tanpa perlu set `content:` manual. :contentReference[oaicite:1]{index=1}

---

##  Catatan Tambahan
- v4 juga menghapus utilitas yang sudah *deprecated*, mengubah nama utilitas, dan mengoptimalkan default styling agar lebih konsisten. :contentReference[oaicite:2]{index=2}
- Perubahan ini biasanya terlihat jelas jika kamu membuka **play.tailwindcss.com**, karena default setup dan hasil style bisa berbeda antara v3 dan v4.

## Praktikum 4

Jika memberi warna latar belakang seperti `bg-blue-600` (Tailwind CSS), maka bagian box model yang terpengaruh adalah:

- Content
- Padding

Margin tidak ikut terpengaruh karena berada di luar elemen.

## Praktikum 7
[Link Screenshot Dark Mode](https://drive.google.com/file/d/1lb6BVzIxZDk6MPtluNSjWwKZXT9kylm-/view?usp=sharing)