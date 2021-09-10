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

1. Desktop Design
![FEM-three-column-card(1)](https://user-images.githubusercontent.com/84383548/132902781-c629d0aa-c5f7-418d-a7cd-dae12f2e6b69.png)

1. Mobile Design <br>
![FEM-three-colunm-card(2)](https://user-images.githubusercontent.com/84383548/132902794-f273302b-6e3e-4121-8b6d-9174b11af611.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My Process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- CSS flexbox
- CSS grid
- CSS absolute and relative positioning
- CSS before and after Pseudo elements
- HTML5 Markup

Some HTML code from the project

```html
<main id="card">
  <div class="card__sedans">
    <img src="./images/icon-sedans.svg" alt="sedans icon" />
    <h1>Sedans</h1>
    <p>
      Choose a sedan for its affordability and excellent fuel economy. Ideal for
      cruising in the city or on your next road trip.
    </p>
    <a href="#">Learn More</a>
  </div>

  <div class="card__suvs">
    <img src="./images/icon-suvs.svg" alt="suvs icon" />
    <h1>Suvs</h1>
    <p>
      Take an SUV for its spacious interior, power, and versatility. Perfect for
      your next family vacation and off-road adventures.
    </p>
    <a href="#">Learn More</a>
  </div>

  <div class="card__luxury">
    <img src="./images/icon-luxury.svg" alt="luxury icon" />
    <h1>Luxury</h1>
    <p>
      Cruise in the best car brands without the bloated prices. Enjoy the
      enhanced comfort of a luxury rental and arrive in style.
    </p>
    <a href="#">Learn More</a>
  </div>
</main>
```

Some CSS code from the project

```css
#card p {
  color: var(--trans-whtie-paragraph);
}

#card a {
  width: 8rem;
  text-align: center;
  text-decoration: none;
  border: 1px solid var(--light-gray-bg-h-b);
  background-color: var(--light-gray-bg-h-b);
  border-radius: 2rem;
  padding: 0.5rem;
}

#card .card__sedans {
  background-color: var(--bright-orange);
  display: grid;
  align-items: center;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
  padding: 1rem 2rem;
}

#card .card__sedans > * {
  margin-bottom: 1rem;
}

#card .card__sedans > p {
  margin-bottom: 2rem;
}

#card .card__sedans > a {
  color: var(--bright-orange);
}
```

## Author

- Twitter - [@abanicaisse](https://www.twitter.com/abanicaisse)
- Frontend Mentor - [@abanicaisse](https://www.frontendmentor.io/profile/abanicaisse)
- CodePen - [My codepen](https://www.codepen.io/Nicaisse)
