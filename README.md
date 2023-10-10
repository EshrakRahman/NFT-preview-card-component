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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
- Desktop view

![](./screenshoots/desktopView.png)

- Active status

![](./screenshoots/activeStatus.png)

- Mobile view

![](./screenshoots/mobileView.png)

### Links

- Solution URL: [GitHub](https://github.com/EshrakRahman/NFT-preview-card-component)
- Live Site URL: [GitHub page](https://eshrakrahman.github.io/NFT-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow


### What I learned

During my journey with **Frontend Mentor**, I delved deep into several foundational CSS concepts, enhancing both my understanding and practical skills.

#### Flexbox:
This powerful layout model allowed me to craft complex layout structures with a more efficient and predictable way than traditional models. I grasped properties like `justify-content`, `align-items`, and `flex-direction`. Flex containers simplified intricate layouts, making the design more responsive and the code neater.

#### Positioning:
I refined my grasp on the `position` property, learning to control element placement. By experimenting with values like `relative`, `absolute`, `fixed`, and `sticky`, I could achieve layouts with pinpoint accuracy.

#### Image Overlay:
Mastering image overlays was particularly enlightening. Through a mix of positioning and other CSS techniques, I created effects by superimposing backgrounds and icons on images. The use of `hsla` allowed me to make semi-transparent backgrounds, balancing visibility between overlay content and the underlying image.

In conclusion, this challenge enriched my technical skill set, elevating my confidence in crafting responsive and aesthetic web designs.


To see how you can add code snippets, see below:

```html
<div class="main-img">
  <img class="eb-image" src="images/image-equilibrium.jpg" alt="Equilibrium product image dark blue color">
  <div class="overlay">
    <img src="images/icon-view.svg" alt=" " class="hover-icon">
  </div>
</div>
```
```css
.main-img .overlay{
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 1;
  border-radius: 10px;
  background-color: hsla(178, 100%, 50%, 25%);
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: opacity 0.3s;
}

.main-img .overlay img{
  width: 40px;
  height: 40px;
}
.main-img:hover .overlay {
  opacity: 1;
  cursor: pointer;
}
```


### Continued development

In forthcoming projects, I aim to delve deeper into responsive design methodologies, ensuring consistent user experiences across all devices. Flexbox and Grid layouts, though familiar, still pose intricate challenges that I wish to master. I've found JavaScript animations intriguing and plan to integrate them more seamlessly into my designs. Additionally, accessibility remains a crucial focus. I recognize the importance of inclusive web design, and I'm determined to learn techniques that cater to all user needs. Lastly, I intend to explore performance optimization, ensuring that the websites I build are not just visually appealing but also efficient. Each project presents a learning curve, and I'm enthusiastic about climbing higher on every turn.


## Author

- Website - [GitHub](https://github.com/EshrakRahman)
- Frontend Mentor - [@eshrakrahman](https://www.frontendmentor.io/profile/eshrakrahman)

