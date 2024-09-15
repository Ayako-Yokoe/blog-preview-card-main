# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Adjusting the image size for mobile was challenging.

### Screenshot

![1440px](./screenshot.jpg)
![375px](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/Ayako-Yokoe/blog-preview-card)
- Live Site URL: [Add live site URL here](https://blog-preview-card-ashy-one.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

When adjusting the size of the image, we need to set the width to 100% in the media query.

To see how you can add code snippets, see below:

```css
.blog-image {
  width: auto;
  height: 200px;
  ...;
}
```

```css
@media (max-width: 375px) {
  .blog-image {
    width: 100%;
    height: auto;
  }
}
```

### Continued development

I’d like to keep working on the minimum code needed to adjust sizes, such as for images and cards.
