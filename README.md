# Week 2 Assignment: CSS Image Galleries

Using Flex to manage rows and columns of items.

## CSS Properties used in Image Galleries

- `margin` area outside of the box and between element and other elements; you can specify top, bottom, left and right independently
- `padding` area inside the box; you can specify top, bottom, left and right independently
- `box-sizing` used frequently to normalize to `border-box` so that border width is not added to element height and width calculation
- `font-family` a list of related fonts that may be found on different browsers
- `font-size` size of the font which can come in different units including pixels `px`, ems `em`, rems `rem`, points `pt`, and `%` and more.  See [MDN font-size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size) for more on this.  You will see `px` use a lot because developers get used to what these sizes might look like.  However as you get into responsive web sites which run on different sized devices, the `rem` is a value relative to the root size of the width of a Capital "M", and no matter how deep it falls in a container, the value you assign it will remain relative to the root size.
- `text-align` specifies how to align text or other elements within a block; it is used a lot to align text and image to the center of the page
- `font-weight` can be used with values like `100` or `"bold"` to indicated how thick or thin text should be
- `list-style` by default when you render list items that are prepended with a bullet point and you can change this to a circle, a square, Roman numerals or alphabetic characters; you'll often see `"none"` because lists that are rendered horizontally as in a navitation bar don't need any prepended characters
- `display` the discussion above regarding `inline-block` is only one of the values that an be assigned to the `display` property; this assignment will use the `display: flex` to layout items in a wrapping left to right or top to bottom manner; 
- `flex` is a property that has not been assigned a value, so it takes the default `0 1 auto` which stand for `flex-grow: 0`, `flex-shrink: 1`, and `flex-basis: auto`; if any of these properties are set, the new setting will override the default
- `flex-basis` default length of a specific flexed item which can be height or width; this overrides the default and items will be allowed to shrink, but not grow past 350px
- `flex-direction` default is row or horizontal, `column` indicates a vertical flex; col-flex example shows flexing the container vertically and flexing each column in the container vertically
- `flex-wrap` specify the `wrap` value to wrap items in a `flex` container
- `justify-content` specify the `center` value to center flex container
- `gap` specify size of empty space between items in a flex box layout
- `border: 1px solid black` is a shorthand to render a 1 pixel solid black border;width, style and color of the border can be changed, for example `solid` can become `dotted`
- `object-fit` instruct how an image or video will fill a container;  
- `cover` fills the container an maintains aspect ratio by clipping if needed
- `width`, `height`, `max-width` and `max-height` are all options for controlling the size of a block element; `max-width` can prevent images overflowing if the container shrinks
- `border-radius` is used to round the corners of an element; if you have a square element
- `::after` pseudo element referencing the last child element; code demonstrate how you can keep images aligned in 3 columns when you know that there will be 1 less item in the last row
`.image-item:hover` `:hover` is a pseudo class that that is activated by user interaction as in pointing at an element 
`align-items:center` + `justify-content: center` is used to both vertically and horizontally center an item
`position: relative` followed by `position: absolute` is used to place an element in an exact position relative to it's container element
`@media only screen and (min-width: 768px)` media query than provides instructions for devices with screens greater than 768 pixels (tablet)


## Resources

[LogRocket Responsive Image Gallery with Flexbox](https://blog.logrocket.com/responsive-image-gallery-css-flexbox)
