# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![QR Code Component Preview](./assets/images/preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive Design principles

### What I learned

During this project, I focused on creating a responsive QR code component that works well across different screen sizes. Some key learnings include:

- Using CSS custom properties for consistent styling:

```css
:root {
  --slate-900: hsl(218, 44%, 22%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-300: hsl(212, 45%, 89%);
}
```

- Implementing responsive design with media queries:

```css
@media (max-width: var(--mobile-width)) {
  .content {
    width: 90%;
    min-height: 450px;
  }
}
```

- Proper image handling for QR codes:

```css
.qr_image img {
  object-fit: contain;
  width: 100%;
  height: 100%;
}
```

### Useful resources

- [CSS Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand flexbox layout principles better.
- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - Great documentation for working with CSS variables.
- [Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries) - Helpful resource for implementing responsive design.
