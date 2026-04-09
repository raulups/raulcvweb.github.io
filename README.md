# Raul Arribas — CV Website

Personal portfolio and CV website for Raul Arribas, Android Developer based in Madrid.

**Live → [raulcvweb.github.io](https://raulcvweb.github.io)**

---

## Stack

- Pure **HTML5 + CSS3 + vanilla JavaScript** — zero frameworks, zero dependencies
- Single self-contained `index.html` (styles and scripts fully embedded)
- **Google Fonts** via CDN: [Syne](https://fonts.google.com/specimen/Syne), [DM Sans](https://fonts.google.com/specimen/DM+Sans), [DM Mono](https://fonts.google.com/specimen/DM+Mono)
- Hosted on **GitHub Pages**, deployed via **GitHub Actions**

## Features

- Typewriter hero with rotating role titles
- Scroll-reveal animations via `IntersectionObserver`
- Animated skill bars, stat counters, staggered pill entrance
- 3D card tilt on hover + magnetic button effect
- Ambient floating orbs in hero section
- Scroll progress indicator
- Functional contact form via [Formspree](https://formspree.io)
- Fully responsive with mobile hamburger menu

## Project structure

```
raulcvweb.github.io/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages deployment
├── images/                 # Profile photo & project screenshots
├── .gitignore
├── README.md
└── index.html              # Entire site — HTML, CSS and JS in one file
```

## Contact form setup

The form uses [Formspree](https://formspree.io) (free tier, no backend required).

1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and copy your endpoint ID
3. In `index.html`, replace `YOUR_FORM_ID`:

```js
const FORMSPREE_URL = 'https://formspree.io/f/YOUR_FORM_ID';
```

## License

MIT
