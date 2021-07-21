# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Create a button that when users hover on it will make it become outline. At first, I used the `border` property. But then, I realized this property will make the parent container change its size when I hover the button. Finally, I found `outline` property can help me. :D

```css
.btn {
  display: inline-block;
  border: none;
  cursor: pointer;
  padding: 0.5em 2em;
  background-color: var(--clr-white-900);
}

.btn:hover {
  color: var(--clr-white-900);
  background-color: transparent;
  outline: 2px solid var(--clr-white-900);
}
```

Another thing I learned from this exercise is how to make round button.

```css
.btn {
  /* omit for simplicity */
  border-radius: 25px;
}
```

### Useful resources

- [Some cool css buttons](https://saruwakakun.com/en/css3-buttons)

## Author

- Frontend Mentor - [@tttinh](https://www.frontendmentor.io/profile/tttinh)
