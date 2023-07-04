# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

<img src="/doc/image.png">
<img src="/doc/image-1.png">

### Links

- Solution URL: [https://github.com/gabrielolvmd/news-homepage-main]
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SCSS
- Mobile-first workflow

### What I learned

While developing this code, I was able to put my CSS and SCSS skills into practice. With SCSS, I used variables and code blocks to be reused later, which made it much easier to manipulate and maintain the code in the future.

Additionally, I was able to further understand flexbox and responsiveness for most devices.

```css
@mixin flex-center($justify, $align, $direction) {
  display: flex;
  justify-content: $justify;
  align-items: $align;
  flex-direction: $direction;
}

/*This code snippet allowed me to adjust the colors of the lists without much effort.*/
@mixin list-color($color) {
  color: $color;
  background-color: color-mix(in srgb, $color, transparent 90%);
}
```
