# AVTR — Futuristic Landing Page

A sleek, responsive landing page dedicated to the concept car **Mercedes-Benz VISION AVTR** (inspired by the movie *Avatar*). This project focuses on modern CSS layouts, semantic HTML, and fluid responsiveness.

---

##  Demo
*(Feel free to insert your live GitHub Pages or Vercel link here)*

##  Features
* **Modern Layouts:** Built using a combination of **CSS Grid** for the design gallery and **Flexbox** for alignment and navigation.
* **Fully Responsive:** Perfectly optimized for all screen sizes, from wide desktop monitors down to mobile devices ($1240\text{px}$, $1000\text{px}$, $640\text{px}$, and $430\text{px}$ breakpoints).
* **Smooth Animations:** Clean hover transitions on social media icons, buttons, and custom SVG links.
* **Semantic HTML5:** Structured with standard elements (`<header>`, `<main>`, `<section>`, `<footer>`) for better SEO and accessibility.

---

##  Tech Stack
* **HTML5** (Semantic structure)
* **CSS3** (Grid, Flexbox, Custom Media Queries, Linear Gradients)
* **Google Fonts** (Roboto Condensed)
* **SVG Icons** for sharp resolution across high-DPI screens

---

##  Layout Architecture
The project demonstrates advanced CSS positioning techniques:
* **The Hero Section (`.top`):** Uses dynamic height calculation `calc(100vh - 100px)` to flawlessly fill the viewport.
* **The Design Section (`.design`):** Leverages a robust **4-column CSS Grid** layout that gracefully converts into a single-column block layout on tablet/mobile screens ($<1000\text{px}$).
* **Adaptive Navigation:** The header and footer utilize `flex-wrap` and CSS `order` property to rearrange layout compositions beautifully on mobile screens ($<640\text{px}$).

---

##  Project Structure
```text
├── img/              # Image assets (JPG, PNG, SVG)
├── style/
│   └── style.css     # Main stylesheet with media queries
└── index.html        # Main HTML structure
How to Run Locally

    Clone the repository:
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
Navigate to the project directory:
Bash

cd YOUR_REPOSITORY_NAME

Open index.html directly in any browser, or use an extension like Live Server in VS Code.
License

This project is open-source and available under the MIT License.
