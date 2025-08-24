# Frontend Mentor - Bento Grid Solution

This is my solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj).  
The goal of this project was to build a responsive grid layout that adapts to different screen sizes, using semantic HTML and modern CSS techniques.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

---

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size (desktop, tablet, and mobile).
- See a clean and consistent design inspired by the provided mockup.

### Screenshot

![Screenshot of my solution](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/mohamad0ahmad/Bento-grid)
- Live Site URL: [Live Demo](https://your-live-site-url.com)

---

## My process

### Built with

- Semantic **HTML5** markup
- **CSS custom properties**
- **Flexbox**
- **CSS Grid**
- **Mobile-first workflow**
- **Google Fonts** (DM Sans)

### What I learned

This project helped me practice **CSS Grid areas** and how to rearrange them with **media queries** to achieve a responsive design.  
I also reinforced the idea of combining **utility classes** like `.grid` with custom styling to keep the CSS clean.

Example snippet:

```css
.bento-grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  grid-template-areas:
    "column1 column2 column3"
    "column1 column2 column3"
    "column1 column4 column4";
}
```
