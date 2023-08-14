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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![product-preview-card-component-main](./images/productpreview.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/Kiunga1/product-preview-card-component-main.git)
- Live Site URL: [Add live site URL here](https://kiunga1.github.io/product-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
Image element with responsive design. Check code below :


```html
<picture class="product_img">
        <source srcset="images/image-product-desktop.jpg" media="(min-width:600px)">
        <img src="images/image-product-mobile.jpg" alt="Perfume">
      </picture>
```
CSS values and units -Relative length units

```css
.product_content {
  padding: 1.5rem;
  display: grid;
  gap: 1rem;
}
```

### Continued development

Media queries
Relative length units
More practise on different types of layouts.

### Useful resources

- [CSS values and unites on Mdm](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units) - This helped me to understand when to use rem and em. I really liked this and will use it going forward.

- [The CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This is an amazing article which helped me to sand down some of the rough edges in the CSS language. I'd recommend it to anyone still learning this concept.

-[Media queries](https://www.w3schools.com/css/css3_mediaqueries.asp) - This is an amazing article which helped me to make my page responsive. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Ann Mukami](https://www.your-site.com)
- Frontend Mentor - [@Kiunga1](https://www.frontendmentor.io/profile/Kiunga1)
- Twitter - [@AnnKiungaa](https://twitter.com/AnnKiungaa)



## Acknowledgments

Acknowledgement to [@fernandanevesf](https://www.frontendmentor.io/profile/fernandanevesf) on Frontend  Mentor. Thankyou for your feedback and sharing links of articles that have been very helpful.
