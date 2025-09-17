# Frontend Mentor - Manage Landing Page

This is a solution to the [Meet Landing Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

This is a fully responsive, modern landing page built with HTML5, CSS3 (custom properties, responsive grid, flexbox, utility classes), and a touch of JavaScript. The design follows accessibility best practices and includes a mobile-friendly navigation, interactive carousel, and a clean, minimal UI.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Mobile Screenshot](#mobile-screenshot)
  - [Desktop Screenshot](#desktop-screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Features](#features)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Mobile Screenshot

![](/images/screenshots/mobile-screenshot.png)

### Desktop Screenshot

![](/images/screenshots/desktop-screenshot.png)

### Links

- Live Site URL: [Manage Landing Page](https://fem-manage-landing-page-woad.vercel.app/)

## My process

### Features

- Responsive layout for mobile → desktop (grid + flexbox)
- Accessible mobile navigation (ARIA + keyboard-friendly)
- Accessible carousel using **a11y-slider** (CDN)
- Reusable utility classes and CSS custom properties
- SVG sprite icons and SVG `<use>` pattern
- CTA, newsletter form, and hero / sales / CTA sections

### What I Learned

---

#### Accessibility

- Using **ARIA attributes** (`aria-expanded`, `aria-controls`, `aria-label`) to improve screen reader and keyboard navigation.
- Implementing a `.visually-hidden` utility class for hidden but accessible text.
- Integrating an accessible carousel using **a11y-slider** instead of building a less accessible one from scratch.

#### Progressive Enhancement

- Building a **mobile navigation toggle** with `data-visible`, `aria-expanded`, and `data-overlay`.
- Enhancing UI with minimal, unobtrusive JavaScript.

#### Modern CSS

- Using **CSS custom properties** for consistent color, spacing, and typography scales.
- Creating **utility classes** (`.flow`, `.container`, `.even-columns`) to make CSS composable and reusable.
- Responsive layouts with **CSS Grid** and **Flexbox** powered by fluid media queries.

#### Component Styling

- Using **CSS counters** and pseudo-elements for numbered badges.
- Decorative backgrounds applied with `::before` and layered background images.

#### SVG & Assets

- Implementing **SVG sprites** with `<use>` for scalable, reusable icons.
- Optimizing icons for performance and crisp rendering.

#### JavaScript

- Selecting elements with `querySelector` and wiring up **event listeners**.
- Toggling attributes programmatically with `toggleAttribute`.
- Managing accessible state dynamically (`aria-expanded` updates).
- Instantiating and configuring a **third-party library** (`new A11YSlider(...)`) via CDN.

#### Tooling

- Getting started with **Vite** and ES module imports for faster development.
- Combining CDN assets with a modular workflow.

#### Best Practices

- Respecting **`prefers-reduced-motion`** for motion-sensitive users.
- Designing for different content widths with attribute-driven styling (`data-width="wide"`).
- Applying fluid spacing and responsive typography.

## Author

Github - [Lewis](https://github.com/Lewis-mbui)
