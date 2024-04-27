# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

This was an interesting one. It was a great practice to learn using pseudo elements and pseudo classes. I also learnt the use of <section> in html and the mandatory heading requirement for semantics. 

```html
<section class="preptime">
      <h2>Preparation time</h2>
      <ul>
        <li><b>Total:</b> Approximately 10 minutes</li>
        <li><b>Preparation:</b> 5 minutes</li>
        <li><b>Cooking:</b> 5 minutes</li>
      </ul>
    </section>
```
```css
li::marker {
    color: hsl(14, 45%, 36%);
    font-weight: 600;
}

td:nth-child(even) {
    color: hsl(14, 45%, 36%);
    font-weight: 600;
}
```

### Continued development

I now feel comfortable working with flexbox and I intend to get into grid. Practice is all thats left to get a good grasp of pseudo classes and pseudo elements.

## Author

- Frontend Mentor - [@1deadjoe](https://www.frontendmentor.io/profile/1deadjoe)
- Twitter - [@chirojoe1](https://www.twitter.com/chirojoe1)

## Acknowledgments
I would like to acknowledge Frontend Mentor for providing this challenge.
