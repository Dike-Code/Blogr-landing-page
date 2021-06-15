# Frontend Mentor - Blogr landing page solution

This is a solution to the [Blogr landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-  [Overview](#overview)
   -  [The challenge](#the-challenge)
   -  [Screenshot](#screenshot)
   -  [Links](#links)
-  [My process](#my-process)
   -  [Built with](#built-with)
   -  [What I learned](#what-i-learned)
   -  [Continued development](#continued-development)
   -  [Useful resources](#useful-resources)
-  [Author](#author)
-  [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

A Bogr Landing Page Solution from the Challange presented by Frontend Mentor... it's built with a pure HTML5 for laying out the structure, CSS for styling the website to make it more compelling, responsive and user friendly... A little bit of Javascript was also utilized in order to make the site more interactive.

The site contain three main sections adjoined with the header and the footer, a media_query used to make it responsive for both mobile and desktop view.

### The challenge

Users should be able to:

-  View the optimal layout for the site depending on their device's screen size
-  See hover states for all interactive elements on the page

### Screenshot

![Desktop View](./images/screenshoot.png)
![Mobile View](./images/screenshoot1.png)

### Links

-  Solution URL: [Add solution URL here](https://your-solution-url.com)
-  Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

-  Semantic HTML5 markup
-  CSS custom properties
-  Flexbox
-  CSS Grid
-  Desktop-first workflow
-  Javascript

### What I learned

I learnt a whole bunch of things, starting with how to buid a dropdown menu and also the distinct form at which a navbar could be positioned using the CSS "Margin" property...

```html
                  <ul class="dropdown">
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Overview</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Pricing</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Marketplace</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Features</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Integrations</a>
                        </li>
                     </ul>
                  </li>
                  <li class="navbar__items">
                     <a href="" class="navbar__links"
                        >Company <i class="fas fa-angle-down"></i
                     ></a>
                     <ul class="dropdown">
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">About</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Team</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Blog</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Careers</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Integrations</a>
                        </li>
                     </ul>
                  </li>
                  <li class="navbar__items">
                     <a href="" class="navbar__links"
                        >Connect <i class="fas fa-angle-down"></i
                     ></a>
                     <ul class="dropdown">
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Contact</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">Newsletter</a>
                        </li>
                        <li class="dropdown__items">
                           <a href="" class="dropdown__links">LinkedIn</a>
                        </li>
                     </ul>
                  </li>
               </ul>
```

```css
.header__container .navbar,
.dropdown {
   display: flex;
   align-items: center;
   list-style-type: none;
}

.header__container .navbar .navbar__items,
.dropdown .dropdown__items {
   position: relative;
   padding: 0 3rem;
}

.header__container .navbar .navbar__items .navbar__links {
   text-decoration: none;
   font-size: 1.2rem;
   color: #fff;
   font-weight: 500;
}

.navbar__items .dropdown {
   display: none;
   position: absolute;
   width: 100%;
   top: 100%;
   left: 10px;
   text-align: center;
   z-index: 1;
}

.dropdown .dropdown__items {
   background: var(--White-text);
   padding: 0 1rem;
}

.dropdown .dropdown__items a {
   color: var(--Very-dark-desaturated-blue);
   text-decoration: none;
   font-size: 1.2rem;
   font-weight: 300;
   margin: 5px auto;
   display: inline-block;
}
.dropdown .dropdown__items a:hover {
   color: var(--Very-light-red);
   font-weight: 500;
}

.navbar__items:hover .dropdown {
   display: block;
}
```

```js
const proudOfThisFunc = () => {
   console.log("🎉");
};
```

### Continued development

All, Practice... Practice and Practice.

### Useful resources

-  [Traversy Media](https://www.example.com) - This helped me with the full asimillation of CSS FLEX BOX and Grid. I really liked this pattern Brad uses in explaining all the concepts one needs to master this craft.

-  [Youtube](https://www.example.com) - This is an amazing website/platform which helped me finally understand a lot including the snippets on buiding a dropdown list. I'd recommend it to anyone still learning this concept.

## Author

-  Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
-  Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

With utmost gratitude I'd like to acknowledge:
- Freecodecamp,
- Traversy Media,
- Dev.Ed,
- Jon Dukket,
- Youtube.
