# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [What I learned](#what-i-learned)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/column%20preview.png)


### Links

- Solution URL: [NETLIFY URL](https://3-column-preview-card-component-gnr23.netlify.app/)
- Live Site URL: [GITHUB URL](https://github.com/gnr23/frontend-exercise-05-Column-preview-component)


### Built with

HTML, CSS
VS code

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

"the lower i am in the css file the more specifity there is"

scaling for bigger screens with media queries for columns:

e.g.

@media(min-width: 992px) {
    .container {
        display: flex;  
        align-items: center;
        justify-content: center;
        min-height: 100vh;
max-width: 900px;
margin:auto;
    }

