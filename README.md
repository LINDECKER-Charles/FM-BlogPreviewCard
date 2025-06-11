# Frontend Mentor - Blog preview card solution ✨📝💡

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 🚀📚🛠️

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
* [Author](#author)
* [Acknowledgments](#acknowledgments)

## Overview 🌐📋🔍

### The challenge

Users should be able to:

* See hover and focus states for all interactive elements on the page

### Screenshot 🖼️📸💾

![](./screenshot.jpg)

### Links 🔗🌍📂

* Live Site URL: [Live Demo](https://charleslindecker.github.io/blog-preview-card)

## My process 🧠🔧🎯

### Built with 🏗️💻🎨

* Semantic HTML5 markup
* Tailwind CSS via CDN
* Custom HSL color palette using `tailwind.config` in a `<script>` tag
* Local variable font integration with `@font-face`
* Mobile-first responsive layout

### What I learned 🧩📖🧠

* How to define Tailwind config directly in HTML using the CDN version
* Integrate local fonts using `@font-face` for custom typography
* Fine-tune layout and spacing using Tailwind utilities
* Customize box-shadow using arbitrary values: `shadow-[8px_8px_0_0_black]`

```js
<script>
tailwind.config = {
  theme: {
    extend: {
      colors: {
        yellow: "hsl(47, 88%, 63%)",
        white: "hsl(0, 0%, 100%)",
        gray: {
          500: "hsl(0, 0%, 42%)",
          950: "hsl(0, 0%, 7%)"
        }
      },
      fontFamily: {
        figtree: ['Figtree', 'sans-serif']
      }
    }
  }
}
</script>
```

### Continued development 🧪🚧📈

I want to explore:

* Creating more complex card layouts
* Making reusable Tailwind components with better accessibility
* Refactoring this into a React/Vue component

### Useful resources 📚🔗🛠️

* [Tailwind CSS documentation](https://tailwindcss.com/docs)
* [Frontend Mentor](https://www.frontendmentor.io) for the challenge and design
* [Google Fonts](https://fonts.google.com/specimen/Figtree) to get the Figtree variable font

## Author 👤🖊️📇

* LinkedIn - [Charles LINDECKER](https://www.linkedin.com/in/charles-lindecker/)
* Frontend Mentor - [@LINDECKER-Charles](https://www.frontendmentor.io/profile/LINDECKER-Charles)

## Acknowledgments 🙌👏💬

Thanks to Frontend Mentor for the design and challenge inspiration. 💡🎨📣
