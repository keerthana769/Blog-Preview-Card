
## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![](./assets/images/Screenshot%20(325).png)

### Links

- Solution URL: [Add solution URL here](https://github.com/keerthana769/Blog-Preview-Card/)
- Live Site URL: [Add live site URL here](https://keerthana769.github.io/Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned that it’s best practice to set elements to width: 100% initially and then build the layout around that. One new technique I got to know is using clamp() for responsive font sizes.

To center content vertically and horizontally, you can set display: flex on the body and use align-items: center and justify-content: center, along with height: 100vh. Additionally, make sure images have width: 100% to scale correctly.

Another key takeaway: when using border-radius on an element with padding, you might not get the expected result. In such cases, it’s better to use margin instead of padding.

I never thought knowing how to use Figma would save so much time. I really recommend understanding the Figma files for developing your project.

Note: Always look for semicolon at the end of code. Make sure margin is set to 0.

clamp(min, preferred, max)

```css
.heading{
  font-weight: bolder;
  font-size: clamp(15px, 6.4vw, 20px);
}
.post{
  margin-bottom: 1rem;
  border-radius: 10px;
  width: 100%;
}
body{
  background-color: hsl(47, 88%, 63%);
  display: flex;
  height: 100vh;
  align-items: center;
  justify-content: center;
}
.heading:hover{
  color: hsl(47, 88%, 63%);
}
```

### Continued development

In the future, I plan to make the buttons and profile links functional so they redirect to other pages which I will design and build myself.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Aligning_items) - It helped me learn how to align a container to the center of the page.
- [Resource 2](https://www.w3schools.com/css/css_text_spacing.asp) - This resource helped me learn how to give spacing between lines, letters...

## Author

- Frontend Mentor - [@keerthana769](https://www.frontendmentor.io/profile/keerthana769)
- LinkedIn - [@keerthana-gurram](https://www.linkedin.com/in/keerthana-gurram/)



