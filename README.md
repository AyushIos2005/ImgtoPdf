# ImgtoPdf
📄 Image to PDF converter Android PWA — select up to 15 images, choose page size &amp; orientation, download PDF instantly. Works offline. No install required.
📄 Img → PDF — Android PWA

Convert images to PDF directly on your Android phone.  
No app store. No installation. Just open and use.

![PWA](https://img.shields.io/badge/PWA-Ready-6C63FF?style=flat-square)
![Max Pages](https://img.shields.io/badge/Max%20Pages-15-1A1A2E?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## ✨ Features

- 🖼️ Select up to **15 images** (JPG, PNG, WEBP, BMP)
- 📐 Page sizes — **A4, Letter, A5**
- 🔄 **Portrait & Landscape** orientation
- 📏 **Fit to page** toggle
- 📥 PDF downloads **instantly** to your device
- 📴 Works **offline** after first visit
- 📱 Installable on Android home screen with **"A" icon**

## 🚀 Live Demo

👉 **[https://imgTopdf.netlify.app](https://imgTopdf.netlify.app)**

## 📲 Install on Android

1. Open the live link in **Chrome** on your phone
2. Tap ⋮ menu → **"Add to Home Screen"**
3. Tap **Add**
4. The app icon appears on your home screen!

## 🛠️ Tech Stack

- **HTML / CSS / JavaScript** — no frameworks
- **jsPDF** — PDF generation in browser
- **Service Worker** — offline support
- **Web App Manifest** — installable PWA

## 📁 Project Structure
ImgToPDF_PWA/
├── index.html      → Main app UI + logic
├── manifest.json   → PWA config (name, icon, theme)
├── sw.js           → Service worker (offline cache)
├── icon-192.png    → App icon 192×192
└── icon-512.png    → App icon 512×512
