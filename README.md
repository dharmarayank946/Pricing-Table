# VEDA Technology Web Development Internship Task 12 — Pricing Table

A clean, modern, and fully responsive **Pricing Table** built strictly using **HTML5** and **CSS3**. This project presents three structured subscription tiers (**Basic**, **Pro**, and **Premium**) tailored with illustrative prices in Indian Rupees (₹), styled with a unique butter-yellow and warm coral palette, semantic markup, and mobile-friendly interactions.

---

## 📌 Project Overview
- **Project Title:** VEDA Technology Web Development Internship Task 12 — Pricing Table
- **Internship Program:** VEDA Technology Web Development Internship
- **Developer:** Nagalambika D Koralli
- **Core Technologies:** HTML5, CSS3 (No JavaScript, No Frameworks, No Build Tools)
- **GitHub Repository:** [https://github.com/dharmarayank946/Pricing-Table.git](https://github.com/dharmarayank946/Pricing-Table.git)
- **Live Demo (GitHub Pages):** [https://dharmarayank946.github.io/Pricing-Table/](https://dharmarayank946.github.io/Pricing-Table/)
- **Unique Theme Palette:**
  - **Background:** `#FFFBEA` (Warm Butter Cream)
  - **Primary Accent:** `#E3B341` (Golden Butter Yellow)
  - **Button Accent:** `#E87955` (Warm Coral)
  - **Main Text:** `#3D352C` (Deep Charcoal Brown)
  - **Secondary Text:** `#817567` (Warm Slate Muted)
  - **Pricing Cards:** `#FFFFFF` (Crisp White)
  - **Border:** `#F0E2B5` (Soft Butter Border)

---

## 🎯 Objectives
1. Design and build a professional, conversion-focused pricing table featuring three distinct tiers: **Basic Plan**, **Pro Plan**, and **Premium Plan**.
2. Provide essential subscription details on every card:
   - Plan name
   - Price in Indian Rupees (₹/month)
   - Short concise description
   - Clear feature list with visual checkmarks
   - Dedicated call-to-action (CTA) button
3. Highlight the **Pro Plan** as the **"Most Popular"** tier using a prominent coral badge, distinct colored border, soft warm tint, and elevated shadow depth.
4. Apply the dedicated Task 12 butter-yellow and coral color scheme across the entire page, ensuring consistent typography, padding, and subtle micro-interactions without dark themes or excessive gradients.
5. Ensure 100% responsiveness across devices:
   - Clean 3-card horizontal row on desktop
   - Fluid vertical stack on tablets and mobile phones
   - Zero horizontal scrolling
   - Large, thumb-friendly tap targets for mobile browsers
6. Keep the codebase pure, clean, and beginner-friendly, requiring zero build commands, npm packages, or terminal environments.

---

## 🛠️ Technologies Used
- **HTML5:** Semantic landmark elements (`<main>`, `<header>`, `<section>`, `<article>`, `<ul>`, `<li>`, `<footer>`, `<button>`) with full accessibility attributes (`aria-label`, `aria-hidden`).
- **CSS3:** Modern layout techniques including CSS Grid, Flexbox, CSS Custom Properties (variables), smooth box-shadows, rounded corners, and micro-interactions.
- **Google Fonts:** `Plus Jakarta Sans` for clean, contemporary, and legible typography across all viewports.
- **SVG Icons:** Inline, scalable SVG checkmarks and assurance icons ensuring zero broken links or external asset delays.

---

## 💳 Pricing Tiers & Details

| Plan Tier | Price | Description | Target Audience | Features Included | CTA Button |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Basic Plan** | **₹499 / month** | Essential tools and foundational access | Beginners | • Basic features<br>• Standard support<br>• Limited access<br>• Suitable for beginners | `Choose Basic` |
| **Pro Plan**<br>*(Most Popular)* | **₹999 / month** | Comprehensive toolset with priority service | Regular Users | • All Basic features<br>• Advanced features<br>• Priority support<br>• Suitable for regular users | `Choose Pro` |
| **Premium Plan** | **₹1,999 / month** | Full suite of capabilities and premier guidance | Advanced Users | • All Pro features<br>• All features included<br>• Premium support<br>• Suitable for advanced users | `Choose Premium` |

---

## ✨ Features & Visual Highlights
- 🎨 **Unique Butter-Yellow & Coral Theme:** Harmonious butter-cream background (`#FFFBEA`) paired with warm coral accents (`#E87955`) and golden butter yellow highlights (`#E3B341`).
- 🌟 **Highlighted "Most Popular" Card:** The Pro Plan card features an elevated coral badge (`Most Popular`), distinct 2px coral border, subtle vertical tint, and increased depth to guide user focus.
- 📐 **Clean CSS Grid & Flexbox Alignment:** Cards share consistent heights on desktop, with footer buttons cleanly pinned to the bottom of each card.
- ⚡ **Subtle Micro-Interactions:** Smooth `transform: translateY(-6px)` hover effects on cards and responsive button hover transitions.
- 📱 **Mobile-First Touch Ergonomics:** All buttons have a minimum tap height of 50px with clear active press states.
- 🔒 **Trust & Assurance Row:** Includes trust indicators for *Secure Payment*, *Instant Activation*, and *Cancel Anytime*.
- 📦 **Zero-Config Static Architecture:** Ready to view locally by double-clicking `index.html` or deploying instantly to GitHub Pages.

---

## 📱 Responsive Design Details
- **Desktop (> 820px):** 3-column CSS Grid layout (`grid-template-columns: repeat(3, 1fr)`) with equal card heights and neat horizontal spacing.
- **Tablet / Mobile (≤ 820px):** Single-column stacked layout (`grid-template-columns: 1fr`) centered with max-width restriction (460px), maintaining card padding, clear typography, and the highlighted Pro card styling.
- **Small Mobile Screens (≤ 400px):** Adaptive font sizes and compact card padding preventing text clipping or horizontal overflow.
- **Viewport Protection:** `overflow-x: hidden` and `box-sizing: border-box` configured globally to guarantee zero horizontal scroll on mobile devices.

---

## 📂 Project File Structure
```text
Task12-Pricing-Table/
├── index.html        # Semantic HTML5 markup containing all 3 pricing cards
├── style.css         # CSS3 styling, color system, grid layout, and media queries
└── README.md         # Comprehensive project documentation and deployment guide
```

---

## 🚀 How to Run the Project Locally

Because this project is built entirely with pure HTML5 and CSS3, no terminal, Node.js, or build commands are required:

1. **Directly from your File Browser:**
   - Navigate to the `Task12-Pricing-Table` folder.
   - Double-click `index.html` to open it in your preferred web browser (Chrome, Firefox, Edge, Safari).

2. **Using VS Code Live Server (Optional):**
   - Open the folder in VS Code.
   - Right-click `index.html` and click **"Open with Live Server"**.

---

## 🌐 GitHub Pages Deployment Instructions

To deploy this project to the web for free using GitHub Pages:

1. Push or upload `index.html`, `style.css`, and `README.md` to your repository:
   ```
   https://github.com/dharmarayank946/Pricing-Table.git
   ```
2. Navigate to your repository on GitHub.
3. Go to **Settings** → **Pages** (under "Code and automation").
4. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: Select `main` (or `master`) and folder `/ (root)`
5. Click **Save**.
6. Within 1–2 minutes, your website will be live at:
   ```
   https://dharmarayank946.github.io/Pricing-Table/
   ```

---

## 📄 License & Attribution
Developed as part of the **VEDA Technology Web Development Internship Program** by **Nagalambika D Koralli**. All rights reserved.
