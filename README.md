# 🍰 Sugar Rush

> Responsive cake bakery website built following **Bedimcode**'s tutorial.  
> Vanilla HTML/CSS/JS, Swiper sliders, mobile-first navigation, scroll reveal animations.  
> Sweet code, sweeter design.

---

## 📸 Preview

<p align="center">
  <img src="assets/img/preview.png" alt="Sugar Rush — Delizia Bakery Preview" width="800"/>
</p>

<!--
<p align="center">
  <img src="assets/img/screenshot-home.png" alt="Home Section" width="400"/>
  <img src="assets/img/screenshot-menu.png" alt="Mobile Menu" width="400"/>
</p>
-->

---

## ⚠️ Project Status

> **🚧 Work in Progress** — This project is not complete yet.  
> Some sections (About, Products, New, Contact, Footer) are still under development.  
> Features and styling may change.

---

## ✨ Features

- **Fully Responsive** — mobile-first, breakpoints at 1150px, 2K+
- **Swiper Sliders** — home cakes carousel, products, new arrivals
- **Smooth Animations** — ScrollReveal on scroll, CSS transitions
- **Mobile Hamburger Menu** — slide-in nav with overlay
- **CSS Custom Properties** — theming, responsive typography
- **Vanilla Stack** — zero frameworks, no build step
- **Accessible** — semantic HTML, ARIA labels, focus states

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic markup |
| CSS3 | Custom properties, Grid, Flexbox, Animations |
| JavaScript (ES6+) | DOM, Swiper init, ScrollReveal, Menu logic |
| [Swiper](https://swiperjs.com/) | Touch sliders |
| [ScrollReveal](https://scrollrevealjs.org/) | Scroll animations |
| [Remixicon](https://remixicon.com/) | Icon font |
| [Google Fonts](https://fonts.google.com/) | Montserrat, Pacifico |

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/sugar-rush.git
cd sugar-rush

# Open index.html in browser
# (or run Live Server in VS Code)
```

No `npm install`, `build`, or dependencies — pure frontend.

---

## 📁 Project Structure

```
sugar-rush/
├── index.html           # Entry point
├── assets/
│   ├── css/
│   │   └── styles.css   # All styles
│   ├── js/
│   │   └── main.js      # All logic
│   └── img/             # Images, SVGs, favicons
└── README.md
```

---

## 🎨 Customization

| What to change | Where to look |
|----------------|---------------|
| Brand colors | `:root` in `styles.css` (`--first-color`, `--second-color`...) |
| Fonts | `@import` in `styles.css` + `--body-font`, `--second-font` |
| Content | `index.html` (texts, links, images) |
| Animations | `main.js` → ScrollReveal config |
| Sliders | `main.js` → Swiper configs |

---

## 📱 Responsive Breakpoints

```css
/* Mobile First → */
@media (width <= 1150px)  { /* Tablet / Mobile menu */ }
@media (width >= 1150px)  { /* Desktop */ }
@media (width >= 1440px)  { /* Large desktop */ }
@media (width >= 2560px)  { /* 2K+ */ }
```

---

## 🙏 Credits

Built following [Bedimcode](https://www.youtube.com/@Bedimcode)'s  
**"Responsive Cake Website"** tutorial on YouTube.

Original design & tutorial by Bedimcode — thank you for the amazing content!

---

## 📄 License

[MIT License](LICENSE) — free to use, modify, distribute.  
Keep a copy of the license when forking.

---

## 👤 Author

<!-- 👇 СВОИ ДАННЫЕ ЗДЕСЬ -->
h1chan — [GitHub](https://github.com/h1chan) · [Discord](https://discord.com/users/1064052965247295518)

---

<p align="center">
  Made with 🍰 and vanilla JS
</p>
