# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

(/screenshot/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

#### stacking multiple divs worked, but I'm unclear if that was the smartest route, but it worked so good for me

```html
<div class="container">
  <div id="qr-code-holder">
    <img src="/images/image-qr-code.png" alt="QR code image" />
  </div>
  <div class="text-container">
    <h4>Improve your front-end skills by building projects</h4>
    <p class="paragraph">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</div>
```

#### I did get stuck on how to center the main div, so I had to resort to chat to gpt

```css
.container {
  width: 250px;
  height: 350px;
  background-color: whitesmoke;
  border: 3px solid #123456;
  border-radius: 30px;
  padding: 20px;
  margin: auto; /* mainly this*/
  color: #333;
  font-size: 16px;
  text-align: center; /* and this helped to center the div...I think :| */
}
```

### Continued development

I will need to incorporate other uses for css. While I am satisfied with this project(because it's my first project without an online tutorial), I will need to incorporate more useful and creative things that css involves. At some point I'll probably come back and do some other things here, but for now I am satisfied.

### Useful resources

- I really just used chatGPT, Stack Overflow and Bing. But I made sure to ask the right kind of questions, like, "How do I center a div" or "how can I have an image in a div" or "why is my text not visible in the div, how can I get it to appear where I wanted it", stuff like that.

## Author

- Twitter/X-(https://twitter.com/RealMosesElite)
- Instagram-(https://www.instagram.com/moses_elite2020)
- Facebook-(https://www.facebook.com/elliot.moses.568)
