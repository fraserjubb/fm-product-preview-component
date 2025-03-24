# FM - <Challenge Name> Solution - Fraser Jubb

This is a solution to the [<name> challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## 📖 Table of contents

- [Overview](#overview)
  - [Project Screenshot](#project-screenshot)
  - [Project Links](#project-links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Noteworthy Updates Since Initial Submission](#noteworthy-updates-since-initial-submission)
- [Connect With Me](#connect-with-me)

## Overview

### Project Screenshot

![Screenshot of solution](/assets/images/solution-fraser.png)

### Project Links

- Solution URL: [Click Here](https://www.frontendmentor.io/solutions/product-preview-component-solution---challenge-5-NeykT__5OR)
- Live Site URL: [Click Here](https://fm-productpreviewcomponent-fraser.netlify.app/)
- Frontend Mentor Profile: [@fraserjubb](https://www.frontendmentor.io/profile/fraserjubb)

## My Process

### Built With

- HTML
- CSS
- Desktop-first workflow

### What I Learned

In this particular project:

1. I now have a much better understanding of the `<picture>` element and how it can be used to swap images on smaller devices.

```html
<picture>
  <source
    media="(max-width:650px)"
    srcset="/assets/images/image-product-mobile.webp"
    type="image/webp"
  />
  <source
    media="(max-width:650px)"
    srcset="/assets/images/image-product-mobile.avif"
    type="image/avif"
  />
  <source
    media="(max-width:650px)"
    srcset="/assets/images/image-product-mobile.jpg"
    type="image/jpg"
  />
  <source
    srcset="/assets/images/image-product-desktop.webp"
    type="image/webp"
  />
  <source srcset="assets/images/image-product-desktop.avif" type="image/avif" />
  <img
    class="card__image"
    src="assets/images/image-product-desktop.jpg"
    alt="Photo of perfume"
  />
</picture>
```

2. I made better use of the style-guide.md file and even updated it for my own quick reference note that I made from analyzing the Figma file.

### Useful Resources

- Nothing of note used for this project.

## Noteworthy Updates Since Initial Submission

1. No major updates since submitted.

## Connect With Me

<a href="https://github.com/fraserjubb"><img height="30px" align="left" alt="GitHub" style="padding-right:10px" title="Github" src="https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/fraser-jubb"><img height="30px" align="left" alt="LinkedIn" style="padding-right:10px" title="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=plastic&logo=linkedin&logoColor=white"/></a>
<a href="https://www.instagram.com/thejubbzone/"><img height="30px" align="left" alt="Instagram" style="padding-right:10px" title="Instagram" src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=plastic&logo=Instagram&logoColor=white"/></a>
<a href="https://x.com/fraserjubb"><img height="30px" align="left" alt="X" style="padding-right:10px" title="X" src="https://img.shields.io/badge/X-%23000000.svg?style=plastic&logo=X&logoColor=white"/></a>
<a href="https://www.youtube.com/@thejubbzone2374"><img height="30px" align="left" alt="YouTube" style="padding-right:10px" title="YouTube" src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white"/></a>
<a href="mailto:fraserjubb.dev@gmail.com"><img height="30px" align="left" alt="Gmail" style="padding-right:10px" title="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=plastic&logo=gmail&logoColor=white"/></a>

<br/>
