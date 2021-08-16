# Frontend Mentor - Stats preview card component solution

This is a solution to the
[Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).
Frontend Mentor challenges help you improve your coding skills by building
realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections
you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop](./screenshots/desktop.PNG) 

### Links

- Solution URL: (https://github.com/HaylzRandom/stats-preview-card-component)
- Live Site URL: (https://haylzrandom.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS3
- SASS/SCSS
- Flexbox
- Mobile-first workflow

### What I learned

It was difficult to figure out how to get the image to be coloured with the
accent colour. After doing research and playing around with different
properties, I settled on the use of:

```background-color: $softViolet;
		background-image: url('./images/image-header-mobile.jpg');
		background-position: center;
		background-size: cover;
		background-repeat: no-repeat;
		background-blend-mode: multiply;
```

The `background-blend-mode: multiply` was the property that finally allowed the
violet colour to appear on the image

### Continued development

Would like to attempt this project again but using CSS grid to find out if that
is any easier or not.

In the future, I want to work on more of the following:

    - CSS Grid
    - Flexbox
    - Positioning
    - SASS/SCSS in general

### Useful resources

- [CSS-Tricks Background-blend-mode](https://css-tricks.com/almanac/properties/b/background-blend-mode/) -
  Mainly used this site for the spoken property but did use it to discover if
  certain things would work they way they would (they didn't!)
- [Mozilla MDN](https://developer.mozilla.org/en-US/) - Still my go to website
  for all things web development

## Author

- Website - [Hayley McCafferty](https://www.haylzrandom.co.uk/)
- Frontend Mentor -
  [@haylzrandom](https://www.frontendmentor.io/profile/HaylzRandom)
- Twitter - [@HaylzRandom](https://twitter.com/HaylzRandom)
