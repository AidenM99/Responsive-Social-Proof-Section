# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

- Recreate the social proof section as accurately as possible according to the design specifications provided.

### Screenshot

![](./Solution.png)

### Links

- Live Site URL: https://aidenm99.github.io/Responsive-Social-Proof-Section/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap 4

### What I learned

- How to use columns in bootstrap in order to accurately place content on the page

```html
<div class="col-lg-6">
<div class="col-lg-4 col-md-6">
```

- How to use media queries to fine tune a responsive design where bootstrap columns cannot

```css
@media (max-width:1100px) {
  .reviews:first-child {
    transform:translateX(0);
  }

   .reviews:last-child {
    transform:translateX(0);
  }

}

@media (max-width:991px) {
  body {
    text-align: center;
  }

  .reviews {
    min-width:0;
    text-align: center;
    margin:0 auto 20px;
  }

  .reviews:first-child {
    transform:translateX(0);
  }

   .reviews:last-child {
    transform:translateX(0);
  }

  .star {
    margin:auto;
  }

  b {
    display:block;
    margin:10px 0 0;
  }

}
```

- How to use the transform property to manipulate elements on the screen

```css
 .reviews:last-child {
  transform:translateX(30px);
}
```

- How to select an item using first child, last child and nth child 

```css
.reviews:first-child {
  transform:translateX(-30px);
}

 .reviews:last-child {
  transform:translateX(30px);
}

.reviews:nth-child(2) {
  transform:translateX()
}
```

### Continued development

- I plan to learn how to utilise the grid property within Bootstrap to allow for greater ease of laying out webpages and to achieve a fully responsive design on all devices.

## Author

- Frontend Mentor - [@AidenM99](https://www.frontendmentor.io/profile/AidenM99)

