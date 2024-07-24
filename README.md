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

![Screenshot](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Vue
- SCSS
- Custom CSS properties

### What I learned

I've learned how to calculate the inner and outer `border-radius` and used this technique in this project:

```css
.qr-code-card {
  --padding: var(--spacing-200);
  --inner-border-radius: 10px;

  padding: var(--padding);
  border-radius: calc(var(--inner-border-radius) + var(--padding));

  img {
    border-radius: var(--inner-border-radius);
  }
}
```

I also used Figma.

### Useful resources

- [Get your stylesheets more organized with Sass partials](https://www.youtube.com/watch?v=9Ld-aOKsEDk) - My SCSS folder structure is inspired by this video.
