<!-- 
   README.md — LichSV Futuristic Landing Page
   Phong cách: Cyberpunk / Robotic / Futuristic
   Tác giả: quanit206
-->

<div align="center">

# 🤖✨ LichSV — Landing Page Sinh Viên 4.0 ✨🤖

<img src="./assets/future-banner.gif" alt="Futuristic Banner" width="100%"/>

[![Trạng thái](https://img.shields.io/badge/status-ONLINE-10b981?style=for-the-badge&logo=vercel&logoColor=white)](#)
[![Phiên bản](https://img.shields.io/badge/version-1.1.7-0ea5e9?style=for-the-badge&logo=github)](#)
[![Xây dựng bằng](https://img.shields.io/badge/Bootstrap-5.3.3-7952b3?style=for-the-badge&logo=bootstrap)](#)
[![Giấy phép](https://img.shields.io/badge/license-MIT-111827?style=for-the-badge)](#license)
[![Made for Students](https://img.shields.io/badge/for-students-2563eb?style=for-the-badge&logo=graduation-cap)](#)

⚡ *Landing page tải ứng dụng LichSV với thiết kế neon-glass, hiệu ứng chuyển động và phong cách robot tương lai.* ⚡

</div>

---

# 🧬 Giới thiệu

**LichSV** không chỉ là một landing page thông thường. Nó được thiết kế để:  

- Hiện đại, sống động với **glassmorphism** và **gradient neon**  
- Có **chuyển động dạng robot**: hover bay lên, chip phát sáng, tooltip mượt  
- Hỗ trợ **dark mode tự động**  
- Chạy **siêu nhanh** (thuần HTML/CSS/JS, không backend)  
- Tối ưu cho **sinh viên**: tải app, tìm trường, tham gia cộng đồng  

---

# ✨ Tính năng nổi bật

## 🔎 Tìm kiếm tức thì
- Nhập ký hiệu hoặc tên trường (ví dụ: `ICTU`, `FTU`)  
- Lọc kết quả **theo thời gian thực**  
- Badge hiển thị số trường khớp  

## 🌗 Dark Mode
- Tự động nhận diện theme hệ thống  
- Nút toggle với icon moon/sun đổi mượt  
- Lưu trạng thái trong `localStorage`  

## 🧊 Giao diện Glass + Neon
- Nền gradient + blob động  
- Card có hiệu ứng **mờ ảo** (blur 10px)  
- Viền bo mềm 18px, shadow nổi  

## 🧭 Liên kết nhanh
- **Android**: tải `.apk` trực tiếp  
- **iOS**: App Store  
- **Cộng đồng**: Telegram, Facebook Group, LMS ICTU  

## ⚡ Hiệu ứng Robot
- Hover → card bay lên `translateY(-2px)`  
- Tooltip xuất hiện êm ái  
- Nút nhấn → rung nhẹ, phát sáng như LED  

---

# 🎥 Motion Spec (Mô tả chuyển động)

```css
/* Hover card */
.logo-item:hover {
  transform: translateY(-2px) scale(1.01);
  box-shadow: 0 8px 18px rgba(2,8,23,.25);
  transition: all .18s cubic-bezier(.4,.0,.2,1);
}

/* Nút toggle dark mode */
.mode-btn {
  transition: background .12s ease, transform .12s ease;
}
.mode-btn:active {
  transform: scale(.95);
}
