# Mercedes-Benz VISION AVTR — Landing Page

A responsive single-page layout dedicated to the **Mercedes-Benz VISION AVTR** concept car, inspired by James Cameron's "Avatar". Built with pure HTML5 and CSS3, no frameworks.

##  Demo

> Add your live link here once deployed via GitHub Pages:
> `https://github.com/ByteBloom357/AVTR/tree/main`

##  Overview

The page consists of the following sections:

- **Header** — logo, menu button, social media links
- **Top (Hero)** — title, tagline, and background car image
- **Concept** — a short description of the concept car's philosophy
- **Premier** — information about the CES 2020 presentation
- **Video** — a block with a video preview and play button
- **Design (Interior & Exterior)** — a section describing the interior/exterior design, built with CSS Grid
- **Footer** — privacy policy link, logo, social media links

##  Technologies

- HTML5
- CSS3 (Flexbox, CSS Grid, media queries)
- Google Fonts (`Roboto Condensed`)

## 📱Responsiveness

The layout is adapted for the following breakpoints:

| Screen width | Behavior |
|---|---|
| `≤ 1240px` | Images are constrained in width |
| `≤ 1000px` | The `design` section switches to a block layout |
| `≤ 640px` | Header/footer are restructured, spacing and font sizes are reduced |
| `≤ 590px` | The `premier` section switches to a block layout |
| `≤ 430px` | Footer content is centered |

## Project Structure

```
├── index.html
├── style/
│   └── style.css
├── img/
│   ├── logo.svg
│   ├── menu-logoo.svg
│   ├── twitter.svg
│   ├── google.svg
│   ├── facebook.svg
│   ├── mercedes-icon.svg
│   ├── top-pg.png
│   ├── concept.jpg
│   ├── img-left.jpg
│   ├── img-right.png
│   ├── video-img.png
│   ├── img-top.jpg
│   ├── img-bottom.png
│   └── car-main.png
└── README.md
```

> ⚠️ Make sure all image files referenced in `index.html` (e.g. `img/logo.svg`, `img/concept.jpg`, etc.) actually exist inside an `img/` folder next to `index.html` — otherwise they won't display.

##  Running the Project Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ByteBloom357/AVTR/tree/main
   ```

3. Open `index.html` in your browser, or run a local server, e.g. via the **Live Server** extension in VS Code.

##  Roadmap

- [ ] Add working logic for the menu button (`.btn-menu`)
- [ ] Wire up actual video playback in the `.video` block
- [ ] Fix a noticeable bug in the play-button SVG icon (invalid attributes `fi11`, `xmIns`, and a stray space in the `path` coordinates)
- [ ] Add `alt` text to images for better accessibility
- [ ] Optimize images for faster load times

## 📄 License

This project is open-source and available under the MIT License. Feel free to use, modify, and share it!
