# MyBike — Landing Page

A fully responsive landing page for an electric bike brand, built as part of a frontend development course at Mate Academy. The project demonstrates practical skills in semantic HTML markup, SCSS component architecture, and mobile-first responsive design — without any CSS frameworks.

The page includes multiple thematic sections: a hero header with a fullscreen background, a product comparison block with model cards, a details section showcasing key bike features with photo galleries, and a contact form. Navigation is implemented via anchor links with smooth scrolling and a slide-out mobile menu.

## Live Preview

[DEMO LINK](https://sonik-boom71.github.io/mybike-landing/)

## Technologies Used

- **HTML5** — semantic markup, accessibility attributes (`aria-label`)
- **SCSS** — BEM methodology, variables, nesting, reusable mixins
- **JavaScript (ES6+)** — smooth scroll, mobile menu toggle
- **Parcel** — module bundler with SCSS support
- **GitHub Pages** — deployment via `gh-pages`

## Project Structure

```
src/
├── images/        # Photos, icons, SVG logos
├── scripts/       # JavaScript files
├── styles/        # SCSS files (BEM blocks)
└── index.html     # Main HTML file
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/sonik-boom71/mybike-landing.git
cd mybike-landing
```

2. Install dependencies:

```bash
npm install
```

3. Run the project locally:

```bash
npm start
```

The dev server will open at `http://localhost:8080`.

## Features

- **Hero section** — fullscreen header with brand tagline and call-to-action
- **Mobile menu** — slide-out navigation panel triggered by a hamburger icon
- **Compare Bikes** — three model cards with images, descriptions and pricing
- **The Details** — three feature blocks (Auto Unlock, Range & Lights, Hydraulic Brakes) with paired photo layouts
- **Contact Form** — fields for name, email and message with HTML5 validation
- **Fully responsive** — mobile-first layout adapting to all screen sizes
- **Smooth scroll** — anchor-based navigation between all sections
