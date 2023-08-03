# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### Screenshot

![Desktop-Design](./images/Screenshot%202023-08-02%20at%2021-06-24%20Frontend%20Mentor%20QR%20code%20component.png)
![Mobile-Design](./images/Screenshot%202023-08-03%20at%2011-15-33%20Frontend%20Mentor%20QR%20code%20component.png)

## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I've learned how to built an QR code UI with the following code -

```html
<div class="main-qr-card">
  <div class="qr-card">
    <img src="./images/image-qr-code.png" alt="" />
  </div>
  <div>
    <h2>Improve your front-end skills by building projects</h2>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</div>
<div class="attribution">
  Challenge by
  <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
    >Frontend Mentor</a
  >. Coded by <a href="#">Utkarsh Singh Tomar</a>.
</div>
```

```css
* {
  box-sizing: border-box;
  font-family: "Outfit", sans-serif;
}

body {
  /* background-color: hsl(220, 15%, 55%); */
  background-color: hsl(212, 45%, 89%);
  /* display: flex; */
  /* flex-direction: column; */
  /* align-items: center; */
  /* justify-content: center; */
  min-height: 96vh;
  padding: 60px;
  /* border: 3px dashed red; */
}

div.main-qr-card {
  width: 26%;
  background-color: hsl(0, 0%, 100%);
  padding: 15px;
  border-radius: 15px;
  min-height: 30rem;
  margin: 0 auto;
  text-align: center;
}

div.qr-card {
  max-width: 100%;
  min-height: 290px;
  position: relative;
}

div.qr-card img {
  position: absolute;
  top: 0;
  left: 0;
  object-fit: cover;
  max-width: 100%;
  max-height: 100%;
  border-radius: 15px;
}

h2 {
  color: hsl(218, 44%, 22%);
}

p {
  color: hsl(220, 15%, 55%);
  font-size: 15px;
  font-weight: 400;
  padding: 0 20px;
}

.attribution {
  font-size: 11px;
  text-align: center;
}

.attribution a {
  color: hsl(228, 45%, 44%);
}

@media (width <= 375px) {
  body {
    /* background-color: hsl(220, 15%, 55%); */
    background-color: hsl(212, 45%, 89%);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 96vh;
    padding: 40px 20px;
    /* border: 3px dashed red; */
  }

  div.main-qr-card {
    width: 100%;
  }

  div.qr-card {
    max-width: 100%;
    min-height: 285px;
    position: relative;
  }

  div.qr-card img {
    position: absolute;
    top: 0;
    left: 0;
    object-fit: cover;
    max-width: 100%;
    max-height: 100%;
    border-radius: 15px;
  }
}
```

### Continued development

learning React
Development of Bigger Websites
