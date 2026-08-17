# 🎧 AURA Pro — Sound Redefined

> **Summit-Fi luxury wireless headphone experience built with Next.js 16, React 19, Tailwind CSS v4, and interactive Apple-style 60fps canvas frame scrubbing.**

[![Next.js](https://img.shields.io/badge/Next.js-16.3-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=flat-square&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#license)

---

## ✨ Overview

**AURA Pro** is a product landing website engineered to showcase luxury, audiophile-grade wireless headphones. It combines high-end editorial aesthetics with dynamic 3D scroll-driven video frame sequences, fluid micro-interactions, custom interactive cursors, and acoustic engineering breakdowns.

### 🌟 Key Highlights

- 🎞️ **Interactive Scroll Canvas Engine**: 225 high-resolution frame preloader and canvas renderer that smoothly rotates and inspects the headphones as the user scrolls.
- 🎨 **Bespoke Luxury Aesthetics**: Dark-mode glassmorphism, warm gold/copper gradients (`#c8956c`), and smooth micro-animations.
- 🖱️ **Custom Dynamic Cursor**: Context-aware cursor with magnetic hover states over buttons, links, and cards.
- ⚡ **Interactive Finishes Selector**: Live color switcher (Cognac Tan, Midnight Obsidian, Natural Oyster) with interactive preorder checkout card.
- 📊 **Animated Specs & Metrics**: Intersection-observer driven counters showcasing drivers, frequency response, battery life, and noise cancellation stats.
- 📱 **Fully Responsive Design**: Optimized layout across ultra-wide desktop monitors, laptops, tablets, and smartphones.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 16 (App Router)](https://nextjs.org/)
- **Core Library**: [React 19](https://react.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) + Custom CSS Glassmorphism
- **Icons**: [Lucide React](https://lucide.dev/)
- **UI Primitives**: Radix UI Slot, Class Variance Authority (`cva`), `tailwind-merge`

---

## 📁 Project Structure

```text
Headphones website/
├── aura-headphones/              # Next.js application root
│   ├── public/
│   │   └── frames/               # 225 sequence frames for 3D scroll animation
│   ├── src/
│   │   ├── app/
│   │   │   ├── globals.css       # Design tokens, variables & keyframe animations
│   │   │   ├── layout.tsx        # App layout and OpenGraph SEO metadata
│   │   │   └── page.tsx          # Full landing page with all product sections
│   │   ├── components/
│   │   │   ├── ScrollCanvas.tsx  # Optimized canvas 2D frame-scrubbing engine
│   │   │   └── ui/               # Reusable UI primitives
│   │   └── lib/                  # Utilities (cn helper, etc.)
│   ├── next.config.ts            # Next.js configuration
│   ├── package.json              # Project scripts & dependencies
│   ├── postcss.config.mjs        # PostCSS configuration
│   └── tsconfig.json             # TypeScript configuration
├── ezgif-223cea20158be040-jpg/   # Raw frame assets repository
└── README.md                     # Documentation
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (version 18.18 or higher recommended) and `npm` installed.

### Installation

1. Clone or navigate to the repository:
   ```bash
   cd "Headphones website"
   ```

2. Navigate into the application folder:
   ```bash
   cd aura-headphones
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Running Locally

Start the local development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### Building for Production

To create an optimized production build:

```bash
npm run build
npm run start
```

---

## 🎧 Product Features Highlighted in UI

| Feature | Specification |
| :--- | :--- |
| **Acoustic Driver** | 40mm Beryllium Composite Vapor Driver |
| **Frequency Response** | 4Hz – 40,000Hz (Hi-Res Audio Certified) |
| **Active Noise Cancelling** | 6-Microphone Adaptive Hybrid ANC (98% reduction) |
| **Wireless Protocol** | Bluetooth 5.3 + LE Audio (LDAC, aptX Adaptive) |
| **Battery Life** | 40 hours continuous playback (5-hr playback with 10-min fast charge) |
| **Materials** | Hand-stitched Italian calfskin, 6061-T6 CNC billet aluminum |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
