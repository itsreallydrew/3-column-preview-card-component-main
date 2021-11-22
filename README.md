# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

CSS challenge practice creating a responsive three column layout.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot


![Desktop View](https://user-images.githubusercontent.com/88289750/142784297-af9555ec-bda4-412b-afc0-448ba5bbb400.png)

### Links

- Solution URL: [Solution Link](https://www.frontendmentor.io/solutions/responsive-3-column-card-built-with-css-grid-z9Xh3FKh4)
- Live Site URL: [Live Site](https://suspicious-pasteur-b73c61.netlify.app)

## My process

Started with a mobile-first workflow. I should have done this on the other projects but I decided that this would be a better approach moving forward after looking at suggestions from others.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

After approaching this from a mobile-first workflow I realized how much easier it is to make adjustments with media queries. I don't have to make as many queries to cause modifications and results in the finished product being completed quicker, as well as significantly less code needing to be written.

Example of media queries to adjust for breakpoints:

I realize now that I probably could have saved these as a mixin to dry up the code some more.

```css
@media only screen and (min-width: $medium) {
	height: 50vh;
	width: 90vw;
	display: grid;
	grid-template-columns: repeat(3, 1fr);
}
@media only screen and (min-width: $desktop) {
	height: 50vh;
	width: 50vw;
	display: grid;
	grid-template-columns: repeat(3, 1fr);
}
```

### Continued development

It seems to be the theme but I want to keep improving as I use grid. One of the major things I learned was the importance and flexibility of vw and vh. I probably stated this in the last project but the more I use them I see how valuable they are. Setting a fixed height or width prevents any sort of responsiveness. I'm becoming a lot more comfortable with using them.

## Author

- Frontend Mentor - [@itsreallydrew](https://www.frontendmentor.io/profile/itsreallydrew)
