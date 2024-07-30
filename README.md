# Frontend Mentor - Product list with cart solution

This is a solution to the [Product list with cart challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-list-with-cart-5MmqLVAp_d). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Some Challenges I Faced](#some-challenges-i-faced)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Add items to the cart and remove them
- Increase/decrease the number of items in the cart
- See an order confirmation modal when they click "Confirm Order"
- Reset their selections when they click "Start New Order"
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [https://github.com/915fonzie/product-list-with-cart-main](https://github.com/915fonzie/product-list-with-cart-main)
- Live Site URL: [https://fonzies-dessert-menu.netlify.app/](https://fonzies-dessert-menu.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- SASS
- Flexbox
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Styled Components](https://styled-components.com/) - For styles


### Some Challenges I Faced

The first problem I came across was how to dynamically change the src of images for the desserts depending on size. In order to solve this issue, I learned of a way to create a custom hook that would import an image based off the url given.

The next challenge that I encountered was a bug that I created when managing state which caused some child components of that parent component to not rerender even though the props were changing inside that parent component. In diving deeper in learning about how rerenders are handled, I realized that I was using the same reference for an object when trying to change state which react then didn't recognize a change. I had to create a new instance of that reference to cause a change to state and that fixed the issue.

### Continued development

I want to continue learning about creating custom hooks and going more in depth with how react works under the hood.

## Author

- Website - [Alfonso Pruneda](https://www.fonziepruneda.com)
- Frontend Mentor - [@915fonzie](https://www.frontendmentor.io/profile/915fonzie)
- Twitter - [@915fonzie](https://www.twitter.com/915fonzie)

