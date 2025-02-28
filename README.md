# Image gallery with automatic "masonry" style layout

In web design, a "masonry" style image gallery refers to a layout where images or content blocks are arranged in an irregular, grid-like pattern, with varying heights but consistent widths (or vice versa). This creates a visually dynamic, Pinterest-like look, where items are placed based on available vertical space rather than in uniform rows or columns. The masonry layout is responsive, meaning that the blocks reflow and adjust to fit different screen sizes without leaving gaps.

This style is particularly useful when dealing with images of varying sizes, as it allows designers to maximize the use of space while maintaining an aesthetically pleasing arrangement. It creates a fluid, modern appearance that can handle both large and small images in a cohesive way.

This is what happens when I make a change in the middle

This example automatically applied a masonry layout based on the width of the browser window and/or the size of the containing element. Change the size of the browser to see it in action. gallery-masonry



## CSS

`.gallery-masonry` - This selector is the container to holds the images. 

`columns: 350px;` - This property sets the goal width of the images in the gallery. Change this value to set the general size of the images. 


`.gallery-masonry img` - This selector affects the images that are inside the gallery area. 

## Example
You can preview a working example of it **[here](https://prof-anderson-uc.github.io/masonry-gallery){:target="_blank"}**
