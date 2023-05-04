# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

a. How to change image dynamically based on the viewport width:

```html
<picture>
  <source srcset="./images/image-product-desktop.jpg" media="(min-width: 600px)">
  <img src="./images/image-product-mobile.jpg" alt="Perfume Picture">
</picture>
```

## Acknowledgments

Thanks for the high-quality video made by Kevin Powell. Really helped me to get through some bottlenecks.
