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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMthreeColumnCard)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMthreeColumnCard)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

The challenge was relatively easy. I used pseudo selectors to color the cards. For the buttons I used a border-radius higher than the height of the button to ensure a perfect semi-circle for the edge without getting an eliptical button. For the hover state used an inset box-shadow instead of a border to avoid enlarging the button.

```css
.container .card:first-child {
  background-color: #e38826;
  border-radius: 5px 5px 0 0;
}
.container .card:nth-child(2) {
  background-color: #006970;
  border-radius: 0;
}
.container .card:last-child {
  background-color: #004241;
  border-radius: 0 0 5px 5px;
}
```

```css
.btn {
  font-size: 15px;
  padding: 12px 27px;
  border-radius: 100px;
}
```

```css
btn:hover {
  box-shadow: 0px 0px 0px 2px #fff inset;
}
```

## Author

- Ayula Boyilo
