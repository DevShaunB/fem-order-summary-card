# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Reference](#reference)
  - [Font](#font)
  - [Color](#color)
  - [Typography](#typography)
- [Run Locally](#run-locally)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Order summary card desktop screenshot](https://devshaunb.github.io/fem-order-summary-card/screenshots/desktop.png)

![Order summary card mobile screenshot](https://devshaunb.github.io/fem-order-summary-card/screenshots/mobile.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/order-summary-card-using-flexbox-and-utility-classes-ofCV_dVIZg](https://www.frontendmentor.io/solutions/order-summary-card-using-flexbox-and-utility-classes-ofCV_dVIZg)

- Live Site URL: [https://devshaunb.github.io/fem-order-summary-card/](https://devshaunb.github.io/fem-order-summary-card/)

## Reference

### Font

- Family: [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display)
- Weights: 500, 700, 900

### Color

#### Primary

- ![hsl(225, 100%, 94%)](https://via.placeholder.com/10/e0e8ff?text=+) `Pale blue: hsl(225, 100%, 94%)`
- ![hsl(245, 75%, 52%)](https://via.placeholder.com/10/3829e0?text=+) `Bright blue: hsl(245, 75%, 52%)`

#### Neutral

- ![hsl(225, 100%, 98%)](https://via.placeholder.com/10/f5f7ff?text=+) `Very pale blue: hsl(225, 100%, 98%)`
- ![hsl(224, 23%, 55%)](https://via.placeholder.com/10/7280a7?text=+) `Desaturated blue: hsl(224, 23%, 55%)`
- ![hsl(223, 47%, 23%)](https://via.placeholder.com/10/1f2f56?text=+) `Dark blue: hsl(223, 47%, 23%)`
- ![hsl(0, 0%, 100%)](https://via.placeholder.com/10/ffffff?text=+) `White: hsl(0, 0%, 100%)`

### Typography

#### Body Copy

- Font size (paragraph): 16px

## Run Locally

Clone the project

```bash
  git clone https://github.com/DevShaunB/fem-order-summary-card.git
```

Go to the project directory

```bash
  cd fem-order-summary-card/
```

Run `index.html`

```bash
  <browsername> index.html
```

E.g.

```bash
  firefox index.html
```

```bash
  google-chrome index.html
```

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom utility classes

### What I learned

- using background property to display a background image with a background color

```css
background: url('./images/pattern-background-mobile.svg') no-repeat top center, hsl(
    var(--clr-blue-100)
  );
```

- creating buttons with custom utility classes

```css
.btn {
  display: block;
  margin-inline: auto;
  font-weight: var(--fw-bold);
  background: none;
  color: inherit;
  border: none;
  cursor: pointer;
}

.btn-primary {
  width: 100%;
  background-color: hsl(var(--clr-blue-600));
  color: hsl(var(--clr-white));
  padding: 0.9375em;
  border-radius: 0.75em;
  box-shadow: 0 1rem 1rem 0 hsl(var(--clr-blue-600) / 0.15);
}

.btn-ghost:where(:hover, :focus-visible) {
  color: hsl(var(--clr-blue-800));
}
```

## Author

- Frontend Mentor - [@DevShaunB](https://www.frontendmentor.io/profile/DevShaunB)
- Twitter - [@DevShaunB](https://www.twitter.com/DevShaunB)

## Acknowledgments

- [Order summary card](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj) by [Frontend Mentor](https://www.frontendmentor.io/)
