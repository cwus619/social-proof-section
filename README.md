# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the section depending on their device's screen size

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/desktop-first-workflow-using-css-grid-and-flexbox-9Eu-CH2Yf]
- Live Site URL: [https://cwus619.github.io/social-proof-section/]

## My process

As with other projects I first of all created the desktop version of the webpage first.
Starting with the layout of the upper half of the page, I divided the title and text into one section and the ratings into another to style separately. Initially, I intended to use CSS Grid for the ratings section, but ultimately felt that flexbox was better suited to achieving my goal.
Following this, I opted to use CSS Grid to style the lower half of the page to allow for easier placement of each review box.

Once I was happy with the dekstop layout, I styled the mobile version, opting to remove CSS Grid entriely, and use flexbox for all sections.

Once the mobile layout was finished, I experimented with different breakpoints to determine where the styling should change slightly (or, indeed, vastly) for smaller screen sizes.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

This challenge presented an opportunity to make use of and to develop my understanding of both flexbox and CSS Grid - I feel quite confident in my flexbox abilities now; however, I also feel that I require more practice in putting together webpages with CS Grid.
One of the things that this challenge showed me was the importance of definining width/height within a grid. One of the more frustrating issues I had was getting the first review box to fill the grid to the extent I had defined. After trying different options for the height/width properties, I found "fit-content" to provide a good solution to the problem.
In a similar way, experimenting with percentages for width/height/margin helped me understand how to make better use of percentages for these attributes to allow for a responsive webpage, and ensure that the elements on the page were sized the way I had intended.

### Continued development

Insofar as I continue to focus on beginner challenges, I intend to practice CSS Grid further. However, I am hoping now to go beyond CSS and HTML to use more JavaScript, and to begin learning how to use libraries such as React.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/)
- [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - I have been making use of css-tricks for several projects recently to review and better understand CSS Grid better - I find the guide very intuitive with its visual aids.

## Author

- Frontend Mentor - [@cwus619](https://www.frontendmentor.io/profile/cwus619)
