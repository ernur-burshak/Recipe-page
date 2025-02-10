# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [solution URL here](https://github.com/ernur-burshak/Recipe-page)
- Live Site URL: [live site URL here](https://ernur-burshak.github.io/Recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I expanded my knowledge of using HTML, and adapted the site to a computer, tablet, and mobile phone. It looks different on each device.

```css
@media (min-width: 768px) and (max-width: 1024px) {
  .container {
    width: 100%;
    max-width: 616px;
  }
}

@media (max-width: 767px) {
  .container {
    width: 100%;
    max-width: 375px;
    padding: 0;
  }
}
```

```css
.line {
  width: 100%;
  height: 1px;
  background-color: #e3ddd7;
}
```

```html
<div class="table">
  <div class="row">
    <div class="cell">Calories</div>
    <div class="cell"><b class="brown">277kcal</b></div>
  </div>

  <div class="line"></div>

  <div class="row">
    <div class="cell">Carbs</div>
    <div class="cell"><b class="brown">0g</b></div>
  </div>

  <div class="line"></div>

  <div class="row">
    <div class="cell">Protein</div>
    <div class="cell"><b class="brown">20g</b></div>
  </div>

  <div class="line"></div>

  <div class="row">
    <div class="cell">Fat</div>
    <div class="cell"><b class="brown">22g</b></div>
  </div>
</div>
```

### Continued development

In the future, I want to create non-centered sites.

### Useful resources

- [resource 1](https://chatgpt.com/) - He helped me with coding and learning additional theory.
- [resource 2](https://www.frontendmentor.io/) - It always helps to find practice and improve your skills.

## Author

- Website - [Ernur](https://ernur-burshak.github.io/Recipe-page/)
- Frontend Mentor - [@ernur-burshak](https://www.frontendmentor.io/profile/ernur-burshak)
