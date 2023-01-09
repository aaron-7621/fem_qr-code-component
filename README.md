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

![Desktop preview image for QR code component challenge](/images/desktop%20preview.png "Desktop preview")
![Mobile preview image for QR code component challenge](/images/mobile%20preview.png "Mobile preview")

### Links

- Solution URL: [Solution](https://github.com/ag7621/fem_qr-code-component)
- Live Site URL: [Live Site](https://ag7621.github.io/fem_qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was a nice introduction to learning how to build a site based off a completed design. I very much enjoyed the challenge and look forward to continuing more of these types of challenges alongside building my own websites and projects.

Although the design was simple in nature, I decided to try and practice building it using different developmental practices I've come across in my learning. These include CSS methodologies such as BEM, declaring CSS variables, and the use of a CSS reset.

While I know not perfect, I would appreciate any tips and comments.

```html
<div class="card">
  <img class="card__img" src="images/image-qr-code.png" alt="image of QR code">
  <h1 class="card__title">Improve your front-end skills by building projects</h1>
  <p class="card__description">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</div>
```
```css
:root {

    /* Primary */

    --clr-primary: hsl(218, 44%, 22%);
    --clr-primary-shadow: hsla(218, 44%, 22%, 20%);

    /* Secondary */

    --clr-secondary: hsl(220, 15%, 55%);

    /* Neutral */

    --clr-neutral-100: hsl(0, 0%, 100%);
    --clr-neutral-200: hsl(212, 45%, 89%);

    /* Font size */

    --fs-400: 0.9rem;
    --fs-600: 1.4rem;

    /* Font weight */

    --fw-regular: 400;
    --fw-bold: 700;

}
```

### Continued development

I am still not comfortable in how to properly using BEM in building a site, nor with naming my CSS variables yet. I plan to continue practicing and finding a naming scheme I am comfortable using until I can fully understand its potential. 

### Useful resources

- [BEM cheat sheet](https://9elements.com/bem-cheat-sheet/) - This helped me understand the basics of how BEM looks and how to name classes.
- [Kevin Powell Youtube](https://www.youtube.com/@KevinPowell) - Amazing channel by veteran web developer Kevin Powell which helped me to understand CSS much better.
- [Josh W Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - A CSS reset referred to in a video by Kevin Powell.

## Author

- Frontend Mentor - [@ag7621](https://www.frontendmentor.io/profile/ag7621)
