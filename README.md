# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/images/Screenshot%202022-11-08%20at%2010-09-42%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

### Links

- Solution URL: [GitHub](https://github.com/turkan03/Product-preview-card-component.git)
- Live Site URL: [GitHub Pages](https://turkan03.github.io/Product-preview-card-component/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

-learn how implement Responsive images:

```html
<picture>
  <source
    media="(min-width: 752px)"
    srcset="images/image-product-desktop.jpg"
  />
  <img
    src="images/image-product-mobile.jpg"
    alt="Gabrielle Essence
            Eau De Parfum image"
  />
</picture>
```

-how make content what can see only screen readers

```css
.sr-only {
  position: absolute;
  left: 10000px;
  width: 1px;
  height: 1px;
  top: auto;
  overflow: hidden;
}
```

-practice FlexBox and CSS Grid.

### Continued development

I want to continue focusing on in Responsive design and clean code;

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This helped me for understand how work with images in code. I really liked this website and will use it going forward. -[Resource 2](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/make-elements-only-visible-to-a-screen-reader-by-using-custom-css) - This helped me for understand how implement style for screen readers and how it is work.

## Author

- Website - [GitHub](https://github.com/turkan03)
- Frontend Mentor - [@turkan03](https://www.frontendmentor.io/profile/turkan03)
