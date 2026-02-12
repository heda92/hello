# Hello World 🎨

A stunning, modern landing page with smooth animations and dynamic theming, inspired by Apple's clean aesthetic.

![Demo](https://img.shields.io/badge/demo-live-brightgreen) ![Bun](https://img.shields.io/badge/bun-latest-orange) ![License](https://img.shields.io/badge/license-MIT-blue)

## ✨ Features

- **Smooth Animations** - Buttery fade-in effects with cubic-bezier easing
- **Confetti Celebration** - Canvas-based confetti animation on page load
- **Dynamic Theming** - Randomly selects from 4 Catppuccin color palettes (Latte, Frappé, Macchiato, Mocha)
- **Random Designer Jokes** - 7 different witty designer jokes that change on each page load
- **Floating Background** - Subtle animated shapes creating an elegant atmosphere
- **Fully Responsive** - Fluid typography and layout that works on all devices
- **Zero Dependencies** - Pure HTML, CSS, and vanilla JavaScript
- **Single File** - Everything in one `index.html` for maximum portability

## 🎭 Design Philosophy

Built with a minimalist approach focusing on:
- Clean, Apple-inspired aesthetics
- Generous whitespace
- Smooth, natural animations
- System fonts for optimal performance
- Accessibility and responsiveness

## 🚀 Quick Start

### Prerequisites

- [Bun](https://bun.sh/) installed on your machine

### Installation

```bash
# Clone the repository
git clone https://github.com/heda92/hello.git
cd hello

# Run the development server
bun dev

# Or run the production server
bun start
```

The site will be available at `http://localhost:5000`

## 🎨 Color Palettes

This project uses the beautiful [Catppuccin](https://catppuccin.com/) color scheme with four flavors:

- **Latte** - Light theme with warm tones
- **Frappé** - Cool, medium-dark theme
- **Macchiato** - Rich, darker theme
- **Mocha** - Deep, darkest theme

Each page load randomly selects a flavor for a fresh experience!

## 📁 Project Structure

```
hello/
├── index.html      # Main landing page with embedded CSS & JS
├── server.js       # Bun production server
├── package.json    # Project configuration
└── README.md       # You are here!
```

## 🛠️ Scripts

- `bun dev` - Start development server with hot reload
- `bun start` - Start production server

## 🎯 Technical Highlights

- **Canvas Animations** - Custom confetti and floating shapes using HTML5 Canvas
- **CSS Animations** - Smooth fade-in effects with cubic-bezier timing
- **Responsive Typography** - Uses CSS `clamp()` for fluid font sizing
- **System Fonts** - `system-ui` for optimal native look and performance
- **Zero Build Step** - Works directly in the browser

## 🌐 Live Demo

Check out the live demo: [https://heda92.github.io/hello/](https://heda92.github.io/hello/)

Refresh the page to see different color palettes and jokes!

## 📝 License

MIT

## 🤝 Contributing

Feel free to open issues or submit pull requests!

---

Made with ❤️ and confetti
