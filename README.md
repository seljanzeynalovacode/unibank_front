# 🏦 Unibank Clone — Frontend Project

A responsive front-end clone of the [Unibank Azerbaijan](https://unibank.az) website, built with HTML5, CSS3, and Bootstrap 5.

---

## 🖥️ Live Preview

> Open `index.html` directly in your browser — no build step required.

---

## 📂 Project Structure

```
project/
│
├── index.html          # Main HTML file
└── css/
    └── style.css       # Custom styles (overrides & additions)
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure & semantic markup |
| CSS3 | Custom styling & layout |
| Bootstrap 5.3.8 | Responsive grid, navbar, carousel, cards |
| Font Awesome 7 | Icons (moon, phone, search, etc.) |

---

## 📦 CDN Dependencies

All external libraries are loaded via CDN — no `npm install` needed.

```html
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Font Awesome 7 -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">

<!-- Bootstrap JS Bundle -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
```

---

## 🗂️ Page Sections

| Section | Description |
|---|---|
| `<header>` | Logo, top navigation, Fərdi/Biznes tabs, dark mode icon, language switcher, search |
| `<nav class="mainnav">` | Secondary nav (Kartlar, Kreditlər, Əmanətlər…) + phone number |
| `<main>` — Carousel | 3-slide Bootstrap carousel with product banners |
| `#main2` | 3 feature cards (Nağd kreditlər, Əmanətlər, Kredit kartı) |
| `#hero-ucard` | UCard hero section with image + CTA buttons |
| `#ubank` | UBank mobile app section with store badges |

---

## ⚙️ Getting Started

1. **Clone or download** the repository:
   ```bash
   git clone https://github.com/your-username/unibank-clone.git
   cd unibank-clone
   ```

2. **Open in browser:**
   ```bash
   # Simply open the file
   open index.html
   # or with VS Code Live Server extension
   code .
   ```

> ✅ No build tools, no package manager — pure HTML/CSS/JS.

---

## 🎨 Customisation

### Colours
Edit `css/style.css` to change brand colours. The primary orange accent used across the site:
```css
/* Unibank primary orange */
color: #FF7A00;
```

### Carousel Images
Replace the `src` URLs inside `.carousel-item` with your own images:
```html
<img id="cpic1" src="YOUR_IMAGE_URL" class="d-block" alt="...">
```

### Navigation Links
Update the `href="#"` placeholders in `<nav>` with real page URLs when routing is implemented.

---

## 📱 Responsive Behaviour

| Breakpoint | Behaviour |
|---|---|
| `lg` (≥992px) | Full horizontal navbar visible |
| `md` (≥768px) | 3-column card grid in `#main2` |
| `< md` | Cards stack vertically, navbar collapses |

---
git clone: https://github.com/seljanzeynalovacode/unibank_front.git

---

## 📄 License

This project is for **educational purposes only**.  
All images and brand assets belong to [Unibank OJSC](https://unibank.az). Not affiliated with or endorsed by Unibank.
