# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

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
- BEM css methodology

### What I learned

1. Image overlay in hover:

```html
<div class="image__container">
  <img
    class="image"
    src="images/image-equilibrium.jpg"
    alt="Equilibrium-Image"
  />
  <div class="image__overlay"></div>
</div>
```

```css
.image__container {
  position: relative;
}

.image {
  width: 100%;
  height: 100%;
}

.image__overlay {
  position: absolute;
  opacity: 0;
  transition: 0.5s ease;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(0, 255, 255, 0.202);
  width: 100%;
  height: 100%;

  &:hover {
    opacity: 1;
  }
}
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.


### Useful resources

- [How TO - Image Hover Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me for Image Hover Overlay.
- [BEM](https://www.frontendmentor.io/learning-paths/advanced-css-techniques-vdOtKjIC4V/article/66684b7c983369c533d01c96/read) - This is an amazing article which helped me understand BEM.

## Author

- Website - [Farzaneh Kazemi](https://verdant-bienenstitch-220a6d.netlify.app/)
- Frontend Mentor - [@Farzane2630](https://www.frontendmentor.io/profile/Farzane2630)
- StackOverflow - [@farzane-kazemi](https://stackoverflow.com/users/19888516/farzane-kazemi)

## Acknowledgments

