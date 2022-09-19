# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)

### Screenshot

![](</images/Screenshot%20(9).png>)

### Links

- Solution URL:https://www.frontendmentor.io/solutions/flexbox-and-boostrap-CYq8tJCAMx
- Live Site URL:https://nondaba.github.io/ProductPreviewCardComponent/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Bootstrap

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned how to resize an svg with css,applied styles to elements using media queryfor phone screen,picture element for multiple pictures and overrided the bootstrap styles with custom styles.

```html
<picture>
  <source media="(max-width:375px)" srcset="images/image-product-mobile.jpg" />
  <img src="images/image-product-desktop.jpg" alt="product-desktop-image" />
</picture>
```

```css
.btn-primary svg {
  margin-right: 3%;
  width: 7%;
}

.btn-primary {
  background-color: hsl(158, 36%, 37%) !important;
  border-color: hsl(158, 36%, 37%) !important;
  font-family: "Montserrat", sans-serif;
  font-weight: bold;
  font-size: 14px;
  position: relative !important;
  top: -60%;
}
```

### Continued development

I need to focus on media query, css units, boostrap.

### Useful resources

- https://www.w3schools.com/ - This helped me for learning different HTML elements and CSS attributes.
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/ - This site help me understand flexbox a bit better.

## Author

- Website -(https://www.nondaba.github.io/)
- Frontend Mentor -https://www.frontendmentor.io/profile/RealuNondaba)
