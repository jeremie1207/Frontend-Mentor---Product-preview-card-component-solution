# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/jeremie1207/Frontend-Mentor---Product-preview-card-component-solution)
- Live Site URL: [Add live site URL here](https://jeremie1207.github.io/Frontend-Mentor---Product-preview-card-component-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

One of the most important things I learned during this project was how to make images responsive using the <picture> element. This technique allows you to serve different image files depending on the user's screen size, which improves performance and design adaptability across devices.

Here’s the code I used and am proud of:

```html
<picture class="product__image">
  <source media="(min-width: 620px)" 
          srcset="./images/image-product-desktop.jpg">
  <img src="./images/image-product-mobile.jpg" 
       alt="Perfume bottle on a gray background with vegetation">
</picture>
```

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.


