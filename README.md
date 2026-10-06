# 🎉 New Year Party Celebration — Landing Page

A festive, single-page landing site for a New Year's Eve party and holiday sale, built with **pure HTML5 and CSS3** from a Figma design.

> **Programming Hero — Level 1 · Assignment 1 (Batch 9)**
> Completed: **January 9, 2024**

<p>
  <a href="https://shimul705.github.io/assignment1-b9/"><img alt="Live Demo" src="https://img.shields.io/badge/Live-Demo-FF0000?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="https://github.com/shimul705/assignment1-b9"><img alt="Source Code" src="https://img.shields.io/badge/Source-Code-070211?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

## 🔗 Links

| | |
|---|---|
| **Live Site** | [shimul705.github.io/assignment1-b9](https://shimul705.github.io/assignment1-b9/) |
| **Repository** | [github.com/shimul705/assignment1-b9](https://github.com/shimul705/assignment1-b9) |

---

## 📌 Overview

This was my **first assignment** at Programming Hero. The goal was to turn a Figma design (`resources/new year.fig`) into a static web page that matches the design closely, using only semantic HTML and hand-written CSS, with no frameworks or JavaScript.

The page promotes a midnight New Year party and a holiday sale, with nine sections from the hero banner to the footer.

---

## ✨ Page Sections

1. **Hero Banner:** a full-width background image with a gradient overlay and the event title.
2. **Offer:** a "65% OFF" holiday deals headline with a featured graphic.
3. **Midnight Party:** an invitation card with a call-to-action button over a gradient background.
4. **Event Details:** the place, date and time, highlighted with a red accent and a **Join Now** button.
5. **Coming Soon:** a three-column layout with a circular framed image and the 2024 highlight.
6. **Holidays Sale 50%:** a layered image composition built with absolute positioning.
7. **Our Awesome Portfolio:** a responsive product gallery built with Flexbox.
8. **Newsletter:** an email subscription form with a pill-shaped input and button.
9. **Footer:** address, contact info, social icons and copyright.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure (`section`, `main`, `footer`, `form`) |
| **CSS3** | Flexbox, `position: absolute` layering, linear gradients, `border-radius`, media queries |
| **Google Fonts** | `Merriweather` (400, 900) for headings, `Inter` (400–700) for body text |
| **Figma** | Design source (`resources/new year.fig`) |
| **GitHub Pages** | Deployment |

---

## 📱 Responsive Design

The original layout targets large desktop screens. Breakpoints were added later so that the page reads cleanly on every device **without changing the desktop design**:

| Breakpoint | Device | Adjustments |
|---|---|---|
| `> 1200px` | Desktop | Original design |
| `≤ 1200px` | Laptop / Tablet | Smaller headings, the 50% sale image composition scales by percentage, a two-column gallery |
| `≤ 992px` | Small tablet | The party card and Coming Soon section stack vertically |
| `≤ 768px` | Mobile | Wider container (90%), mobile type scale, a stacked footer, a compact newsletter form |
| `≤ 480px` | Small mobile | A single-column gallery and further type scaling |

---

## 📂 Project Structure

```
assignment1-b9/
├── index.html          # Page markup
├── styles/
│   └── newyear.css     # All styles + responsive media queries
├── resources/          # Images, icons and the Figma design file
└── info.txt            # Font reference notes
```

---

## 🚀 Run Locally

```bash
git clone https://github.com/shimul705/assignment1-b9.git
cd assignment1-b9
```

Then open `index.html` in any browser. No build step is required.

---

## 📚 What I Learned

- Converting a **Figma design into HTML/CSS** with close attention to spacing, typography and colour.
- Building layouts with **Flexbox** (`justify-content`, `align-items`, `flex-wrap`, `gap`).
- Layering images with **`position: relative` / `absolute`**.
- Combining **gradient overlays with background images**.
- Loading and pairing **Google Fonts**.
- Writing **media queries** to make a desktop-first design responsive.
- Deploying a static site with **GitHub Pages**.

---

## 👤 Author

**Shimul**
GitHub: [@shimul705](https://github.com/shimul705)

---

<sub>Part of my Programming Hero learning journey. Each assignment shows a step in my growth as a web developer.</sub>
