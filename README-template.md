# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Tablet View](images\screenshot.png)

### Links

- Solution URL: [Source code](https://github.com/ceesiyamoah/loopstudios-landing-page-main)
- Live Site URL: [Live website](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

How to use grid

To see how you can add code snippets, see below:

Grid for layout

```css
.creation__main {
	display: grid;
	grid-template-rows: repeat(2, 1fr);
	grid-template-columns: repeat(4, 1fr);
	justify-content: space-between;
	gap: 20px;
}
```

Media queries for responsive design

```css
@media only screen and (max-width: 68.75em) {
	display: flex;
	flex-direction: column;
}
```

Block element modifier (BEM) Naming scheme

```css
.nav {
	&__items {
		background-color: #fff;
	}
	&__link {
		padding: 2rem;
		&__link--left {
			margin-right: auto;
		}
	}
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

- Grid for responsive design
- Transition timing functions
- Responsive images

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Website - [Cyril Yamoah](https://cyrilyamoah.netlify.app/)
- Frontend Mentor - [@ceesiyamoah](https://www.frontendmentor.io/profile/ceesiyamoah)
- Twitter - [@Siisi_Any](https://twitter.com/Siisi_Any)
