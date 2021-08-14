# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Live Site URL: [Preview Site](https://patricia-hurst.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

More practice with manipulating box-shadows to help highlight and/or add contrast to certain elements. In this particular project I added a box-shadow around the entire card element in order to add some contrast between it and the background colors, as shown below:

```css
.card {
    /* other styles */
    box-shadow: 0 0 3px rgba(0, 0, 0, 0.3);
}
```

Note that we aren't using the X or Y offsets, allowing us to surround the entire element with the box-shadow.

I also added a small box-shadow directly beneath the 'Proceed to Payment' button to add some contrast.

```css
.btn--purple {
	/* other styles */
    box-shadow: 0 15px 20px -15px rgb(64, 82, 97);
}
```

Note the use of spread to make it appear as if the box-shadow is only on one side (in this case, the bottom).

### Continued development

Work on implementing BEM naming conventions and practices. Separate CSS into sections (layout, utilities, global, etc). Keep CSS dry!

## Author

- GitHub - [Patricia Hurst](https://github.com/patricia-hurst)
