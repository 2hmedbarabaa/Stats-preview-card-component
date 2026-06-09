# Frontend Mentor - Stats Preview Card Component Solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8e6m6qn63). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (`min-width: 320px` up to desktop viewports).
- See a professional purple color blend overlay on the header image matching the original design fidelity.

### Screenshots

#### Desktop View
![Desktop Design](./design/desktop-design.jpg)

#### Mobile View
![Mobile Design](./design/mobile-design.jpg)

*(Note: Replace these paths with your actual project screenshot paths if you take custom screenshots later)*

### Links

- Solution URL: [Add your Frontend Mentor solution URL here]
- Live Site URL: [Add your live site URL here (e.g., GitHub Pages, Netlify, Vercel)]

## My process

### Built with

- Semantic HTML5 markup (utilizing `<main>`, `<section>`, and `<ul>` list structures for optimal accessibility)
- CSS Custom Properties (Variables for streamlined token management)
- Flexbox Architecture (Mobile-first responsive layout processing)
- `<picture>` element for adaptive viewport asset delivery
- CSS `mix-blend-mode` for non-destructive, professional image color blending

### What I learned

During this project, I gained deep structural insights into handling responsive typography alignment and multi-layered asset composition. 

1. **Advanced Image Color Blending**: Instead of placing a flat, semi-transparent block over the header image which dulls contrast, I utilized a pseudo-element combined with `mix-blend-mode: multiply`. This allows the dark tones of the container background to realistically merge with the purple hue, replicating professional design tool logic.

2. **Semantic List Architecture for Stats**: To ensure compliance with modern accessibility (WCAG) guidelines, I structured the data statistics using unordered list matrices (`<ul>` and `<li>`), which explicitly communicates tabulated metric relationships to screen readers.

3. **Flexbox Cross-Axis Synchronization**: I mastered alignment transitions between responsive modes—ensuring that items transition cleanly from central alignment on narrow mobile containers to rigid, single-baseline vertical alignment (`align-items: flex-start`) on desktop rows.

### Continued development

In my future projects, I intend to focus on:
- Exploring complex cubic-bezier acceleration values to implement fluid motion paths on hover states.
- Expanding component layouts using standard CSS Grid layouts for multi-axis landing pages.
- Enforcing stricter engineering guidelines regarding fluid scale systems using `clamp()` instead of fixed breakpoint steps.

## Author

- Frontend Mentor - [@YourUsername](https://www.frontendmentor.io/profile/YourUsername)
- Twitter/X - [@YourTwitter](https://www.twitter.com/YourTwitter)
