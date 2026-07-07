# Master Section Library

Kumpulan section UI yang dikonversi dari Bootstrap → Tailwind CSS, siap untuk diintegrasikan ke dalam CMS sebagai Blade component.

---

## Tech Stack

- **HTML5** (semantic)
- **Tailwind CSS** (via CDN)


---

## Struktur Folder

```
Master-Section/
├── index.html              → Preview gallery semua section
├── README.md
│
├── assets/
│   ├── images/             → Gambar/foto yang dipakai section
│   ├── icons/              → Icon (SVG, dll)
│   └── fonts/              → Font lokal (jika ada)
│
├── sections/               → File HTML per section (1 file = 1 section)
│   ├── about/
│   ├── blog/
│   ├── call-to-action/
│   ├── clients/
│   ├── contact/
│   ├── facts/
│   ├── faq/
│   ├── features/
│   ├── footer/
│   ├── hero/
│   ├── misc/
│   ├── navbar/
│   ├── portfolio/
│   ├── pricing/
│   ├── process/
│   ├── team/
│   └── testimonials/
│
│
└── docs/
    └── PRD_Master_Section_Tailwind.md
```

---

## Naming Convention

| Tipe | Format | Contoh |
|------|--------|--------|
| Section tunggal | `[nama].html` | `hero.html` |
| Section dengan variasi | `[nama]-[variasi].html` | `navbar-center.html` |
| Blade file | `[nama].blade.php` | `hero.blade.php` |

---

## Cara Kerja

1. Ambil section dari template Bootstrap (Sandbox)
2. Konversi class Bootstrap → Tailwind utility class
3. Rapikan HTML, pastikan semantic
4. Simpan di `sections/[nama-section]/`
5. Test di browser
6. Jika sudah oke → konversi ke Blade, simpan di `blade/[nama-section]/`

---

