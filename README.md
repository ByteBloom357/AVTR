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
 How to Run Locally

Follow these simple steps to get the project up and running on your local machine:
1. Clone the Repository

Run the following command in your terminal to clone the project:
Bash

git clone https://github.com/ByteBloom357/AVTR.git

2. Navigate to the Project Folder

Switch to the project directory:
Bash

cd AVTR

3. Open the Project

    Method 1: Simply locate the index.html file in your folder and double-click it to open it in any web browser.

    Method 2 (Recommended): If you are using VS Code, install the Live Server extension, right-click on index.html, and select "Open with Live Server".

License

This project is open-source and available under the MIT License. Feel free to use, modify, and share it!
---
##  Project Structure
```text
├── img/              # Image assets (JPG, PNG, SVG)
├── style/
│   └── style.css     # Main stylesheet with media queries
└── index.html        # Main HTML structure
---


