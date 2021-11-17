# Frontend Mentor - Profile card component solution (in progress)

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Profile card component solution (in progress)](#frontend-mentor---profile-card-component-solution-in-progress)
  - [Table of contents](#table-of-contents)
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

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](/assets/images/screenshot.png)


### Links

- Solution URL: [https://www.frontendmentor.io/solutions/profile-card-component-built-using-html-and-css-qyBog7xmQ](https://www.frontendmentor.io/solutions/profile-card-component-built-using-html-and-css-qyBog7xmQ)
- Live Site URL: [https://lmac-1.github.io/profile-card-component/](https://lmac-1.github.io/profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

You can have multiple background images in CSS. I also learned how to use `vw` and `vh` in `background-position` to achieve a solution without having to write any media queries for the background: 

```css
body {
    background-image: url(../assets/images/bg-pattern-top.svg), url(../assets/images/bg-pattern-bottom.svg);
    background-repeat: no-repeat;
    background-position: right 52vw bottom 35vh, left 50vw top 50vh;
}
```

I have heard of CSS variables before, but this was the first project that I have used them in. They work particularly well when building something according to a style guide with a provided colour scheme:

```css
:root {
    --dark-cyan: hsl(185, 75%, 39%);
    --dark-blue: hsl(229, 23%, 23%);
    --dark-gray-blue: hsl(227, 10%, 46%);
    --dark-gray: hsl(0, 0%, 59%);
}

body { 
  color: var(--dark-blue);
}
```

### Continued development

I still don't feel completely comfortable with the `background-position` property in CSS. At the moment, I'm going through a CSS for JS developers course which I hope will give me a deeper understanding of CSS in general. I will revisit `background-position` once going through this course in more detail. 

I'd also like to look into Semantic HTML in more detail as sometimes I'm still not completely sure which tag would be most appropriate in each individual situation. 

### Useful resources

- [Background position CSS tutorial](https://www.youtube.com/watch?v=3T_Jy1CqH9k) - this short tutorial from Kevin Powell was a good summary of how `background-position` works. I'd recommend this for anyone who doesn't quite understand how this property works.

## Author

- Frontend Mentor - [@lmac-1](https://www.frontendmentor.io/profile/lmac-1)
- Twitter - [@codingwithlucy](https://www.twitter.com/codingwithlucy)

## Acknowledgments

Tech Twitter helped me out with my background position problems. Particularly [@thelulato](https://twitter.com/thelulato) and [@NoahJohnScales](https://twitter.com/NoahJohnScales). Thank you! I'm always blown away by people's kindness on Twitter to help those doing #100DaysOfCode. If you are considering starting an account, you should definitely do it! 