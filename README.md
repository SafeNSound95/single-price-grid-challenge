# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

This is my third challenge on the frontend mentor website, the task is to build a grid component component. I really liked this one because it got me to improve in many ways and learn new things while also implementing the things I've been learning along the way.

### Screenshot

![](2023-09-10-Frontend-Mentor-Single-Price-Grid-Component-1.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Grid for the overall layout, flex for the smaller containers.
this time I wanted to challenge myself with using grid-template-areas which I learned recently, I'm glad I decided to go this route and try something new.

### Built with

- HTML
- CSS
- Flexbox
- CSS Grid

### What I learned

I learned so much with this one:

- absolutely positioning the overall layout is not that good of an idea, especially with responsivness in mind.

- "fr" doesn't mean that the columns will stay equal if the content of one column gets bigger, we'd have to use something like minmax(0, 1fr) but that also comes with the risk of content overflowing so I decided against it, and I finally just gave an accruate width to the grid container which kept the columns equal.

and much more..

### Continued development

- I gotta read more on why absolute elements are not that good for responsivness.

- I had to set the link to display: block, cause with display: inline-block and padding it kept expanding and making the grid column much bigger than it needed to be, I need to read up more on why this behaviour happens.

## Author

- Frontend Mentor - [@SafeNSound95](https://www.frontendmentor.io/profile/SafeNSound95)
