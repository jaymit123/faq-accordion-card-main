# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [https://www.frontendmentor.io/solutions/mobile-first-approach-for-faq-accordion-card-with-only-css-u3UwyUQM5](https://www.frontendmentor.io/solutions/mobile-first-approach-for-faq-accordion-card-with-only-css-u3UwyUQM5)
- Live Site URL: [https://jaydesai-faq-accordion-main.netlify.app/](https://jaydesai-faq-accordion-main.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SCSS



### What I learned

1. Using Absolute child element in relative parent
2. Context stacking with abolute and relative element - Z-Index 
3. Using percentages to center child component (shouldn not be relied on though)
4. Creating Accordion without JS
5. Color and Typography in SCSS
6. Gradients in SCSS
7. Setting the css by different screen size rather then percentages, makes things easier. dont rely on calc function to much for responsiveness
8. Dont use vh for setting height of main components, instead use rem to make sure its value is same


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

Refine responsive CSS across different height for same width. Eg ipad pro, has different height then desktop browser.
Manage height of components using vh or percentage or fixed ?

### Useful resources

- [Gradients in CSS](https://css-tricks.com/css3-gradients/) - Learnt about graidents in CSS
- [Using Gradients with SCSS](https://medium.com/@alvaro.saburido/applying-gradient-trends-in-sass-cf825d70f5fe) - Using SCSS with Linear Gradients
- [Colors in design systems](https://medium.com/codyhouse/create-your-design-system-part-3-colors-798e4729921f) - How to manage colors in your web projects
- [Variables in CSS vs SASS](https://css-tricks.com/difference-between-types-of-css-variables/) - Difference between SASS and CSS Variables
- [Details HTML5 Tag for Accordions and its drawbacks](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) - Introduction to HTML5 implementation of Accordion, has styling limitations but has a lot of capabilities to be considered for future implementation. is A11y compliant.
- [Create Accordion without JS](https://stackoverflow.com/questions/13630229/can-i-have-an-onclick-effect-in-css) - Great learning on how to implement Accordions withou JS

- [Rotate Background using Transform](https://www.sitepoint.com/css3-transform-background-image/)
- [nesting pesudo elements in SCSS](https://marksheet.io/sass-nesting.html)
- [Centering SVG Inside DIV](https://stackoverflow.com/questions/41822510/center-an-svg-inside-a-div) - Important one to center Avatar on top of FAQ card
- [Guide on using Calc CSS](https://css-tricks.com/a-complete-guide-to-calc-in-css/)
- [Why doesnt percentage work in height](https://stackoverflow.com/questions/5657964/css-why-doesn-t-percentage-height-work)
- [Scoping variables in BEM](https://css-tricks.com/using-sass-control-scope-bem-naming/)
- [a CSS Only Solution to :hover on Touchscreens](https://dzone.com/articles/finally-a-css-only-solution-to-hover-on-touchscree)
- [SASS Media Queries](https://css-tricks.com/approaches-media-queries-sass/)
## Author

- Website - [Jaymit Desai](https://www.jaymitdesai.com)
- Frontend Mentor - [@jaymitd](https://www.frontendmentor.io/profile/jaymitd)
- Github - [@jaymit123](https://github.com/jaymit123)


