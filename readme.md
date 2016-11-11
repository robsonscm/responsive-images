Create a HTML file and an external CSS file that shows responsive images using the <picture>, <source>, and <img> tags combined with a responsive layout driven by CSS media queries.

As the user adjusts the size of your page two things will happen:

1. The media queries in your CSS file will be altering the layout and the number of columns that appear on the page.

2. The media queries in your HTML <source> elements will be choosing the most appropriate size image file to load and display.



To create a proper image grid that expands as the page is adjusted, use an HTML <ul> plus an <li> element for each picture.



Images

Download these images - raw-images.zipView in a new window

Each image needs to be resaved and optimized for the web. Crop and convert each image into three sizes:

Large: 800px width x 600px height - to be used when the page width is greater than 1500px.

Medium: 600px width x 450px height - to be used when the page width is between 700px and 1500px

Small: 400px width x 300px height - to be used when the page width is less than 700px

These sizes should be used in your <source> elements.

Use the medium size as the default for your <img> elements.

All your <picture> and <img> elements should be given a default max-width of 90% so that they can resize to fit their container.



Image Attribution

Be sure to add the attribution to your images as a comment in either your CSS or HTML.

All images used belong to:

Markus Spiske - https://500px.com/markusspiske (Links to an external site.)

Yinan Chen - https://500px.com/webmaster85 (Links to an external site.)

Fahim Akhter - https://500px.com/fahimakhter (Links to an external site.)



Layout

In your webpage there will be 3 layouts. Use percentages to control the width of the <li> elements and the margins between them.

1. Less than 600px - one column layout

2. Between 600px and 1200px - two column layout

3. Above 1200px - four column layout
