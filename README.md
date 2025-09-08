<!--
   LichSV — Futurist/Robotic README
   Tone: neon / glass / circuits / motion-first
-->

<div align="center">

<img src="./assets/hero-motion.gif" alt="LichSV Futuristic Motion" width="960"/>

# 🤖 LichSV • Future Landing

[![Status](https://img.shields.io/badge/status-ONLINE-10b981?style=for-the-badge)](#)
[![Version](https://img.shields.io/badge/1.1.7-0ea5e9?style=for-the-badge&label=version)](#)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952b3?style=for-the-badge)](#)
[![A11y](https://img.shields.io/badge/A11y-AA-22c55e?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/MIT-111827?style=for-the-badge)](#license)

*Neon glass • micro-interactions • dark-by-design • zero-backend*

</div>

---

## 🧬 DNA
**LichSV** là landing page tải app lịch học cho sinh viên Việt Nam, thiết kế theo ngôn ngữ **neon-glass** và **robotic motion**.  
Tập trung: **nhanh**, **mượt**, **tương lai** — chạy thuần HTML/CSS/JS + CDN.

> **Motion-first**: hover nâng bề mặt (elevation), chip version phát sáng, toggle dark/light mượt 120ms, tooltip mềm 180ms.

---

## ⚙️ Tính năng (Core Systems)

- 🔎 **Instant Search**: lọc theo tên/ký hiệu (ICTU, FTU…) với debounce 120ms  
- 🌗 **Dark Engine**: auto theo `prefers-color-scheme` + toggle, nhớ LocalStorage  
- 🧊 **Glass UI**: blur 10px + viền mờ + shadow động (easing cubic-bezier)  
- 🧭 **Quick Actions**: Android / iOS / LMS / Telegram / Facebook  
- 🧰 **Resilient Logos**: lazy-load, tooltip, *graceful* khi lỗi ảnh  
- ♿ **Accessible**: aria-labels, focus ring, key nav thân thiện

---

## 🚀 60s Quick-Start

```sh
# Clone
git clone https://github.com/<your-org>/lichsv-landing.git
cd lichsv-landing

# Dev preview (1 trong 2)
python -m http.server 8080
# hoặc VS Code → Live Server

# Open
# http://localhost:8080
