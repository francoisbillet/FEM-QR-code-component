# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](images/screenshot-qr-code-2.png)

### Links

Live Site URL: [https://francoisbillet.github.io/QR-code-component/](https://francoisbillet.github.io/QR-code-component/)

## My process

### Built with

- HTML markup
- CSS custom properties

### What I learned

- To use a downloaded font, set a **rule** :

```css
@font-face {
    font-family: Outfit;
    src: url(fonts/Outfit-VariableFont_wght.ttf);
}
```
And then apply that font-family to an element

- To fit an image inside a div, set the image's *max-height* and *max-width* to 100% :

```css
.component img {
  max-width: 100%;
  max-height: 100%;
}
```

### Continued development

#### HTML
- For this component, should I use a simple ```<div>``` or a semantic element such as ```<section>``` ?
- What good practices can I use for naming classes ?

#### CSS:
- What good practices can I use for naming my custom properties ?
- How can I center vertically my ```<div>```, without adding a manual margin/padding or using flexbox/grid ?
- As a good practice, what properties should I set for *html* and *body* selectors ?
- What units should I use for different use cases ? Spacing, font sizing, etc.


### Useful resources

[Eric A. Meyer's CSS Reset](https://meyerweb.com/eric/tools/css/reset/) - This helped me resetting my browser's built-in CSS properties. However it is missing the *box-sizing: border-box* reset, which I added

## Author

Frontend Mentor - [@FunkyCreep](https://www.frontendmentor.io/profile/francoisbillet)
