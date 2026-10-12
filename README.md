# ✨ Glassmorphism Personal Portfolio Card

<p align="center">
  <img src="images/bg.png" alt="Portfolio Background Preview" width="100%" style="border-radius: 12px;" />
</p>

<p align="center">
  A sleek, modern, and lightweight <strong>Glassmorphism Portfolio Card</strong> web application built with pure <strong>HTML5</strong> and <strong>Vanilla CSS3</strong>. Designed to showcase a developer's identity, key technical skills, social profiles, and call-to-action in an elegant frosted-glass presentation.
</p>

<p align="center">
  <a href="https://github.com/CodeWithTanim/Portfolio/stargazers"><img src="https://img.shields.io/github/stars/CodeWithTanim/Portfolio?style=for-the-badge&logo=star&color=ffb703" alt="Stars"></a>
  <a href="https://github.com/CodeWithTanim/Portfolio/network/members"><img src="https://img.shields.io/github/forks/CodeWithTanim/Portfolio?style=for-the-badge&logo=git&color=219ebc" alt="Forks"></a>
  <a href="https://github.com/CodeWithTanim/Portfolio/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License"></a>
  <img src="https://img.shields.io/badge/Language-HTML5%20%26%20CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 and CSS3">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status">
</p>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Comprehensive Feature Breakdown](#-comprehensive-feature-breakdown)
  - [1. Visual & Glassmorphism Design System](#1-visual--glassmorphism-design-system)
  - [2. Header & Identity Section](#2-header--identity-section)
  - [3. Profile Avatar & Orbit Framing](#3-profile-avatar--orbit-framing)
  - [4. Skills Directory](#4-skills-directory)
  - [5. Interactive Social Presence](#5-interactive-social-presence)
  - [6. Call-to-Action (CTA) Button](#6-call-to-action-cta-button)
  - [7. Layout, Responsiveness & Centering](#7-layout-responsiveness--centering)
  - [8. Zero-Dependency & Performance Architecture](#8-zero-dependency--performance-architecture)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Customization Guide](#-customization-guide)
- [Author & Connect](#-author--connect)
- [License](#-license)

---

## 📖 Overview

The **Glassmorphism Personal Portfolio Card** is a focused personal landing card and developer bio component. Utilizing modern CSS backdrop filters, translucent glass styling, and smooth micro-interactions, it presents essential portfolio details in an uncluttered, modern format.

Whether used as a standalone single-page portfolio, a digital business card, a "link-in-bio" alternative, or an embeddable UI card, it offers instant visual impact with zero overhead.

---

## 🚀 Comprehensive Feature Breakdown

Every feature in this project has been crafted to deliver an aesthetically pleasing, responsive, and intuitive user experience:

### 1. Visual & Glassmorphism Design System
- **Frosted Glass Backdrop (`backdrop-filter: blur(25px)`)**: Applies a native hardware-accelerated blur to everything behind the card container, creating a realistic translucent glass pane.
- **Translucent Fill Layer (`background: rgba(255, 255, 255, 0.1)`)**: Subtle high-key white tint that separates the card from the underlying wallpaper while maintaining background visibility.
- **Diffuse Multi-Layer Drop Shadow (`box-shadow: 0 25px 45px rgba(0, 0, 0, 0.25)`)**: Delivers realistic visual elevation and depth, giving the illusion of the card floating in 3D space.
- **Specular Border Accent (`border: 1px solid rgba(255, 255, 255, 0.1)`)**: Simulates refracted edge light reflections along the perimeter of the card.
- **Organic Border Radius (`border-radius: 30px`)**: Smooth, generous rounding that softens edges in line with modern mobile and web OS design languages.
- **Fixed Fullscreen Canvas**: Implements a high-resolution ambient background graphic (`images/bg.png`) set to `background-size: cover`, `background-position: center`, and `background-attachment: fixed` to maintain immersion during viewport shifts.

### 2. Header & Identity Section
- **Card Header Bar (`.top`)**: Structured flex container with top-level spacing, bottom divider border (`1px solid #d5cccc24`), and aligned brand typography.
- **Prominent Display Name**: Highlights the creator’s identity (**MD SAMIUR RAHMAN TANIM**) in high-contrast crisp lettering (`font-size: 20px`, `color: #fff`).
- **Interactive Tooltip Architecture**: Pre-configured CSS hover state support for title bar controls and informational tooltips (`opacity: 0` to `opacity: 1` with `.5s ease-in-out` transitions).

### 3. Profile Avatar & Orbit Framing
- **Circular Avatar Container**: Displays an authentic avatar photo (`images/avatar.png`) at `170px` width with `border-radius: 50%`.
- **Dual-Layered Orbit Accent**: Features a multi-ring border treatment combining:
  - An inner transparent buffer boundary (`border: 5px solid transparent`).
  - An outer dashed luminous orbit ring (`outline: 3px dashed rgba(255, 255, 255, 0.25)`).

### 4. Skills Directory
- **Categorized Skillset Display**: Clearly labeled skills block highlighting core capabilities:
  - 🎨 **Web Designer**
  - 💻 **Programmer**
  - 🖌️ **Graphic Designer**
- **Custom Bullet Typography**: Scannable, elegant bullet items styled with `list-style-type: circle` for clean hierarchy.

### 5. Interactive Social Presence
- **Integrated Boxicons Suite**: Embeds vector iconography from Boxicons (`v2.1.4`):
  - Facebook (`bx bxl-facebook`)
  - LinkedIn (`bx bxl-linkedin`)
  - Instagram (`bx bxl-instagram`)
  - GitHub (`bx bxl-github`)
- **Micro-Animated Hover Dynamics**:
  - **Lift Motion**: Smooth upward floating displacement (`transform: translateY(-4px)`).
  - **Color Inversion**: Transitions from white outline on glass to solid white fill (`background: #fff`, `box-shadow: inset 0 0 0 15px #fff`).
  - **Brand Accent Shift**: Icon glyph shifts dynamically to royal accent blue (`color: #3c79db`).
  - **Smooth Easing**: Controlled with `transition: 0.4s` for seamless tactile feedback.
- **Safe External Navigation**: All social links open in dedicated browser tabs (`target="_blank"`).

### 6. Call-to-Action (CTA) Button
- **Dedicated "Hire" Action**: Direct contact gateway linked to the author's primary outreach channel.
- **Pill Geometry**: Form-fitted rounded button (`border-radius: 20px`) with balanced padding (`12px 20px`).
- **Primary Accent Coloring**: High-energy blue base (`background: #3c79db`) with crisp white typography.
- **Smooth Inset Glow Animation**: On hover, renders an expanding inset glow effect (`box-shadow: inset 0 0 0 20px #83ace2`) over a `0.3s` transition.

### 7. Layout, Responsiveness & Centering
- **Dual-Axis Flexbox Alignment**: The main section uses `min-height: 97vh`, `display: flex`, `justify-content: center`, and `align-items: center` to ensure the portfolio card is centered on all displays.
- **Modular Multi-Zone Layout**:
  - Top: Header bar with profile identity.
  - Middle: Two-column split layout (Left: avatar, Right: skills & social links).
  - Bottom: Right-aligned action footer housing the CTA button.

### 8. Zero-Dependency & Performance Architecture
- **Pure Native Web Technologies**: Zero bundlers, zero npm dependencies, zero JavaScript overhead.
- **Typography via Google Fonts**: Pre-connected Google Fonts CDN delivering the modern geometric sans-serif **Poppins** font family (`wght@400;500;600;700`).
- **Sub-Millisecond Rendering**: Pure static files ensure immediate First Contentful Paint (FCP) and near-zero Total Blocking Time (TBT).

---

## 📂 Project Structure

```bash
Portfolio/
├── images/
│   ├── avatar.png       # Circular profile avatar graphic
│   └── bg.png           # Ambient high-resolution background wallpaper
├── index.html           # Semantic HTML5 markup containing card structure
├── style.css            # Custom CSS styling (glassmorphism, typography, keyframes)
└── README.md            # Comprehensive project documentation
```

---

## 🛠️ Tech Stack

| Technology | Role | Source / Version |
| :--- | :--- | :--- |
| **HTML5** | Semantic structure and layout | Native |
| **CSS3** | Glassmorphism, animations, flexbox layout | Native |
| **Google Fonts** | Modern typography (Poppins) | [Google Fonts](https://fonts.google.com/specimen/Poppins) |
| **Boxicons** | Vector social media icons | [Boxicons v2.1.4](https://boxicons.com/) |

---

## ⚡ Getting Started

### Prerequisites
All you need is a modern web browser (Google Chrome, Firefox, Microsoft Edge, Safari, Brave, etc.).

### Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CodeWithTanim/Portfolio.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Portfolio
   ```

3. **Open `index.html`**:
   - Double-click `index.html` in your file explorer, or
   - Run with VS Code **Live Server** extension, or
   - Run a quick local HTTP server:
     ```bash
     # Using Python 3
     python -m http.server 3000
     ```
   - Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🎨 Customization Guide

You can easily adapt this portfolio card for your own personal brand:

1. **Replace Avatar & Background**:
   - Place your profile photo in `images/avatar.png`.
   - Place your desired wallpaper in `images/bg.png` (or change the path in `style.css` line 4).

2. **Update Personal Information**:
   - In [index.html](file:///d:/SCRIPTS/GitHub/Portfolio/index.html), replace `MD SAMIUR RAHMAN TANIM` with your name.
   - Update the `<title>` tag in `<head>`.

3. **Modify Skills**:
   - Edit the list items under `<div class="right">` inside [index.html](file:///d:/SCRIPTS/GitHub/Portfolio/index.html):
     ```html
     <ul>
         <li>Your Skill 1</li>
         <li>Your Skill 2</li>
         <li>Your Skill 3</li>
     </ul>
     ```

4. **Update Social & Hire Links**:
   - Swap the `href` URLs in the `.social-icon` section with your own profile links.
   - Update the `href` in the `<a class="btn">Hire</a>` button.

5. **Customize Colors & Blur**:
   - In [style.css](file:///d:/SCRIPTS/GitHub/Portfolio/style.css), tweak `backdrop-filter: blur(25px)` to increase or decrease blur strength.
   - Adjust `#3c79db` to match your personal brand accent color.

---

## 👨‍💻 Author & Connect

**MD SAMIUR RAHMAN TANIM**
*Web Designer • Programmer • Graphic Designer*

- **GitHub**: [@CodeWithTanim](https://github.com/CodeWithTanim)
- **LinkedIn**: [in/CodeWithTanim](https://www.linkedin.com/in/CodeWithTanim)
- **Facebook**: [facebook.com/CodeWithTanim](https://www.facebook.com/CodeWithTanim)
- **Instagram**: [@CodeWithTanim](https://www.instagram.com/CodeWithTanim)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute it for personal and commercial projects.
