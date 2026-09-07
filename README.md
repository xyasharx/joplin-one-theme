<div align="center">

# 🎨 Joplin One Theme

**A modern, dual-mode (One Dark / One Light) theme for [Joplin](https://joplinapp.org) featuring an Obsidian-style scrollable Mermaid engine and first-class Persian/RTL typography.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Joplin Compatibility](https://img.shields.io/badge/Joplin-v2.8%2B-blue.svg)](https://joplinapp.org)
[![Theme Support](https://img.shields.io/badge/Mode-Auto%20Dark%20%2F%20Light-61afef.svg)](#)
[![RTL & LTR](https://img.shields.io/badge/Direction-LTR%20%26%20RTL-success.svg)](#)

[English](#-overview) • [راهنمای فارسی](#-راهنمای-فارسی-persian-guide) • [Installation](#-installation) • [Mermaid Fix](#-the-mermaid-scroll-engine)

</div>

---

## ✨ Overview

**Joplin One Theme** brings the timeless elegance of Atom's **One Dark** and **One Light** color palettes to Joplin, packed with smart layout optimizations for everyday productivity:

- 🌗 **Automatic Dark / Light Mode:** Seamlessly adapts to your system theme (`prefers-color-scheme`).
- 📊 **Obsidian-Style Mermaid Engine:** Large, wide, or complex diagrams never get squashed or illegible; they remain crisp and scrollable inside an unconstrained horizontal viewport.
- 🌍 **Dual Flavors (LTR & RTL):** 
  - Standard global edition for English/LTR languages.
  - Dedicated Persian/Arabic edition powered by the gorgeous **Vazirmatn** font with zero punctuation-jump bugs.
- 📱 **Mobile & Tablet Optimized:** Compact paddings, touch-friendly horizontal swipe for tables and flowcharts.
- 🖨️ **Clean Print & PDF Export:** Strips dark backgrounds and scrollbars when generating documents.

---

## 🚀 The Mermaid Scroll Engine

> **Why this theme?** In default Joplin, complex Mermaid flowcharts either stretch vertically into gigantic blocks or shrink down horizontally until the text is completely microscopic.

**Joplin One Theme solves this natively without plugins:**
- Narrow/Vertical diagrams (`flowchart TD`) remain centered and compact.
- Wide/Horizontal diagrams (`flowchart RL / LR`, Sequence, Gantt) render at **100% native resolution** with an elegant horizontal scrollbar.
- Labels, nodes, and borders maintain crisp typography and never get cut off.

---

## 📦 File Variants

| File | Direction | Primary Font | Best For |
| :--- | :--- | :--- | :--- |
| **`userstyle.css`** | **LTR** (Left-to-Right) | System Native (`Segoe UI`, `-apple-system`, `Roboto`) | English, European, & global languages |
| **`userstyle-rtl.css`** | **RTL** (Right-to-Left) | **Vazirmatn** (وزیرمتن) | Persian (فارسی), Arabic, & RTL notes |

---

## 🛠️ Installation

### Desktop (Windows, macOS, Linux)

1. Download or copy the contents of your chosen file:
   - For English/Global notes: copy **`userstyle.css`**
   - For Persian/RTL notes: copy **`userstyle-rtl.css`**
2. In Joplin, go to:
   - **Tools** → **Options** (or **Joplin** → **Preferences** on macOS)
   - Click on **Appearance** in the sidebar.
   - Click **Show Advanced Settings**.
   - Click **Custom stylesheet for rendered Markdown** (this opens your local `userstyle.css`).
3. Paste the code into the file and save it.
4. **Completely restart Joplin** (*File → Quit*, then reopen) to apply the stylesheet.

### Mobile (Android / iOS)
Using the Import Local CSS plugin or plugins with similar functionality.

---

## 🇮🇷 راهنمای فارسی (Persian Guide)

این تم به طور اختصاصی برای کاربران فارسی‌زبان بهینه‌سازی شده تا تمام مشکلات رایج Markdown در زبان‌های راست‌چین برطرف شود:

### ویژگی‌های نسخه فارسی (`userstyle-rtl.css`):
- **فونت وزیرمتن (Vazirmatn):** لود فونت استاندارد وب برای نمایش چشم‌نواز حروف و اعراب.
- **راست‌چین کامل و اصولی:** رفع به‌هم‌ریختگی پرانتزها، علامت سوال، لیست‌ها، جداول و خطوط سرفصل‌ها.
- **ایزوله‌سازی کدهای برنامه‌نویسی:** بلوک‌های کد (`pre`) و کدهای درون‌خطی (`code`) به صورت چپ‌چین (LTR) و با فونت‌های مونو‌اسپیس خوانا باقی می‌مانند.
- **موتور اسکرول دیاگرام‌های Mermaid:** نمودارهای شلوغ و متون درون نودها هرگز ریز نمی‌شوند و درون یک کادر استاندارد به زیبایی اسکرول می‌خورند.

### نحوه نصب نسخه فارسی:
1. محتویات فایل **`userstyle-rtl.css`** را کپی کنید.
2. در جاپلین از منوی بالا به مسیر **ابزارها (Tools)** ← **تنظیمات (Options)** ← **ظاهر (Appearance)** بروید.
3. روی **نمایش تنظیمات پیشرفته (Show Advanced Settings)** کلیک کرده و گزینه **Custom stylesheet for rendered Markdown** را بزنید.
4. متن کپی‌شده را در فایل بازشده جایگزین و ذخیره کنید.
5. برنامه جاپلین را یک‌بار **کاملاً ببندید (Quit)** و مجدداً باز کنید.

---

## 🎨 Color Palette Preview

| Role | One Light | One Dark |
| :--- | :--- | :--- |
| **Background** | `#fafafa` | `#282c34` |
| **Foreground** | `#383a42` | `#abb2bf` |
| **H1 (Red)** | `#e45649` | `#e06c75` |
| **H2 / Links (Blue)** | `#4078f2` | `#61afef` |
| **H3 (Green)** | `#50a14f` | `#98c379` |
| **H4 (Purple)** | `#a626a4` | `#c678dd` |
| **H5 (Cyan)** | `#0184bc` | `#56b6c2` |
| **H6 (Orange)** | `#986801` | `#d19a66` |

---

## 🤝 Contributing & Feedback

Suggestions, bug reports, and pull requests are warmly welcome! If you encounter any styling glitch or have ideas for improvements, please feel free to open an [Issue](../../issues).

⭐ **If you find this theme useful, please star this repository on GitHub!**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
