# Two Leaves and a Bud — Responsive Web Clone

**Assignment 6** · Sheriyans Coding School · Responsive Web Development

**Author:** Divyansh

A responsive front-end clone of the [Two Leaves and a Bud](https://www.twoleavestea.com/) organic tea website, built with HTML, CSS, and vanilla JavaScript.

---

## About the Project

This project recreates the look and feel of the Two Leaves and a Bud homepage across desktop, tablet, and mobile screen sizes. It includes a multi-section landing page with hero, product showcases, reviews, journal carousel, newsletter footer, and interactive UI details inspired by the original site.

---

## Features

- **Responsive layout** — Separate stylesheets for desktop, tablet (`max-width: 1024px`), and mobile (`max-width: 480px`)
- **Sticky navbar animation** — Header slides in on load and compacts on scroll; announcement bar hides after scrolling
- **Interactive navigation** — Hover underline on Reviews and right-side nav links; mobile hamburger menu layout
- **Product & review sections** — Horizontally scrollable cards on larger layouts; stacked layouts on smaller screens
- **Hover effects** — Smooth button transitions on key CTAs (Shop Now, Explore All Teas, Our Story, etc.)
- **Newsletter footer** — “Steep with Us” signup with social icons
- **Accessibility button** — Fixed corner icon (`assessablity-icon.png`) matching the reference design
- **Custom typography** — Reckless, Figtree, Midnight, Gothic, and Roboto Mono font files

---

## Tech Stack

| Technology | Use |
|------------|-----|
| HTML5 | Page structure & semantic sections |
| CSS3 | Layout, animations, media queries |
| JavaScript | Navbar scroll behavior |
| [Remix Icon](https://remixicon.com/) | Icons (menu, stars, arrows) |

---

## Project Structure

```
Two levies/
├── index.html          # Main HTML file
├── style.css           # Base / desktop styles
├── tablet.css          # Tablet responsive styles
├── mobile.css          # Mobile responsive styles
├── nav-scroll.js       # Navbar sticky scroll logic
├── assessablity-icon.png
├── fonts/              # Custom web fonts
├── assests/            # SVG logos & icons
└── README.md
```

---

## Getting Started

1. Clone or download this repository
2. Open `index.html` in a browser, or use a local server:

```bash
# Example with Live Server (VS Code) or Python:
python -m http.server 5500
```

3. Visit `http://localhost:5500` in your browser

---

## Responsive Breakpoints

| Breakpoint | Stylesheet | Target |
|------------|------------|--------|
| Default | `style.css` | Desktop (1025px+) |
| `max-width: 1024px` | `tablet.css` | Tablets |
| `max-width: 480px` | `mobile.css` | Mobile phones |

---

## Sections Overview

| Section | Description |
|---------|-------------|
| Hero | Full-width banner with headline and Shop Now CTA |
| Page 2 | Best sellers product carousel |
| Page 3 | Tea discovery search & vibe tags |
| Page 4 | Born in Colorado brand story |
| Page 5 | Customer reviews |
| Page 6 | Cafe & wholesale partners |
| Page 7 | Barista blends feature |
| Page 8 | Tea journal carousel |
| Page 9 | About / community CTA |
| Footer | Newsletter signup, link columns, brand logo |

---

## Credits

- Design inspiration: [twoleavestea.com](https://www.twoleavestea.com/)
- Built as **Assignment 6** for **Sheriyans Coding School** — Responsive Web Development
- Developed by **Divyansh**

---

## License

This project is for educational purposes only as part of a coding school assignment.
