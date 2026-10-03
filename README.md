# Persona 3 Reload — Pause Menu & Portfolio

> Pixel-perfect, authentic recreation of **Persona 3 Reload's Pause Menu** built with pure HTML5, modern vanilla CSS3, and JavaScript (ES6+).

---

## 🌟 Highlights & Features

- **Authentic Atlus Aesthetic**: Dynamic angled layouts, signature cyan & midnight blue color palette, SVG mask color-inversion, and geometric shattered glass banners.
- **Ultra-Low Latency Audio**: Web Audio API engine with `{ latencyHint: "interactive" }` and hardware-decoded audio buffers for instant sound feedback (<10ms).
- **Smooth 60+ FPS Performance**: Hardware-accelerated transitions via WAAPI (Web Animations API), GPU compositor-driven animations, and elimination of CPU blur rasterization.
- **Just-In-Time (JIT) Media Buffering**: Intelligent speculative video preloading on hover/selection to save bandwidth and prevent decode bottlenecks.
- **Dual-Mode Controls**:
  - **Full Keyboard Navigation**: `W` / `S` / `Up` / `Down` to navigate, `Enter` / `Space` / `A` / `B` to confirm, `Esc` / `Backspace` to return.
  - **Mouse / Touch Interactive**: Dynamic hover response, custom hitboxes, and tactile button controls.
- **Rich Subpages**:
  - **PROJECT**: Social Link-style project card stack.
  - **SKILLS**: Atlus stat rows with animated mastery bars.
  - **ABOUT**: Character showcase with profile narrative.
  - **CONTACT**: Themed phone messaging UI.

---

## 🛠️ Tech Stack

- **Markup**: Semantic HTML5 with accessibility ARIA landmarks.
- **Styling**: Vanilla CSS3 (Custom Properties, Flexbox, Skew/Matrix Transforms, WAAPI).
- **Logic**: Vanilla ES6+ JavaScript (Web Audio API, rAF tickers, DOM caching).
- **Fonts**: Rodin Pro, NewRodin Pro, Skip Std, Poppins.

---

## 🚀 Running Locally

You can serve the project using any local HTTP server:

```bash
# Using Python 3
python3 -m http.server 8080

# Or using Node.js npx serve
npx serve .
```

Open `http://localhost:8080` in your web browser.

---

## 👤 Author

**Ilham Ziqri**
- GitHub: [@Aiosssss](https://github.com/Aiosssss)
- Email: aiosssml@gmail.com
