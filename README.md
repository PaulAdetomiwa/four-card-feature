# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

- This is a solution to a four card feature section challenge on Frontend Mentor. It was made to be responsive, with the ability to view the optimal layout depending on their device's screen size. It also involved using CSS Grid, which is a very optimal way of arranging elements across th webpage

### Screenshot

![](desktop-layout.png)

### Links

- https://github.com/PaulAdetomiwa/product-preview-card-component/blob/main/index.html

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox 
- Media queries

### What I learned

```css
@media (max-width: 768px) {
      body {
        margin: 20px;
      }

      .container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        max-width: 400px;
      }

      .image-container {
        width: 100%;
      }

      .image-container img {
        border-radius: 15px 15px 0 0;
        height: 300px;
      }

      .text {
        width: 90%;
        padding: 0;
        margin: 20px 0 20px 5%;
      }

      .text h1 {
        font-size: 36px;
      }

      .text p {
        width: 93%;
      }

      .current-price {
        font-size: 36px;
      }
    }
```
- This is the media query for screens on or beneath the width of 768px. Major adjustments to the .container div in its flex direction, and font sizes of various of the text in the webpage.

- The width and heights of the elements were set using responsiveness-friendly metrics, mostly percentages.

## Author

- Website - [Paul Adetomiwa](https://github.com/PaulAdetomiwa)
- Frontend Mentor - [@PaulAdetomiwa](https://www.frontendmentor.io/profile/PaulAdetomiwa)
- X - [@AdewolePaul6](https://www.x.com/AdewolePaul6)