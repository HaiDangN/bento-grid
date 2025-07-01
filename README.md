# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Desktop](/solution/solution-screenshot-desktop.png)
![Mobile](/solution/solution-screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/HaiDangN/bento-grid]
- Live Site URL: [https://haidangn.github.io/bento-grid/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned that it's better practice to lower the number of columns in a CSS grid to 1 instead of turning it into a flexbox.

I learned that if you have `overflow: hidden`, if an element doesn't have a defined size, it will collapse. It will appear to have dimensions in a css grid because it will copy the dimensions of the cells adjacent to it. 

I learned that images are `display: inline` by default. This means it's affected by text-alignment and line height and doesn't take up the full width of its parent. In most use cases, setting all images to `display: block` is correct.

Use `letter-spacing` to adjust the space between the letters in the text.