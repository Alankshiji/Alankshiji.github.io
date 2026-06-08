# Alan K Shiji — Portfolio Website

A professional, minimal, and responsive portfolio website built for **Alan K Shiji** — Cybersecurity & AI Developer based in Kottayam, Kerala, India.

---

## Live Preview

> Deploy on [GitHub Pages](https://pages.github.com), [Netlify](https://netlify.com), or [Vercel](https://vercel.com) and paste your URL here.

---

## About

This is a single-file static portfolio website designed with a **dark tech / terminal aesthetic** — built to make a strong impression on MNC recruiters and hiring managers. It showcases professional experience, skills, education, and contact details in a clean, modern layout.

---

## Features

- **Fully Responsive** — works seamlessly on mobile, tablet, iPad, and desktop
- **Single HTML file** — no frameworks, no build tools, zero dependencies (fonts loaded via Google Fonts CDN)
- **Smooth animations** — scroll-triggered reveals, typing effect on hero title, staggered card entrances
- **Terminal-style contact card** — JSON display with syntax highlighting
- **Mobile hamburger menu** — collapsible navigation for small screens
- **Accessible** — semantic HTML5, readable contrast ratios throughout

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | Hero | Name, animated title, CTA buttons, key stats |
| 02 | About | Professional summary + personal info card |
| 03 | Experience | Work history with role details and bullet points |
| 04 | Skills | Technical skills grouped into four categories |
| 05 | Education | Degree and school cards |
| 06 | Certifications | Workshops and certifications list |
| 07 | Contact | Links + terminal JSON profile card |

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, clamp(), animations
- **Vanilla JavaScript** — IntersectionObserver for scroll reveals, typing effect, mobile menu
- **Google Fonts** — Syne, Space Mono, DM Sans

No npm. No build step. Just one file.

---

## Getting Started

### Run Locally

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
# Open the file in your browser
open alan-portfolio.html
```

### Deploy to GitHub Pages

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Rename `alan-portfolio.html` to `index.html`
5. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

### Deploy to Netlify (drag & drop)

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the `alan-portfolio.html` file (renamed to `index.html`)
3. Live in seconds — free custom subdomain included

---

## Customization

All content is in a single `alan-portfolio.html` file. To update:

| What to change | Where to find it |
|----------------|-----------------|
| Name, title, summary | `#hero` and `#about` sections |
| Contact details | `#about` info card and `#contact` links |
| Work experience | `#experience` `.exp-item` blocks |
| Skills | `#skills` `.skill-card` blocks |
| Education | `#education` `.edu-card` blocks |
| Colors / theme | `:root` CSS variables at the top of `<style>` |
| Fonts | `@import` link in `<head>` + font-family in `:root` |

### Color Variables

```css
:root {
  --bg: #050a0f;          /* Main background */
  --accent: #00c8ff;      /* Primary accent (cyan) */
  --accent2: #00ff9d;     /* Secondary accent (green) */
  --text: #e8f0f8;        /* Primary text */
  --text2: #8ba4be;       /* Secondary text */
}
```

---

## Project Structure

```
/
├── alan-portfolio.html   # The entire website (rename to index.html for deployment)
└── README.md
```

---

## Contact

**Alan K Shiji**
- 📧 alankshiji@gmail.com
- 📱 +91 7306600310
- 💼 [linkedin.com/in/alan-k-shiji-75a928265](https://www.linkedin.com/in/alan-k-shiji-75a928265/)
- 📍 Kottayam, Kerala, India

---

## License

This project is open source and available under the [MIT License](LICENSE).

Feel free to fork and adapt for your own portfolio — a credit or star is appreciated!
