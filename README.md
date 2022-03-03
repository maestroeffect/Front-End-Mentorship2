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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](/screenshot (20).jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

```html
<div class="whole-container">
    <div class="image-desktop">
      <div class="overlay">
      </div>
    </div>
    <div class="image-mobile">
      <div class="overlay2">
```
```css
@media screen and (max-width: 800px) {
  body {
    background-color: hsl(233, 47%, 7%);
    font-size: 15px;
    margin: 0;
  }

  .overlay2 {
    width: 350px;
    height: 256.875px;
    background: hsl(277, 64%, 61%,.5);
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
  }

  .wait {
    display: none;
  }

  .whole-container {
    border: none;
    margin: 120px 80px;
    height: 880px;
    border-radius: 20px;
    width: 350px;
    background-color: hsl(244, 38%, 16%);
    text-align: center;
  }

  .left-section {
    width: 380px;
    height: 400px;
    margin-top: 50px;
    margin-left: 20px;
  }

  h1 {
    width: 300px;
    text-align: center;
  }

  .first-paragraph {
    width: 220px;
    text-align: center;
    margin-left: 35px;
    margin-bottom: 30px;
  }

  .image-desktop {
    display: none;
  }

  .image-mobile {
      background: url('../images/image-header-mobile.jpg');
      width: 350px;
      height: 256.875px;
      border-top-right-radius: 10px;
      border-top-left-radius: 10px;
  }

  .first-subcontent {
    float: none;
    text-align: center;
  }

  .second-subcontent {
    float: none;
    text-align: center;
  }

  .third-subcontent {
    float: none;
    text-align: center;
    margin-right: 70px;
  }

}
```
### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=ZJZtmD3H9Sc) - This helped me for overlay and background image color. I really liked this pattern and will use it going forward.
- [Example resource 2](https://stackoverflow.com/questions/7037959/css-root-directory) - This is an amazing article which helped me finally understand css root directory. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Omokhaiye Precious](https://www.your-site.com)
- Frontend Mentor - [@maestro_effect](https://www.frontendmentor.io/profile/maestro_effect)
- Instagram - [@maestro_effct](https://www.instagram.com/maestro_effct)

## Acknowledgments

I want to Aknowledge the Almighty God for the grace and divine enablement to run through this mini project successfully. I also want to thank the Holy Spirit for constant inspiration and retentive memory. Thank You Lord Jesus!
