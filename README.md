# shecan
# 🌸 She Can Foundation — Frontend Internship Task

A beautifully designed, single-page website built for **She Can Foundation**, an NGO dedicated to empowering women and girls through education, mentorship, and community support.

---

## 📁 Project Structure

```
she-can-foundation/
│
├── she-can-foundation.html   # Main webpage (HTML + CSS + JS in one file)
└── README.md                 # Project documentation
```

---

## ✅ Features Implemented

### Required Elements
| Element | Details |
|---|---|
| NGO Name | "She Can Foundation" in navbar & hero |
| Heading | Animated hero heading with typewriter effect |
| About Section | Mission description + 3 feature cards |
| Image | Hero image with organic blob shape |
| Button | "Discover Our Mission" CTA with hover animation |
| Footer | Full footer with links, copyright & tagline |

### Bonus Features (Advanced)
| Feature | Details |
|---|---|
| 🌙 Dark Mode | Toggle button (bottom-right) switches full color scheme |
| ✍️ Typewriter Effect | Hero text cycles through empowering phrases |
| 🔢 Counter Animation | Stats count up from 0 when scrolled into view |
| 👁️ Scroll Reveal | Cards & sections fade-slide in on scroll |
| 📐 Responsive Design | Fully mobile-friendly layout |
| 🎨 CSS Animations | Blob morph, floating badge, hover effects |
| 🔝 Navbar Shrink | Navbar compresses smoothly on scroll |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, Flexbox, Grid, Keyframe animations
- **Vanilla JavaScript** — No frameworks or libraries needed
- **Google Fonts** — Playfair Display + DM Sans

---

## 🚀 How to Run

1. Download `she-can-foundation.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. No installation, no dependencies, no build step needed!

```bash
# Or serve locally with VS Code Live Server / Python
python -m http.server 8000
# Then open: http://localhost:8000/she-can-foundation.html
```

---

## 🎨 Design Decisions

- **Color Palette:** Rose (`#e8416e`), Blush (`#fde8ef`), Cream (`#fdf6f0`) — warm, feminine, and professional
- **Typography:** *Playfair Display* (headings) + *DM Sans* (body) — elegant editorial pairing
- **Layout:** CSS Grid for hero & about section; responsive single-column on mobile
- **Aesthetic:** Soft organic shapes, gradient overlays, generous whitespace

---

## 🧩 JavaScript Features Explained

```js
// 1. Dark Mode Toggle
// Dynamically updates CSS variables on :root for full theme switch

// 2. Typewriter Effect
// Cycles through an array of phrases with typing & deleting animation

// 3. Counter Animation
// Uses requestAnimationFrame + cubic ease-out for smooth number counting

// 4. Scroll Reveal (IntersectionObserver)
// Watches elements entering viewport and fades them in

// 5. Navbar Shrink
// Listens to window scroll and reduces nav padding dynamically
```

---

## 📸 Sections Overview

| Section | Description |
|---|---|
| **Navbar** | Fixed, blurred background, shrinks on scroll |
| **Hero** | Full-height, two-column layout with image & CTA |
| **About** | Mission paragraph + 3 interactive cards |
| **Stats Bar** | Animated counters — 5K+ Women, 12 Countries, etc. |
| **Footer** | Brand, navigation links, social links, copyright |

---

## 👩‍💻 Author

Built as part of the **She Can Foundation Frontend Development Internship Task**.

> *"Because She Can Change the World."* 🌍
