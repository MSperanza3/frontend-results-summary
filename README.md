# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Screenshot 2023-12-05 at 9.26.57 AM.png](assets%2Fimages%2FScreenshot%202023-12-05%20at%209.26.57%E2%80%AFAM.png)

### Links

- Solution URL: [Github](https://github.com/MSperanza3/frontend-results-summary)
- Live Site URL: [Live Site Here](https://msperanza3.github.io/frontend-results-summary/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Got More comfortable with Flexbox and learning how you can use it to create cleaner looking websites.
Learning how to making a faded circle was also huge problem but with trial and error got it to work

```html
<p class="reaction">
        <span class="reaction-content">
      <img src="assets/images/icon-reaction.svg">
      <span>Reaction</span>
        </span>
  80 / 100
</p>
```
```css
.grade-circle::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to top, rgba(75, 50, 203, 0), #4B32CB);
    border-radius: 50%;
}
```

### Continued development

Continue focus on using Flexbox more effectively and learning to clean us CSS to be more digestible

## Author

- Website - [Matteo Speranza](https://github.com/MSperanza3)
- Frontend Mentor - [@MSperanza3](https://www.frontendmentor.io/profile/MSperanza3)


## Acknowledgments

Thanks of course to my Instructors at Codeup as well as some classmates for helping me with some of the coding in CSS!
