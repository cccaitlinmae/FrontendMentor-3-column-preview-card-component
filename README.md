# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/screenshot_desktop-view.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://cccaitlinmae-3-column-preview.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I grew accustomed on using SASS in working my projects lately. But for this, I decided to use plain CSS to practice myself on other properties I still didn't know.

1.) Use of CSS Variables: Since I'm used to SASS variables, I wanted to try to work with their variables on this challenge.

```css
:root {
  /*colors*/
  --main-orange: hsl(31, 77%, 52%);
}
.card {
  background: var(--main-orange);
}
```

2.) Use of relative units: I still find it difficult to figure out the computation of ems, rems, vh & vw units. But delving into the basics on how it works on your browser, you would prefer this as well. Helps a lot for accessibility.

```css
html {
  font-size: 62.5%;
}
.card-title {
  font-size: 3.2rem;
}
```

3.) Use of overflow:hidden : I had no idea how to work with this at first but this helped me to corner borders of a div container.

```css
.container {
  overflow: hidden;
}
```

### Continued development

I would definitely continue the use relative units and mobile-first workflow for my future responsive web projects.

### Useful resources

- [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) - This helped me know the standard syntax of CSS Variables and its usage
- [Use of Flexbox](https://getflywheel.com/layout/flexbox-create-modern-card-design-layout/) - This helped me understand more a comprehensive appraoch to card layout with Flexbox
- [Goodbye to Pixel Units!](https://uxdesign.cc/say-goodbye-to-pixels-cb720fbaf250) - As someone who grew making websites using px as units in almost everything, it has come to point where it has to end. Yet I'm still getting used to it as this point because I still use them in media queries. Although, I recommend reading this article to know why (px) is not anymore a good approach for responsive design.

## Author

- Frontend Mentor - [@cccaitlinmae](https://www.frontendmentor.io/profile/cccaitlinmae)
- Github - [@cccaitlinmae](https://github.com/cccaitlinmae/)
