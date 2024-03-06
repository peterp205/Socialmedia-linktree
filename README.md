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


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This was a recap for me although the ability to center verticle the solution suddenly clicked and was super easy using flexbox on the body and a container for the solution. (see below):

```css
body{
    display: flex;
    align-items: center;
}
```

Also managed to apply a transition element into the hover states with the below:

```css
.social-links li{
    display: inline;
    background-color: var(--grey);
    margin: 10px 0;
    padding: 15px 20px;
    width: 300px;
    border-radius: 10px;
}

.social-links li:hover{
    background-color: var(--green);
    color: var(--off-black);
    cursor: pointer;
    transition: 0.3s ease-in-out;
}
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

Key focuses:
- Using grid instead of flex
- apply better consistent understanding of em, rem etc.
