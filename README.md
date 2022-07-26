# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Skilled e-learning landing page solution](#frontend-mentor---skilled-e-learning-landing-page-solution)
  - [Table of contents](#table-of-contents)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Mobile Screenshot](./codebase/assets/ss-mobile.png)
![Tablet Screenshot](./codebase/assets/ss-tablet.png)
![Desktop Screenshot](./codebase/assets/ss-desktop.png)


### Links

- Solution URL: [GitHub Repository](https://github.com/varonalearns/Skilled-elearning-landing-page)
- Live Site URL: [Vercel Live Site](https://skilled-elearning-landing-page-mauve.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- That I can store linear-gradient()s in a CSS variable! I don't know why I did not think about that before but while I setting up my default/global values in styles.css I wondered if it was possible and it was!

- That linear-gradient() belongs to the background-image property. I was banging my head on how to get a white to light blue gradient to work only to realize that I was using the wrong the property. I also placed a fallback color just in case the gradient doesn't end up working on a browswer. 

```
#courses {
    background-color: rgb(240, 241, 255); /* fallback if gradient doesn't work */
    background-image: linear-gradient(to bottom, rgb(255, 255, 255), rgb(240, 241, 255) 10%);
}
```

### Continued development

- Something that I want to be more cognizant of is providing fallback styles just in case whatever I created in CSS doesn't end up working. IE might be dead but it never hurts to be safe!

- I hade an incredibly difficult time trying to make the hero image function in the way that I needed to until I realized I needed to use position and z-index to get the effect that I wanted to get with the CSS. Definitely something to develop further in the future.

- I also want to work on making my elements even more response. Because I was stumped and running out of time to make the practice site fully responsive, that is something that I want to keep in mind going into my next projects.

### Useful resources

- [Linear Gradients](https://css-tricks.com/css3-gradients/) - This article helped me to understand how CSS linear-gradients work. 


## Author

- Website - [Evalia Varona](https://www.evaliavarona.com)
- Frontend Mentor - [@varonalearns](https://www.frontendmentor.io/profile/varonalearns)
- Hashnode - [@evavarona](https://evaliavarona.hashnode.dev/)