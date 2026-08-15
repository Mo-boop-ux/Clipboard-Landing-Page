# Frontend Mentor - Clipboard Landing Page Solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5O7E7WdE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover and focus states for all interactive buttons and navigation links
- Experience a clean, fluid responsive layout across mobile, tablet, and desktop screens

### Links

- **Live Site URL**: [Live Demo](https://mo-boop-ux.github.io/Clipboard-Landing-Page/)
- **GitHub Repository**: [Clipboard-Landing-Page](https://github.com/Mo-boop-ux/Clipboard-Landing-Page)

---

## My Process

### Built With

- **Semantic HTML5** markup (`<main>`, `<section>`, `<footer>`, `<button>`, `<h1>`-`<h3>`)
- **CSS3 Custom Styling** - CSS Flexbox for modern alignment and responsive stacking
- **Google Fonts** - [Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree) (Weights: 400, 600)
- **Responsive Design** - Mobile-first workflow with media queries for seamless multi-device scaling
- **Interactive UI States** - Hover effects on action buttons, social icons, and navigation links

### What I Learned

During this project, I deepened my understanding of building multi-section landing pages with complex image layouts:

1. **Split-Screen Feature Showcase**:
   Aligning a large feature preview image alongside structured text blocks while maintaining responsiveness.

```css
.section-2 .split-card {
    display: flex;
    align-items: center;
    width: 100%;
    overflow: hidden;
}
```

2. **Styling Responsive Call-to-Action Buttons**:
   Implementing clean, accessible buttons with hover feedback and rounded aesthetics:

```css
.ios-btn, .mac-btn {
    padding: 0.8rem 2rem;
    color: white;
    font-weight: 600;
    border-radius: 2rem;
    cursor: pointer;
    transition: opacity 0.2s ease;
}
```

### Useful Resources

- [MDN Web Docs - CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Helpful reference for flexible layout structuring.
- [Frontend Mentor](https://www.frontendmentor.io) - Great platform for real-world frontend challenges.

---

## Author

- GitHub - [Mo-boop-ux](https://github.com/Mo-boop-ux)
- Frontend Mentor - [@Mo-boop-ux](https://www.frontendmentor.io/profile/Mo-boop-ux)
