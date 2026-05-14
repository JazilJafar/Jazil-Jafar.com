# 🔐 Jazil's Portfolio Website

> A cyberpunk-themed personal portfolio for a 14-year-old junior web developer & ethical hacker.

---

## 👤 About

This is the personal portfolio of **Jazil** — a junior web developer and ethical hacker with a passion for building animated, interactive websites and exploring cybersecurity.

---

## 🚀 Features

- ⚡ **Animated Hero Section** — Staggered fade-in with a live terminal window
- 🖱️ **Custom Cursor** — Smooth lag cursor with hover expand effect
- 🟩 **Scanline + Grid Background** — Cyberpunk aesthetic with CSS-only effects
- 💀 **Glitch Effect** — Hover over the name for a glitch animation
- 📊 **Skill Bars** — Animated progress bars that trigger on scroll
- 🃏 **Project Cards** — Scroll-reveal cards with hover effects
- 📡 **Status Bar** — Sweeping light animation with key stats
- 📱 **Responsive** — Mobile-friendly layout

---

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── jazil-portfolio.css # All styles (link this in index.html)
└── README.md           # You are here
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure |
| CSS3 | Styling & animations |
| Vanilla JavaScript | Cursor, scroll animations, skill bars |
| Google Fonts | Orbitron, Share Tech Mono, Rajdhani |

---

## ⚙️ Setup

1. **Clone or download** the files
2. Make sure all 3 files are in the **same folder**
3. Open `index.html` in your browser — done!

> No build tools, no npm, no frameworks. Just pure HTML, CSS & JS.

---

## 🔗 Google Fonts Import

Make sure this is inside your `<head>` tag in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600&display=swap" rel="stylesheet">
```

---

## ✏️ Customization

| What you can change | Where |
|----------------|-------|
| Your name / bio | `index.html` → `#hero` and `#about` sections |
| Project details | `index.html` → `#projects` section |
| Skill percentages | `index.html` → `--target` values on `.skill-bar-fill` |
| Social links | `index.html` → `#contact` section |
| Colors | `jazil-portfolio.css` → `:root` variables |

### 🎨 Color Variables (easy to tweak)

```css
:root {
  --green: #00ff88;   /* Main accent */
  --cyan:  #00e5ff;   /* Secondary accent */
  --red:   #ff2d55;   /* Danger / highlight */
  --bg:    #050a0f;   /* Page background */
  --text:  #c8e6f0;   /* Body text */
  --muted: #4a7a8a;   /* Dimmed text */
}
```

---

## 🧠 Animations Used

| Animation | Effect |
|-----------|--------|
| `fadeUp` | Hero elements slide up on load |
| `pulse` | Background glow breathes in/out |
| `scanMove` | Scanlines scroll downward |
| `sweep` | Light sweeps across status bar |
| `blink` | Terminal cursor blinks |
| `barFill` | Skill bars fill on scroll |
| `glitch` | Name glitches on hover |

---

## 📜 License

This project is personal and open for learning purposes.  
Feel free to fork, modify, and make it your own! 🚀

---

> **Built with `</>`  and ☕ by Jazil — Age 14**
