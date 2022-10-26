# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Sunnyside agency landing page solution](#frontend-mentor---sunnyside-agency-landing-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](/images/landing-page-finished.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/deividcode/sunnyside-agency-landing-page-main.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Variables
- Flexbox
- CSS Grid
- Mobile-first workflow
- Metodology BEM

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
  <details class="iconmenu">
    <summary>      
      <img src="images/icon-hamburger.svg" alt="menu">
    </summary>          
  </details>

  <nav class="menu">
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Projects</a>
    <a href="#">CONTACT</a>
  </nav>
```

```css
  details[open] + .menu{
    animation: openMenu 0.35s linear forwards;    
  }

  summary {
    display: block;
  }

  summary::-webkit-details-marker {
    display: block;
  }

  .menu{
  animation: closeMenu 0.35s linear forwards;    
  }
```


### Useful resources

- [@keyframes](https://front.id/es/articles/css-animaciones-con-keyframes) - This helped me learn how to make animated elements.

## Author

- Frontend Mentor - [@deividcode](https://www.frontendmentor.io/profile/deividcode)
- 
- Twitter - [@deividCode](https://twitter.com/deividCoder)

