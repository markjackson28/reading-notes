
# Class 12

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*[Charts.js API Article](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)*

- Chart.js is a Javascript plugin that allows you to display a chart using HTML5’s elements.
- Types of charts you can create: line, pie, and bar chart.

*[Canvas API: Basic Usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)*

- <canvas\> has two attributes: height and width.
- <canvas\> is usually blank and needs its method to display something and that is getContext().
- You must pass in a specify text parameter such as ‘2d’. Ex. getContext(2d’).
- Fallback is when a browser does not support the context so I need to display something that the browser supports.
- You can check for fallback support by using an if, else statement.

*[Canvas API: Drawing Shapes](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)*

- fillRect(x, y, width, height): draws a filled rectangle.
- strokeRect(x, y, width, height): draws a rectangle outline.
- clearRect(x, y, width, height): draw/creates a transparent rectangle.
- beginPath() allows you to create lines and curves to split/curve areas of the rectangle.

*[Canvas API: Applying Styles and Colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)*

- fillStyle is the style to use to fill the object
- strokeStyle is the style to use to fill the border of the object.

*[Canvas API: Drawing Text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)*

- fillText(text, x, y [, maxWidth]) fills in text.
- strokeText(text, x, y [, maxWidth]) outlines text.
