# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)  
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](.images/screenshot-desktop.png)

### Links

- Solution URL: [github.com/nikmaxott/sunnyside-agency-landing-page](https://github.com/nikmaxott/sunnyside-agency-landing-page)
- Live Site URL: [nikmaxott.github.io/sunnyside-agency-landing-page/](https://nikmaxott.github.io/sunnyside-agency-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- JavaScript

### What I learned

The JavaScript for this project is very simple, but I am particularly proud of my resizing reset. 
It's something that took a little time to perfect, so that the menu works properly.

```js
window.onresize = resetSize; 
  
function resetSize() {
  if (document.documentElement.clientWidth >= 500) {
    document.getElementById("menu").style.display = "flex";
  } else {
    document.getElementById("menu").style.display = "none";
  }
}
```

## Author

- Website - [Nikolaus Zolnhofer](https://www.nikmaxott.org)
- Frontend Mentor - [@nikmaxott](https://www.frontendmentor.io/profile/nikmaxott)
- Twitter - [@nikmaxott](https://www.twitter.com/nikmaxott)
