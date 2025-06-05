# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot of the solution](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/alepacc/4-card-feature-section](github)
- Live Site URL: [Add your live site URL here](live-site)

## My process

### Built with

- Semantic HTML5 markup
- SCSS (CSS custom properties)
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project I improved my understanding of CSS Grid for complex layouts and how to combine it with Flexbox for responsive design.  
I also practiced using SCSS variables for color management and learned how to structure a component-based layout.

```scss
.cards-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(2, auto);
  gap: 30px;
  justify-items: center;
}
```

### Continued development

I want to continue improving my skills with advanced CSS layouts and accessibility best practices.  
In future projects, I plan to focus more on ARIA roles and keyboard navigation.

### Useful resources

- [CSS-Tricks: A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped me understand CSS Grid properties.
- [MDN Web Docs: Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - Reference for Flexbox concepts.

## Author

- Website - [Your Name](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

Thanks to the Frontend Mentor community for feedback and inspiration!