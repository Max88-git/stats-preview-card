# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

The code in this repository was created from frontendmentor.com so it is not part of a bigger project. Please feel free to use any parts of it should you find it of value.

If you're looking for a good challenge check out frontendmentor.com they have lots of really good challenges.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Design screenshot for the Stats preview card component coding challenge](./design/screenshot.jpg)

### Links

- Solution URL: [Solution](https://github.com/Max88-git/stats-preview-card)
- Live Site URL: [Live Site](https://max88-git.github.io/stats-preview-card/)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned a lot about the differences between images and background-images and how they impact the layout. I also used CSS variables for the first time using :root pseudo-class, so that it can be applied globally across your HTML document. 

I learnt how to display items in the container in reverse order using flex-direction: row-reverse, which can be seen in the below snippet.

```css
@media (min-width: 768px) {
	.container {
		display: flex;
		flex-direction: row-reverse;
		align-items: center;
		justify-content: center;
		padding: 0;
		text-align: left;
	}
```

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Ordering_Flex_Items) - This helped me figure out how to control the order of content for medium devices. I really liked the simple diagrams for demonstrating how to order flex items.

## Author

- Website - [Max Lockwood](https://www.maxlockwood.uk/)
- Frontend Mentor - [@Max88-git](https://www.frontendmentor.io/profile/Max88-git)

