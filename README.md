# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page
  
### Links

- Solution URL: [https://www.frontendmentor.io/solutions/social-links-profile-7BILeMZPa2]
- Live Site URL: [https://benhyh.github.io/Social-Links-Profile/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Anchor tags

### What I learned

Anchor tags & pseudo-elements and its active state to achieve interactivity. 

```css
.social-links a {
    text-decoration: none;
    color: white;
}

.social-links a:hover {
    color: black;
    transition: 0.5s ease;
}

.social-links:hover {
    background-color: hsl(75, 94%, 57%);
    cursor: pointer;
    transition: 0.5s ease;
}
```

### Continued development

- The link is only active when the user cursor is directly on the anchor tags and I can't seem to work around that without messing up the dimensions of the element. Future development will take in consideration of that feature where users are able to access the link wherever the cursor position is at of the element.

## Author

- Frontend Mentor: [https://www.frontendmentor.io/profile/benhuynh003]

