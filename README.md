# Base-apparel-coming-soon-master--Frontend-Mentor
# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot
#### Desktop View
![](./Base%20Apparel%20coming%20soon%20page%20-%20desktop%20solution.png)
#### Mobile View
![](./Base%20Apparel%20coming%20soon%20page%20-%20mobile%20solution.png)

### Links

- Solution URL: [View solution URL here](https://github.com/preciousvictory/Base-apparel-coming-soon-master--Frontend-Mentor)
- Live Site URL: [View live site URL here](https://preciousvictory.github.io/Base-apparel-coming-soon-master--Frontend-Mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox
- Js

### What I learned

- I learnt how to space the letters not just the default spacing using letter-spacing.
```css
.col-1 h1{
    font-size: 60px;
    font-weight: 600;
    letter-spacing: 18px;
}
```
- I also learnt how to stack/ overlap two elements together using the position property.
I gave the parent element `position: relative` then I gave the child element `position: absolute`, Then specifying the exact position using the values (left, right, top, bottom).
```css
.col-1 form{
    position: relative;
    width: 80%;
}

.col-1 .child{
    position: absolute;
}

.col-1 .email{
    left: 0;
    top: 0;
    ...
}
```

-   I also learnt how to use gradient. 
```css
.col-1 .button{
    background-image: linear-gradient(135deg, hsl(0, 80%, 86%), hsl(0, 74%, 74%));
    ...
}
```

- I also learnt how to make images reponsive in css using backgroung-image property.
```css
.col-2{
    background-image: url(../images/hero-desktop.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

@media screen and (max-width: 600px) {
   .col-2{
        background-image: url(../images/hero-mobile.jpg);
    }
}
```

```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```
### Continued development

- CSS Grid
- JS form validation

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient) - This helped me for learn how to use linear gradients. 
- [Example resource 2](https://css-tricks.com/how-to-stack-elements-in-css/) - This is an amazing article which helped me finally understand how to stack more than more elements on each other. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Abiodun-Omoniyi Victory](https://preciousvictory.github.io/order-summary-component-main-frontendmentor/)
- Frontend Mentor - [@preciousvictory](https://www.frontendmentor.io/profile/preciousvictory)
- Twitter - [@preciousvicky_](https://www.twitter.com/preciousvicky_)
