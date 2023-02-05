# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/single-price-grid-component-using-css-grid-_f0-y_slJ5)
- Live Site URL: [Github Pages](https://delanohendrix.github.io/Single-Price-Grid-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In order to use CSS Grid the way I wanted to, I needed to make sue each section was its own seperate entity. To achieve this I chose to use the div with the class content as the container with a grid display. From there I was able to align everything easily while making sure each section was uniform to a certain extent.

```html
<div class="container">
  <div class="content">
    <section>
      <div class="section1-content">
        <h2>Join our community</h2>
        <h3>30-day, hassle-free money back guarantee</h3>
        <p>
          Gain access to our full library of tutorials along with expert code reviews. Perfect for
          any developers who are serious about honing their skills.
        </p>
      </div>
    </section>
  </div>
</div>
```

### Continued development

I would possibly like to redo this project at a later date likely using SASS; as I felt it would fit nicely with how I approached it.

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)

## Acknowledgments

I would like to acknoledge w3 Schools, as I used one of their animated buttons in conjunction with my code. The specific button and code can be found here: [w3 Schools](https://www.w3schools.com/css/tryit.asp?filename=trycss_buttons_animate1)
