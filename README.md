<div align="center">

# 🎨 Joplin One Theme

**A modern, dual-mode (One Dark / One Light) theme for [Joplin](https://joplinapp.org) featuring an Obsidian-style scrollable Mermaid engine, mobile-first typography, and first-class Persian/RTL typography.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Joplin Compatibility](https://img.shields.io/badge/Joplin-v2.8%2B-blue.svg)](https://joplinapp.org)
[![Theme Support](https://img.shields.io/badge/Mode-Auto%20Dark%20%2F%20Light-61afef.svg)](#)
[![Direction](https://img.shields.io/badge/Direction-LTR%20%26%20RTL-success.svg)](#)
[![Mobile Optimized](https://img.shields.io/badge/Mobile-Optimized%20Typography-orange.svg)](#)

[English](#-overview) • [راهنمای فارسی](#-راهنمای-فارسی-persian-guide) • [Installation](#️-installation) • [Mobile Features](#-mobile--responsive-typography) • [Mermaid Fix](#-the-mermaid-scroll-engine)

</div>

---

## ✨ Overview

**Joplin One Theme** brings the timeless elegance of Atom's **One Dark** and **One Light** color palettes to Joplin, packed with smart layout optimizations for everyday productivity, mobile reading comfort, and bilingual note-taking:

- 🌗 **Automatic Dark / Light Mode:** Seamlessly adapts to your system theme (`prefers-color-scheme`).
- 📱 **Mobile & Tablet Optimized:** Standard 16px typography, proportional H1–H6 scaling, compact list indents, and touch-friendly table/code scrolling.
- 🌐 **Dual Flavors & `<div dir="ltr">` Support:**
  - **`userstyle.css`:** Native LTR edition for English & global languages.
  - **`userstyle-rtl.css`:** Native RTL edition powered by **Vazirmatn** with zero punctuation jumps and full `<div dir="ltr">` support for English sections without plugins.
- 📊 **Obsidian-Style Mermaid Engine:** Large, wide, or complex diagrams render crisply inside an unconstrained horizontal viewport with smooth scrolling.
- 🖼️ **Responsive Media & Elements:** Auto-scaled images (`max-width: 100%`), styled `<hr>` dividers, scrollable KaTeX math formulas, Table of Contents (`[[toc]]`), and Footnotes (`[^1]`).
- 🖨️ **Clean Print & PDF Export:** Automatically strips dark backgrounds and scrollbars when generating documents.

---

## 📱 Mobile & Responsive Typography

Reading notes on high-DPI smartphones often suffers from tiny fonts, awkward heading sizes, and squeezed list columns. This theme implements strict mobile typography guidelines:

- **16px Base Reading Size:** Perfectly tuned with optimal line-height (`1.85` for Persian, `1.65` for English) for fatigue-free long-form reading.
- **Harmonic H1–H6 Hierarchy:** Distinct, balanced heading scales tailored for small viewports (< 768px).
- **Optimized List Indentation:** List padding reduced from `2.0em` to `1.3em`, saving precious horizontal width on 360–420px phone screens while preserving native hanging indents.
- **Touch-Friendly Tables & Code:** Code blocks and tables feature smooth hardware-accelerated horizontal scrolling (`-webkit-overflow-scrolling: touch`) with comfortable tap targets.

---

## 🚀 The Mermaid Scroll Engine

> **Why this theme?** In default Joplin, complex Mermaid flowcharts either stretch vertically into gigantic blocks or shrink down horizontally until text is completely microscopic.

**Joplin One Theme solves this natively without plugins:**
- Narrow/Vertical diagrams (`flowchart TD`) remain centered and compact.
- Wide/Horizontal diagrams (`flowchart LR / RL`, Sequence, Gantt) render at **100% native resolution** with an elegant horizontal scrollbar.
- Labels, nodes, and borders maintain crisp typography and never get cut off.

---

## 📦 File Variants

| File | Direction | Primary Font | Best For |
| :--- | :--- | :--- | :--- |
| **`userstyle.css`** | **LTR** (Left-to-Right) | System Native (`-apple-system`, `Segoe UI`, `Roboto`) | Pure English, European, & global notes |
| **`userstyle-rtl.css`** | **RTL** (Default) + **LTR Support** | **Vazirmatn** (وزیرمتن) | Persian, Arabic, & bilingual notes (supports `<div dir="ltr">`) |

---

## 🛠️ Installation

### Desktop (Windows, macOS, Linux)

1. Download or copy the contents of your chosen file:
   - For English/Global notes: copy **`userstyle.css`**
   - For Persian/RTL/Bilingual notes: copy **`userstyle-rtl.css`**
2. In Joplin, go to:
   - **Tools** → **Options** (or **Joplin** → **Preferences** on macOS)
   - Click on **Appearance** in the sidebar.
   - Click **Show Advanced Settings**.
   - Click **Custom stylesheet for rendered Markdown** (this opens your local `userstyle.css`).
3. Paste the code into the file and save it.
4. **Completely restart Joplin** (*File → Quit*, then reopen) to apply the stylesheet.

### Mobile (Android / iOS)

You can apply custom styles on mobile using the Joplin sync mechanism or mobile plugins (such as *Import Local CSS*). The theme automatically detects mobile screen widths (< 768px) and activates mobile-optimized typography.

---

## 🇮🇷 راهنمای فارسی (Persian Guide)

این تم به طور اختصاصی برای کاربران فارسی‌زبان بهینه‌سازی شده است تا تمامی مشکلات رایج رندرینگ، تایپوگرافی، چیدمان بولت‌ها و نمایش در موبایل برطرف شود.

### ✨ ویژگی‌های برجسته نسخه فارسی (`userstyle-rtl.css`):

1. **فونت استاندارد وزیرمتن (Vazirmatn):** لود فونت استاندارد وب با بهترین اعراب‌گذاری و خوانایی چشم‌نواز.
2. **بهینه‌سازی کامل صفحه نمایش موبایل:**
   - اندازه متن پایه **`16px` با ارتفاع خط `1.85`** برای خواندن آسان متون طولانی در نمایشگر گوشی.
   - سلسله‌مراتب دقیق سرفصل‌ها (از H1 تا H6) متناسب با صفحه گوشی.
   - بهینه‌سازی تورفتگی لیست‌ها (`1.3em`) برای جلوگیری از باریک شدن ستون متن در موبایل.
3. **لیست‌های استاندارد با تورفتگی معلق (Hanging Indent):**
   - بولت‌ها و اعداد ترتیبی دقیقاً در سمت راست قرار دارند.
   - در متن‌های چندخطی، خطوط بعدی دقیقاً زیر متن قرار می‌گیرند نه زیر بولت.
4. **پشتیبانی کامل از متون انگلیسی بدون پلاگین (`<div dir="ltr">`):**
   - برای نوت‌های کاملاً انگلیسی یا بخش‌های انگلیسی در میان متن فارسی، کافیست از تگ `<div dir="ltr">` استفاده کنید تا متن، تیترها، خط H2، خط نقل‌قول و بولت‌ها خودکار چپ‌چین شوند!
5. **المان‌های پیشرفته مارک‌داون:**
   - **تصاویر ریسپانسیو:** تصاویر بزرگ به صورت خودکار اندازه صفحه گوشی می‌شوند و کادر را نمی‌شکنند.
   - **فرمول‌های ریاضی (KaTeX):** ایزوله‌سازی چپ‌چین برای جلوگیری از معکوس شدن توان‌ها و کسرها.
   - **خطوط جداکننده (`---`):** خطوط ۲ پیکسلی شیک با رنگ هماهنگ با تم تاریک و روشن.
   - **فهرست مطالب (`[[toc]]`) و پاورقی‌ها:** طراحی کارتی مدرن مشابه Obsidian و GitHub.
6. **موتور اسکرول دیاگرام‌های Mermaid:** رفع قطعی کوچک شدن یا کشیده شدن فلوچارت‌ها.
7. **خروجی تمیز PDF و چاپ:** حذف پس‌زمینه تیره و اسکرول‌بارها هنگام خروجی گرفتن.

---

### 📝 نحوه نوشتن متون انگلیسی در تم فارسی:

برای یادداشت‌های انگلیسی یا بخش‌های انگلیسی در تم فارسی، تنها کافی است متن را درون یک بلوک `div` با صفت `dir="ltr"` قرار دهید:

```markdown
<div dir="ltr">

# English Title
This is an English paragraph.

- First item
- Second item with long text that wraps cleanly
  - Nested sub-item

> This blockquote has a sleek left border.

</div>
```

*(نکته: همیشه یک خط خالی بعد از `<div dir="ltr">` و قبل از `</div>` بگذارید تا مارک‌داون به درستی رندر شود).*

---

### 📥 نحوه نصب نسخه فارسی:

1. محتویات فایل **`userstyle-rtl.css`** را کپی کنید.
2. در جاپلین به مسیر: **ابزارها (Tools)** ← **تنظیمات (Options)** ← **ظاهر (Appearance)** بروید.
3. روی **نمایش تنظیمات پیشرفته (Show Advanced Settings)** کلیک کرده و گزینه **Custom stylesheet for rendered Markdown** را بزنید.
4. متن کپی‌شده را در فایل بازشده جایگزین کرده و ذخیره کنید (`Ctrl + S`).
5. برنامه جاپلین را یک‌بار **کاملاً ببندید (File → Quit)** و دوباره باز کنید.

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

Suggestions, bug reports, and pull requests are warmly welcome! If you encounter any styling glitch or have ideas for improvements, please feel free to open an [Issue](https://github.com/xyasharx/joplin-one-theme/issues).

⭐ **If you find this theme useful, please star this repository on GitHub!**

---

## 📄 License

This project is licensed under the [MIT License](https://github.com/xyasharx/joplin-one-theme/blob/main/LICENSE).
