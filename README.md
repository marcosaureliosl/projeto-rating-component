# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
![Design sem nome](https://github.com/marcosaureliosl/projeto-rating-component/assets/127764997/804c27f5-ee4b-4cb7-8adb-04f4ad722976)

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


### Links

- Solution URL: [projeto-rating-component](https://marcosaureliosl.github.io/projeto-rating-component/)
- Live Site URL: [meu GitHub](https://github.com/marcosaureliosl/projeto-rating-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow




### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1><Div class="card">
    <div class="card_container">
      <div class="rating_section">
        <div class="star_icon">
          <img src="./images/icon-star.svg" alt="star">
        </div></h1>
```
```css
:root {
  --Orange: hsl(25, 97%, 53%);
  --White: hsl(0, 0%, 100%);
  --Light-Grey: hsl(217, 12%, 63%);
  --Medium-Grey: hsl(216, 12%, 54%);
  --Dark-Blue: hsl(213, 19%, 18%);
  --Very-Dark-Blue: hsl(216, 12%, 8%);
  --secondary: hsl(213deg, 20%, 22%);
}
```
```js
const rating_cards = document.querySelectorAll(".ratings span");
const submit_btn = document.querySelector(".submit_btn");
const rate_point = document.getElementById("rate");
const rating_section = document.querySelector(".rating_section");
const thank_section = document.querySelector(".thank_section");
let rate = null;
```



### Continued development
Quero me desenvolver mias na liguagem do JavaScript,  tentar trazer mais soluções neste caminho



## Author

- Frontend Mentor - [@marcosaureliosl](https://www.frontendmentor.io/profile/marcosaureliosl)
- Twitter - [@marcosaureliosl](https://www.twitter.com/marcosaureliosl)



## Acknowledgments

Obrigado a todos que me da apoio.
