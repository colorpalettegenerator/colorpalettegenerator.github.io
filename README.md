# 🎨 Color Palette Generator

A modern, lightweight web application for generating harmonious color palettes with multiple export options. Built with vanilla HTML, CSS, and JavaScript — no dependencies, no build step.

**🌐 Live Application:** [colorpalettegenerator.github.io](https://colorpalettegenerator.github.io)

---

## ✨ Features

- **6 Color Harmony Modes**
  - Analogous
  - Complementary
  - Triadic
  - Tetradic
  - Monochromatic
  - Random

- **Interactive Controls**
  - Pick any base color via color picker
  - Lock individual colors to preserve them while regenerating
  - One-click copy of any color value
  - Toggle between horizontal and vertical palette layouts
  - Bilingual interface (Ukrainian / English) with a single-click toggle

- **Multiple Export Formats**
  - HEX
  - RGB
  - CSS variables (`:root` block)
  - JSON

- **User Experience**
  - Animated gradient background
  - Glassmorphism UI with smooth transitions
  - Auto-contrast text on swatches for readability
  - Toast notifications for feedback
  - Persistent state via `localStorage` — your palette and preferences survive reloads
  - Keyboard shortcut: press **Space** to regenerate the palette
  - Fully responsive design

---

## 🚀 Getting Started

### Online

Just visit the live application — no installation needed.

### Local

Clone the repository and open `index.html` in any browser. No build process, no dependencies — everything runs straight from the file.

---

## 🎯 How to Use

1. **Choose a harmony type** from the dropdown (Analogous, Complementary, etc.)
2. **Pick a base color** with the color picker — the palette regenerates instantly
3. **Lock 🔒 colors** you want to keep, then regenerate to vary only the unlocked ones
4. **Copy individual colors** with the 📋 button on each swatch
5. **Toggle orientation** between horizontal and vertical layouts with the icon button
6. **Switch language** between Ukrainian (UA) and English (EN) with one click
7. **Export** your palette in HEX, RGB, CSS, or JSON format
8. Press **Space** anywhere to generate a fresh palette

---

## 🌍 Internationalization

The interface supports two languages out of the box:

- 🇺🇦 **Ukrainian** (Українська) — default
- 🇬🇧 **English**

The active language is remembered between sessions.

---

## 🛠️ Tech Stack

- **HTML5** — semantic markup with SEO meta tags and Open Graph
- **CSS3** — custom properties, gradients, backdrop-filter, animations
- **Vanilla JavaScript** — no frameworks, no dependencies
- **SVG favicon** — inlined as data URI

---

## 📂 Project Structure

```
colorpalettegenerator.github.io/
├── index.html       # Single-file application (HTML + CSS + JS)
└── README.md
```

Everything lives in one file for maximum portability and simplicity.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Ideas for contributions:
- Additional harmony algorithms
- More export formats (SCSS, Tailwind config, ASE, etc.)
- Image-based palette extraction
- Color blindness simulation
- Shareable palette URLs
- Additional language translations

---

## 📄 License

MIT License

---

Made with 🎨 for designers, developers, and color enthusiasts.
