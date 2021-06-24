
# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/desktop_screenshot.jpg)

![](./images/mobile_screenshot.jpg)


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


### What I learned

I experimented with CSS Grid where my goal was to make the project fully responsive using media queries as little as possible

To see how you can add code snippets, see below:

```html
<div  class="col">
   <div  class="col--1">
      <h1  class="col__heading">Sedans</h1>
      <p  class="col__text">Choose a sedan for its affordability...</p>
      <a  class="btn orange">Learn more</a>
   </div>
</div>
```
```css
.col  {
  /* ... */
  display:  grid;
  grid-template-columns:  repeat(auto-fit,  minmax(20rem,  1fr));
  /* ... */
}
```


### Continued development

Planning on using more CSS Grid and Flexbox, to improve the overall workflow and maintainability of the code. Also considering on researching about media queries and responsive web development

### Useful resources

- [stackedit.io](https://stackedit.io/) - This website helped me to write my markdown files faster and easier, highly recommended.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://github.com/kens-visuals)
- Frontend Mentor - [@kens-visuals](https://www.frontendmentor.io/profile/kens-visuals)
- Twitter - [@kens_visuals](https://twitter.com/kens_visuals)



