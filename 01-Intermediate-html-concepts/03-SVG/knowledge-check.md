# [SVG Knowledge Check](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-svg#knowledge-check)

## What is the xmlns attribute?
This specifies what dialect of XML you’re using. Without it, some browsers will not render your image or will render it incorrectly

## What are some situations where you wouldn’t want to use SVG?
If the image is really complex

## What are the benefits of “inlining” your SVGs? What are the drawbacks?
 Will allow you to alter the image dynamically via CSS or JavaScript. 
 It makes your code harder to read, makes your page less cacheable, and if it’s a large SVG it might delay the rest of your HTML from loading.
