# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents✒️

- [Overview](#overview)🎯
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)🧩
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)🙋🏻

## Overview🎯

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![image](https://user-images.githubusercontent.com/86482525/126371106-15151bdf-e031-4235-b4a5-bb10d6c3ef8c.png)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/fylo-data-storage-component-made-with-html-and-css-8SVL89bga)
- Live Site URL: [Live site](https://alvaro-j.github.io/fylo-data-storage-component/)

## My process🧩

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Use <b>CSS variables</b> to optimize the development: in this case, i defined the site colors.
```css
:root {
  --pale-blue: hsl(243, 100%, 93%);
  --grayish-blue: hsl(229, 7%, 55%);
  --dark-blue: hsl(228, 56%, 26%);
  --very-dark-blue: hsl(229, 57%, 11%);
  --light-pink: hsl(6, 100%, 80%);
  --pink: hsl(335, 100%, 65%);
}
```
- Use <b>CSS background shorthand</b> to simplify the code.
```css 
body {
  background: var(--very-dark-blue) url(images/bg-desktop.png) no-repeat fixed bottom;
}
```
### Useful resources

- [Speech bubbles](http://nicolasgallagher.com/pure-css-speech-bubbles/) - This is an amazing article which helped me finally understand how to make speech bubbles. I'd recommend it to anyone who wants to understand this concept.

## Author🙋🏻

- Website - [Álvaro J.](https://www.github.com/alvaro-j/)
- Frontend Mentor - [@alvaro-j](https://www.frontendmentor.io/profile/alvaro-j)
