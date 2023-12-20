# Animated Grid Showcase

A simple HTML and CSS template showcasing an animated grid of boxes with hover effects. Each box has a unique transition and reveals additional information on hover.

## Features

- Responsive grid layout with smooth animations.
- Hover effects on individual boxes, providing a grayscale and opacity transition.
- Dynamic grid adjustments based on the hovered box for an enhanced visual experience.

## Usage

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.

## CSS Styles

```css
* {
  /* Resetting default styles */
}

body {
  /* Body styles */
}

html {
  /* Root font size */
}

.container {
  /* Grid container styles */
}

.box {
  /* Individual box styles */
}

@keyframes bounce {
  /* Bouncing animation keyframes */
}

.box:hover {
  /* Hover effect on individual boxes */
}

.container:has(.box-1:hover) {
  /* Grid adjustment on box 1 hover */
}

/* Similar adjustments for box-2 to box-5 */

.box:nth-child(odd) {
  /* Odd box styles */
}

.box:nth-child(even) {
  /* Even box styles */
}

.box::after {
  /* Additional information overlay styles */
}

.box:hover::after {
  /* Hover effect on additional information overlay */
}
```

Feel free to customize the styles and adapt the template to suit your project's needs. Explore the possibilities of this animated grid showcase!
