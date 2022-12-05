# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

I will include screenshots in my GitHub repository.

### Links

- Live Site URL: (https://nevercanon.github.io/productpreviewcard/)

## My process

I began with using mobile-first workflow to build the mobile card component, then built the desktop component. I didn't use any frameworks or libraries for this project.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The biggest thing I learned was about using two different pictures for the desktop and the mobile components. I had this challenge with a previous project. I couldn't get the entire image to show in my media query, since I was using the background-image property instead of building the images into my HTML. It was very frustrating for me. When I started working on the desktop view for this project I had the same issue. My solution this time was to put both images in my HTML and set display: none; for the one I wasn't using and switching them in my media query. This worked so much better and was such a relief. Since I had to use the background-image property in my previous project because I was tinting the image, I don't know how I could have done it differently, but this project helped me make the image look so much better. It made me really happy to see the progress that I made by doing this challenge.

The next biggest challenge I had was working with margins. I don't think I got them exactly right in this project. In the desktop view, it seemed like I just had too much space entirely. I wasn't sure what to do about this, since I was letting the card just be the natural size of the image. I thought about decreasing the height of the image, but in the end I just left it so the image looked normally-proportioned. 

It was a bit of a challenge to get the words spaced and on the same lines as they appear in the design pictures, but I got it in the end and I think it was a good learning experience for me. For a while I was trying to add lots of padding to the product description paragraph to squish the words onto the correct lines, when it turned out I actually needed to decrease the padding to give the words room. That was a small breakthrough moment for me.

### Continued development

I would really like to learn how to tint images without making them background-images, though that's really a concept that was used in another project. I just learned how I could do it better after completing this project.

I'm also planning on working more at getting more accurate margins.

### Useful resources

- [Resource 1](https://www.w3schools.com/Css/css3_mediaqueries_ex.asp) - This website has helped me numerous times with remembering how to set media queries.

## Author

- Frontend Mentor - [@nevercanon](https://www.frontendmentor.io/profile/nevercanon)
- GitHub - [@nevercanon](https://github.com/nevercanon)