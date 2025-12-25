# ✨ Resume Storage & Tracking System — README

<!-- Hero SVG animation (renders on GitHub README) -->
<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="xMidYMid meet">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0%" stop-color="#6C63FF"/>
      <stop offset="100%" stop-color="#00C2FF"/>
    </linearGradient>
    <radialGradient id="rg" cx="50%" cy="30%" r="80%">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.12"/>
      <stop offset="100%" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>
    <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="12" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="1200" height="220" fill="#071026" rx="12"/>

  <!-- floating 3D-ish card group -->
  <g transform="translate(80,32)">
    <g id="card" transform="translate(0,0)">
      <rect x="0" y="18" rx="14" width="420" height="140" fill="url(#g1)" opacity="0.12"/>
      <rect x="8" y="8" rx="12" width="404" height="124" fill="#0b1220" stroke="rgba(255,255,255,0.04)"/>
      <g fill="#fff" font-family="Segoe UI, Roboto, Helvetica, Arial">
        <text x="24" y="44" font-size="18" fill="#fff">Resume Storage & Tracking System</text>
        <text x="24" y="74" font-size="12" fill="#9aa8c3">Store, preview, and analyze resumes — animated demo</text>
      </g>
      <!-- animated 3D-ish rotating cube (SVG simulated) -->
      <g transform="translate(320,14) scale(0.9)">
        <polygon points="0,18 22,6 44,18 22,30" fill="#6C63FF">
          <animateTransform attributeName="transform" type="rotate" from="0 22 18" to="360 22 18" dur="6s" repeatCount="indefinite"/>
        </polygon>
        <polygon points="44,18 22,30 22,60 44,48" fill="#00C2FF" opacity="0.95">
          <animateTransform attributeName="transform" type="rotate" from="360 22 36" to="0 22 36" dur="8s" repeatCount="indefinite"/>
        </polygon>
      </g>
    </g>

    <!-- moving particle background -->
    <g transform="translate(0,160)">
      <circle cx="0" cy="0" r="3" fill="#6C63FF"><animate attributeName="cx" dur="6s" values="0;180;360;540;0" repeatCount="indefinite"/></circle>
      <circle cx="40" cy="-8" r="2.5" fill="#00C2FF" opacity="0.9"><animate attributeName="cx" dur="5s" values="40;220;400;580;40" repeatCount="indefinite"/></circle>
      <circle cx="100" cy="-4" r="2" fill="#9AD1FF" opacity="0.7"><animate attributeName="cx" dur="7s" values="100;280;460;640;100" repeatCount="indefinite"/></circle>
    </g>
  </g>

  <g transform="translate(560,38)">
    <text x="0" y="36" font-family="Segoe UI, Roboto" font-size="28" fill="url(#g1)">Live Demo</text>
    <a href="https://resumestorage.vercel.app/" target="_blank">
      <text x="0" y="72" font-size="14" fill="#9aa8c3">https://resumestorage.vercel.app/</text>
    </a>
  </g>

  <!-- glow layer -->
  <rect x="0" y="0" width="1200" height="220" fill="url(#rg)" opacity="0.14"/>
</svg>

<p align="center">
  <a href="https://resumestorage.vercel.app/"><img src="https://img.shields.io/badge/Live-Demo-brightgreen" alt="live demo"></a>
  <a href="#features"><img src="https://img.shields.io/badge/Status-Prototype-orange.svg" alt="status"></a>
  <a href="https://github.com/Abhishek79958/Resume-Storage-Tracking-System/actions"><img src="https://img.shields.io/github/actions/workflow/status/Abhishek79958/Resume-Storage-Tracking-System/ci.yml?branch=main" alt="ci"></a>
  <a href="https://resumestorage.vercel.app/"><img src="https://img.shields.io/badge/Visit-Vercel-purple" alt="vercel"/></a>
</p>

---

## 🔮 Overview

Yeh repository ek polished, animated aur visually-rich README ke saath static frontend prototype hai jo resumes ko store/track visualize karne ke liye banaaya gaya hai. Aapko milta hai:
- Animated hero header (complex SVG animation)
- Direct live demo link deployed on Vercel
- Demo GIF placeholder (added below)
- Lottie animation support & examples

---

## 🔗 Live Deployment

Project is deployed on Vercel — open the live site here:

- https://resumestorage.vercel.app/

---

## Demo (local copy)

![Demo GIF - optimized local copy](./demo.gif)

---

## 🎆 Animated Gallery (curated collection)

Below is a curated, attractive gallery of GIFs, 3D loops, anime-style assets and stickers sourced from public collections (Anmol-Baranwal / mdazfar2). These are hotlinked to their original locations — credits shown under each row. Use them as README decoration and to make the project page more engaging.

<!-- Row: hero / large highlight GIFs -->
<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/213866269-5d00981c-7c98-46d7-8a8e-16f462f15227.gif" width="360" alt="highlight-loop" />

</div>

**Social / Party Parrots**

<div align="center">
<img src="https://cultofthepartyparrot.com/parrots/hd/githubparrot.gif" width="80" />
<img src="https://cultofthepartyparrot.com/parrots/hd/opensourceparrot.gif" width="80" />
<img src="https://cultofthepartyparrot.com/parrots/hd/levitationparrot.gif" width="80" />
<img src="https://cultofthepartyparrot.com/parrots/hd/spinningparrot.gif" width="80" />
</div>

**Animated Social Icons & Avatars**

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/235294002-8aafea24-3179-45af-91d9-412ad7ff5359.gif" width="120" />
<img src="https://user-images.githubusercontent.com/74038190/235294007-de4f6f..." width="120" />
<img src="https://user-images.githubusercontent.com/74038190/235294008-ed8de58b-d4d0-4790-aa81-a39fdc8a1e50.gif" width="120" />
</div>

**Coding / Work Vibes (3D-ish loops, scenes)**

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212746035-d5c61762-973c-44c0-aec7-887f3b7690e3.gif" width="260" />
<img src="https://user-images.githubusercontent.com/74038190/212747919-84b68444-0d81-46db-a338-7ec50e9dd4cd.gif" width="260" />
<img src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif" width="260" />
</div>

**Pixel / Retro / Game Loops**

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="320" />
<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="320" />
</div>

**Emojis & Stickers (fun)**

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/216120974-24a76b31-7f39-41f1-a38f-b3c1377cc612.png" width="120" />
<img src="https://user-images.githubusercontent.com/74038190/216121919-60befe4d-11c6-4227-8992-35221d12ff54.png" width="120" />
<img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="120" />
</div>

---

## 💡 Quick Start (Local)

1. Clone repo:

```bash
git clone https://github.com/Abhishek79958/Resume-Storage-Tracking-System.git
cd Resume-Storage-Tracking-System
```

2. Open locally (simple):
- Directly open `index.html` in browser (for static demo)

3. Serve using a lightweight HTTP server (recommended):

```bash
python3 -m http.server 8000
# or
npx http-server -p 8000
```

