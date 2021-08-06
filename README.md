# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/desktop-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started with the desktop version of the site to get my base information set up, by adding all divs and font formatting, along with color scheme.
Using flexboxes i positioned all of my content within the divs I allocated to give the appearance of a centralised stats card.

I then used media query to alter my design depending on whether the users screen is more or less than 500px.

once i had this in place I added the surrounding code to hide the opposing image and create padding and margins around and within divs.

### Built with

- HTML
- CSS
- Flexbox
- Media Query

### What I learned

My main leaarning curve was media query to which I used MDN to learn the process required to alter the content depending on different aspects of device, particularly the width on this occassion.
I also learned more about flexboxes and how to justify content and align content in other ways.

@media (min-width: 501px){
  .mobile{
    display: none;
  }
  .text-container{
    display: flex;
    justify-content: space-around;
    align-content: space-around;
    flex-wrap: wrap;
    margin: 4em;
    text-align: left;
    }
  .desktop, .overlay{
    border-radius: 0 10px 10px 0;
  }
  .stat-container{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-right: 4em;
  }
  .heading, .paragraph{
    margin: 0 0 2em 0;
  }
  .desktop{
    height: 100%;
  }
}

### Continued development

I am to carry on learning about media query and the various parameters it can work to other then the screen sizing.
my positioning is getting better but i also aim to keep working on this to perfect it.

### Useful resources

- https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries

## Author

- Frontend Mentor - [@scott-the-coder] (https://www.frontendmentor.io/profile/Scott-the-coder)
