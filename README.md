# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshots](#screenshots)
    - [Mobile](#mobile)
    - [Desktop](#desktop)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Here are some code snippets:](#here-are-some-code-snippets)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshots

### Mobile

![](/images/mobile.png)

### Desktop

![](/images/desktop.png)

### Links

- Solution URL: [Solution here](https://github.com/Tyrone-Cartwright/qr-code-component)
- Live Site URL: [Live site](https://tyrone-cartwright.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 Markup
- CSS
- Mobile-first Workflow

### What I learned

What I learned was how semantic markup workflow makes it easier to code, as you come to understand how writing semantically allows for maintainable & readable, and self-descriptive code. Also, building from a mobile-first gives you a better UX, you also have that progressive enhancement mindset so when you want to add other features or layouts for when screen sizes increase.

### Here are some code snippets:

```html
<main>
  <div class="card">
    <div class="card-image">
      <img src="./images/image-qr-code.png" alt="QR Code" />
    </div>
    <div class="card-content">
      <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</main>
```

```css mobile-first
.card {
  width: 20rem;
  height: 31.1875rem;
  border: none;
  border-radius: 0.625rem;
  background-color: var(--white);
  padding: 1rem 1rem 2.5rem 1rem;
  margin: 0 auto;
}
```

```css root styles
:root {
  /* Color Palette */
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);

  /* Font Styles */
  --font-outfit: "Outfit", sans-serif;
  --font-reg: 400;
  --font-bold: 700;
}
```

If you want more help with writing CSS, I'd recommend checking out [CSS Tricks Guides ](https://css-tricks.com/guides/) section to learn more.

### Continued development

### Useful resources

- [CSS Tricks](https://css-tricks.com/guides/) - This helped me for centering. It is a goto resource with anything pertaining to CSS and I will continue to use it going forward.
- [FreeCodeCAmp](https://www.freecodecamp.org/) - This is an amazing resource for practicing or reinforcing what you already know. They provide an interactive platform, where you can learn and build at the same time, in which you don't have to download anything.

## Author

- Website - [Tyrone Cartwright](https://tyrone-cartwright.github.io/qr-code-component/)
- Frontend Mentor - [@Tyrone-Cartwright](https://www.frontendmentor.io/profile/Tyrone-Cartwright)
