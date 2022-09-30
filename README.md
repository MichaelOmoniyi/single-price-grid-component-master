# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/Screenshot_desktop_2022-09-30%20at%2010-52-10%20Frontend%20Mentor%20Single%20Price%20Grid%20Component.png)

![](./images/Screenshot_mobile_2022-09-30%20at%2010-52-51%20Frontend%20Mentor%20Single%20Price%20Grid%20Component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I focused on the Html section first. Before moving to style the mobile view, categorizing into section, styling appropriate padding and margin, styling font-size, styling appropriate backgrounds. Then I moved to adjust the styles for the desktop view.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I learnt the use of Css grid.


```css
    .cardBox {
        display: grid;
        grid-template-areas: "a a" "b c";
    }
    .section1 {
        grid-area: a;
    }
    .section2 {
        grid-area: b;
    }
    .section3 {
        grid-area: c;
}
```

### Continued development

I'd love to master the use of Css grid and know how and when to use it.

### Useful resources

- [Example resource 2](https://www.w3schools.com) - This is an amazing website, which helped me understand css grid better. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Michael Omoniyi](https://www.your-site.com)
- Frontend Mentor - [@MichaelOmoniyi](www.frontendmentor.io/profile/MichaelOmoniyi)
- Twitter - [@Omons_Mikel](https://twitter.com/Omons_Mikel)