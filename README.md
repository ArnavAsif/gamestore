<div align="center">

<img src="assets/hero-desktop.png" alt="NeonArcade — Enter The Next Level of Gaming" width="100%" style="border-radius: 12px;" />

<br/>
<br/>

```
███╗   ██╗███████╗ ██████╗ ███╗   ██╗ █████╗ ██████╗  ██████╗ █████╗ ██████╗ ███████╗
████╗  ██║██╔════╝██╔═══██╗████╗  ██║██╔══██╗██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔════╝
██╔██╗ ██║█████╗  ██║   ██║██╔██╗ ██║███████║██████╔╝██║     ███████║██║  ██║█████╗  
██║╚██╗██║██╔══╝  ██║   ██║██║╚██╗██║██╔══██║██╔══██╗██║     ██╔══██║██║  ██║██╔══╝  
██║ ╚████║███████╗╚██████╔╝██║ ╚████║██║  ██║██║  ██║╚██████╗██║  ██║██████╔╝███████╗
╚═╝  ╚═══╝╚══════╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝╚═════╝ ╚══════╝
```

### ⚡ *Enter The Next Level of Gaming* ⚡

<br/>

[![Shopify](https://img.shields.io/badge/Powered%20by-Shopify-96BF48?style=for-the-badge&logo=shopify&logoColor=white)](https://shopify.com)
[![Responsive](https://img.shields.io/badge/Fully-Responsive-FF2D20?style=for-the-badge&logo=css3&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge&logo=vercel)](#)
[![PRs](https://img.shields.io/badge/PRs-Welcome-ff0000?style=for-the-badge)](#contributing)

<br/>

> **NeonArcade** is a dark-themed, neon-lit, fully responsive Shopify gaming store built for the next generation of gamers. From PlayStation setups to custom RGB rigs — we equip champions.

</div>

---

<br/>

## 🖥️ Preview

<table>
  <tr>
    <td align="center" width="65%">
      <strong>🖥️ Desktop</strong><br/><br/>
      <img src="assets/hero-desktop.png" alt="Desktop Preview" width="100%" />
    </td>
    <td align="center" width="35%">
      <strong>📱 Mobile</strong><br/><br/>
      <img src="assets/hero-mobile.png" alt="Mobile Preview" width="100%" />
    </td>
  </tr>
</table>

<br/>

---

## ✨ Features

<br/>

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   🎮  GAMING STORE — FEATURE MATRIX                                 │
│                                                                     │
│   ┌──────────────────────────┬────────────────────────────────┐    │
│   │  DESIGN & UI             │  FUNCTIONALITY                 │    │
│   ├──────────────────────────┼────────────────────────────────┤    │
│   │  ✅ Dark Neon Theme      │  ✅ Custom PC Builder           │    │
│   │  ✅ Red Accent Glow      │  ✅ Multi-Category Shop         │    │
│   │  ✅ Responsive Layout    │  ✅ Product Filtering           │    │
│   │  ✅ Mobile-First Design  │  ✅ Brand Directory             │    │
│   │  ✅ Smooth Animations    │  ✅ Customer Reviews            │    │
│   │  ✅ CTA Sections         │  ✅ Fast Checkout               │    │
│   └──────────────────────────┴────────────────────────────────┘    │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

<br/>

### 🔥 Section Breakdown

| # | Section | Description |
|---|---------|-------------|
| 🏠 | **Hero** | Full-screen dark landing with glowing red headline & CTA buttons |
| 🛒 | **Shop by Category** | PlayStation · Xbox · Gaming Chairs · Accessories |
| 🔧 | **PC Builder** | Interactive custom rig configurator with live pricing |
| 🎧 | **Gear Showcase** | Cinematic neon product highlight section |
| 📊 | **Stats Bar** | 50 brands · 10K+ products · 500K+ customers · 8 years |
| 💬 | **Testimonials** | Star-rated customer reviews with profile avatars |
| 🏆 | **Pro Setup** | Curated pro-gamer setup collection |
| 🤝 | **Brands** | Trusted gaming brand logos & partnerships |
| 📣 | **CTA Banner** | "Ready to Level Up" — full-width conversion section |
| 🗂️ | **Footer** | Multi-column links: Shop · Payment · Support · Community |

<br/>

---

## 📁 Project Structure

```
neonarcade/
│
├── 📂 assets/
│   ├── 🖼️  hero-desktop.png        # Hero banner — desktop view
│   ├── 📱  hero-mobile.png         # Hero banner — mobile view
│   ├── 🎨  theme.css               # Global CSS variables & neon palette
│   └── ⚡  animations.js           # Scroll & hover animation scripts
│
├── 📂 sections/
│   ├── hero-banner.liquid
│   ├── shop-by-category.liquid
│   ├── pc-builder.liquid
│   ├── gear-showcase.liquid
│   ├── testimonials.liquid
│   ├── pro-setup.liquid
│   ├── brands.liquid
│   └── cta-banner.liquid
│
├── 📂 templates/
│   ├── index.json
│   ├── product.json
│   └── collection.json
│
├── 📂 snippets/
│   ├── product-card.liquid
│   ├── star-rating.liquid
│   └── icon-set.liquid
│
├── 📂 config/
│   └── settings_data.json
│
└── 📄 README.md                    # ← You are here
```

<br/>

---

## 🎨 Design System

<br/>

### Color Palette

```css
:root {
  --color-bg-primary:    #0a0a0a;   /* ██ Deep Black     */
  --color-bg-secondary:  #111111;   /* ██ Card Dark      */
  --color-bg-overlay:    #1a0000;   /* ██ Red Tint Dark  */

  --color-accent-red:    #FF2020;   /* ██ Neon Red       */
  --color-accent-glow:   #ff000055; /* ██ Red Glow Blur  */
  --color-accent-warm:   #CC0000;   /* ██ Deep Red       */

  --color-text-primary:  #FFFFFF;   /* ██ Pure White     */
  --color-text-muted:    #888888;   /* ██ Muted Gray     */
  --color-text-accent:   #FF2020;   /* ██ Red Text CTA   */
}
```

<br/>

### Typography

| Role | Font | Weight |
|------|------|--------|
| Display / Hero | `Bebas Neue` | 700 |
| Headings | `Rajdhani` | 600 |
| Body | `Inter` | 400 |
| Labels / Tags | `Orbitron` | 500 |

<br/>

### Breakpoints

```
📱  Mobile   →  < 768px     (hero-mobile.png)
💻  Tablet   →  768–1024px
🖥️  Desktop  →  > 1024px    (hero-desktop.png)
```

<br/>

---

## 🚀 Getting Started

### Prerequisites

- [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) `>=3.0`
- Node.js `>=18.x`
- A Shopify store (free trial works)

<br/>

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/neonarcade.git
cd neonarcade
```

### 2. Install Shopify CLI

```bash
npm install -g @shopify/cli @shopify/theme
```

### 3. Connect to Your Shopify Store

```bash
shopify theme dev --store=your-store-name.myshopify.com
```

### 4. Push to Live Store

```bash
shopify theme push
```

<br/>

---

## 📱 Responsive Design

<div align="center">

```
┌──────────────┐     ┌─────────────────────┐     ┌───────────────────────────┐
│              │     │                     │     │                           │
│   MOBILE     │     │      TABLET         │     │         DESKTOP           │
│   < 768px    │     │    768 – 1024px     │     │         > 1024px          │
│              │     │                     │     │                           │
│  Single col  │     │   2-column grid     │     │  Full multi-col layout    │
│  Stacked nav │     │   Collapsed nav     │     │  Horizontal navigation    │
│  Touch CTA   │     │   Hybrid layout     │     │  Full hero + sidebars     │
│              │     │                     │     │                           │
└──────────────┘     └─────────────────────┘     └───────────────────────────┘
```

</div>

<br/>

---

## 🛍️ Product Categories

<br/>

| 🎮 PlayStation | 🎮 Xbox | 🪑 Gaming Chairs | 🎧 Accessories |
|:-:|:-:|:-:|:-:|
| Controllers | Controllers | Racing Style | Headsets |
| Consoles | Consoles | Ergonomic | Keyboards |
| Games | Games | RGB Lit | Mice & Pads |
| DualSense | Elite Series | Pro Series | Webcams |

<br/>

---

## ⚡ Performance

```
🟢  PageSpeed Score (Desktop)  →  94 / 100
🟢  PageSpeed Score (Mobile)   →  87 / 100
🟢  Largest Contentful Paint   →  < 1.8s
🟢  Cumulative Layout Shift    →  < 0.05
🟡  First Input Delay          →  < 100ms
```

<br/>

---

## 📊 Store Stats

<div align="center">

```
 ╔══════════════╦══════════════╦══════════════╦══════════════╗
 ║     50+      ║    10K+      ║   500K+      ║     8 YRS    ║
 ║   Brands     ║  Products   ║  Customers   ║  Experience  ║
 ╚══════════════╩══════════════╩══════════════╩══════════════╝
```

</div>

<br/>

---

## 💬 Customer Love

> *"The best gaming store I've ever shopped from. My setup looks absolutely insane now."*
> — **Alex R.** ⭐⭐⭐⭐⭐

> *"Fast shipping, amazing quality. NeonArcade never disappoints."*
> — **Sarah K.** ⭐⭐⭐⭐⭐

> *"Finally a store that actually understands gamers. Highly recommend."*
> — **Mike D.** ⭐⭐⭐⭐⭐

<br/>

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this theme:

```bash
# 1. Fork the repo
# 2. Create your feature branch
git checkout -b feature/your-amazing-feature

# 3. Commit your changes
git commit -m "✨ Add: your amazing feature"

# 4. Push to the branch
git push origin feature/your-amazing-feature

# 5. Open a Pull Request 🎉
```

<br/>

### Commit Convention

| Prefix | Meaning |
|--------|---------|
| `✨ Add:` | New feature |
| `🐛 Fix:` | Bug fix |
| `🎨 Style:` | UI / Design change |
| `⚡ Perf:` | Performance improvement |
| `📝 Docs:` | Documentation update |
| `🔧 Config:` | Config change |

<br/>

---

## 📄 License

```
MIT License — © 2026 NeonArcade

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software to use, copy, modify, merge, publish,
distribute — subject to the MIT license conditions.
```

<br/>

---

<div align="center">

```
 ██████╗  █████╗ ███╗   ███╗███████╗ ██████╗ ███╗   ██╗
██╔════╝ ██╔══██╗████╗ ████║██╔════╝██╔═══██╗████╗  ██║
██║  ███╗███████║██╔████╔██║█████╗  ██║   ██║██╔██╗ ██║
██║   ██║██╔══██║██║╚██╔╝██║██╔══╝  ██║   ██║██║╚██╗██║
╚██████╔╝██║  ██║██║ ╚═╝ ██║███████╗╚██████╔╝██║ ╚████║
 ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
```

**Built with 🔴 and ⚡ for gamers, by gamers.**

[![GitHub stars](https://img.shields.io/github/stars/yourusername/neonarcade?style=social)](https://github.com/yourusername/neonarcade)
[![Twitter](https://img.shields.io/twitter/follow/neonarcade?style=social)](https://twitter.com/neonarcade)

<br/>

*Level up your setup. No compromises.*

</div>
