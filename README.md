# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/testimonials.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I built this design as mobile-first and used media queries for larger screen sizes. When building mobile first, writing the HTML knocks out about half of the process. Structuring the design with `divs` that will allow targeted styling makes things easier.
In writing the CSS, I utilized Flexbox and CSS Grid to structure and separate each testimonial. I knew I wanted to use grid-areas to place the testimonials in a dynamic way at larger screen sizes. On the first try however, I was running into issues because I had defined grid-template-rows and grid-template-columns explicitly. After doing some more research, I learned that these don't have to be defined explicitly. You can set up the grid areas, and in this way the rows and columns are implicitly defined.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I wanted to practice CSS grid and Flexbox to reproduce a clean, dynamic layout. I tried to give a class to as many elements as possible in order for CSS to be understood clearly, and to be able to target styles to specific elements. I learned about positioning and best practices for grid setup.

### Continued development

I want to practice more with device-width cutoffs and grid responsiveness. I attempted to use the auto-fit and auto-fill properties, along with minmax, but I didn't quite have a grasp on this. I want to get some more practice with these in order to make dynamic grids that look great on different screen sizes.
I also want to continue learning about positioning. I was able to place background image close to the top right corner in the first testimonial just by using `background position`, but that won't always be an option. I want to learn more about absolute/fixed/relative positioning, z-index, negative margins, etc. to better able place elements on a page.

### Useful resources

While continuing to learn more about positioning, I found a useful article in CSS Tricks that helped me with positioning of the background image. I learned that you can give up to four values to position the element. These will determine horizontal and vertical placement as well as any offset from that placement.
After reaching my original solution, I found a great Kevin Powell YouTube - it is actually coding this exact project! But this is where I learned how to fix the grid responsiveness issue. I had explicitly defined rows and columns, and that made redefining grid areas more challenging. I merely had to snip a few lines of code and add a couple more and voila!

## Author

- Frontend Mentor - [@Michaella](https://www.frontendmentor.io/profile/michaella23)
- Twitter - [@NotMichaella](https://twitter.com/NotMichaella)
