# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.png)

### Links

- [Solution URL](https://github.com/codercreative/stats-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I had a hard time adjusting the image for responsive layout.

In order to make the image fit, I had to use object-fit in the mobile version:

```css
img {
  /* avoid stretching the image --> */
  object-fit: contain;
}
```

For the desktop version, I had to use below code in order to avoid a thin purple line to the right of the image.

```css
img {
  object-fit: cover;
}
```

The above is a bit "hacky". Not sure what a better solution is at this point.

## Author

- Frontend Mentor - [@codercreative](https://www.frontendmentor.io/profile/codercreative)
