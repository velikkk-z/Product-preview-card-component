# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview
This challenge is to build out this product preview card component and get it looking as close to the design as possible. This HTML & CSS-only challenge will be perfect for anyone starting to build responsive projects.And it takes me 6-8 hours to get it done.


### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Screenshot

### Links

## My process

1. Download the starter code
2. Set up the project with version control (e.g. Git)
3. Read the `README.md` file and have a look around the project
4. Get colors, fonts etc from the `style-guide.md` file
5. Start coding!
  1) Structure document using semantic tags
  2) Use HTML to include responsive image
  3) Write styles as close to the design as I can
  4) Estimate the difference between my solution and design
  5) Debug
  
  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```html
<img class="productImage" srcset="images/image-product-desktop.jpg 800w, images/image-product-mobile.jpg 375w"
      sizes="(max-width:375px) 340px,800px" src="images/image-product-mobile.jpg" >
```
```css
letter-spacing: 4px;     
      button {
          display: flex;
          flex-direction: row;
          justify-content: center;
      }
      button:hover {
          cursor: pointer;
      }
      .product{
              padding-left: 20px;
              padding-right: 20px;
              height: 65%;
              overflow: auto;
          }
      @font-face {
          font-family: Fraunces;
          src: url("fonts/Fraunces-VariableFont_SOFT\,WONK\,opsz\,wght.ttf");
      }
      @media screen and (max-width:375px){
      }
```

### Continued development


### Useful resources
- [MDN Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) This is an amazing article which helped me finally understand responsive images and how to use attributes: srcset and sizes.


## Author
- Github - [velikkk-z](https://github.com/velikkk-z/)
- Frontend Mentor - [velikkk-z](https://www.frontendmentor.io/profile/velikkk-z)
