# HTML Canvas Graphics 
The HTML \<canvas> element is used to draw graphics on a web page.

The graphic to the left is created with \<canvas>. It shows four elements: a red rectangle, a gradient rectangle, a multicolor rectangle, and a multicolor text.

### What is HTML Canvas?
The HTML \<canvas> element is used to draw graphics, on the fly, via JavaScript.

The \<canvas> element is only a container for graphics. You must use JavaScript to actually draw the graphics.

Canvas has several methods for drawing paths, boxes, circles, text, and adding images.
## Canvas Examples
A canvas is a rectangular area on an HTML page. By default, a canvas has no border and no content.

The markup looks like this:

\<canvas id="myCanvas" width="200" height="100"></canvas>
Note: Always specify an id attribute (to be referred to in a script), and a width and height attribute to define the size of the canvas. To add a border, use the style attribute.
# charts 
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

To see how to use chart.js we’re going to create a set of 3 graphs; one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart; the second will show which countries the customers come from, this will be the pie chart; finally we’ll use a bar chart to show profit over the period.