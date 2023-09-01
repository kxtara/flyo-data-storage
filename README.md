# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

This is my first Junior Frontend Mentor challenge. I think I did pretty well on this challenge,but as always,if there's something you see that can be done better,let me know.
**HAPPY CODING!!**

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![ScreenShot](https://raw.github.com/kxtara/flyo-data-storage/main/images/desktop.jpg)


### Links

- [Solution URL](https://www.frontendmentor.io/solutions/flyo-data-storage-component-nvbDn8-cw6)
- [Live Site URL](https://kxtara.github.io/flyo-data-storage/)

## My process

I started structuring the HTML keeping in mind how the desktop version looks as well. Then I started styling for the mobile version of the challenge and continued with the desktop version.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to manipulate elements to create shapes like the triangle used for the '185 GB LEFT' element.

```css
.GB-left::before {
    content: "";
    position: absolute;
    left: 86.2%;
    top: 4rem;
    width: 0;
    height: 0;
    border-top: 0px solid transparent;
    border-right: 26px solid var(--Pale-Blue);
    border-bottom: 35px solid transparent;
  }
```

### Continued development

I want to continue doing these challenges to practice my skills and figure things that I need to work on.

### Useful resources

- [css-tricks](https://css-tricks.com/the-shapes-of-css/) - This helped me manipulate elements to create shapes like the triangle used for the '185 GB LEFT' element.

## Author

- Frontend Mentor - [@kxtara](https://www.frontendmentor.io/profile/kxtara)
- Twitter - [@kiarahoheb](https://www.twitter.com/kiarahoheb)
- LinkedIn - [@kiarahoheb](https://www.linkedin.com/in/kiara-hoheb-641157244/)
