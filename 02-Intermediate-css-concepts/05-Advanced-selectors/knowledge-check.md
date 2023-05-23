# [Advanced Selectors Knowledge Check](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-advanced-selectors#knowledge-check)

## What is the difference between the child combinator and the descendant combinator?
The child combinator will only select the direct children, where as the descendant combinator will select children and grandchilden 

## How does the syntax of pseudo-classes and pseudo-elements differ?
Pseudo-class selectors are prefixed with a single colon and are a different way to target elements that already exist in HTML. Pseudo-elements are prefixed with two colons and are used to target elements that don’t normally exist in the markup.

## Do pseudo-classes exist somewhere in HTML? Do pseudo-elements?
Pseudo-classes do exist in the HTML and pseudo-elements do not.

## Name two ways you could select every second child of an element, starting with the first
1. div:nth-of-type(2)
2. div:nth-child(2n)

## What is the difference between div:first-child and div:last-child? What will each select?
The first-child will select the first element inside of the div element and last-child will select the last element inside of the div.

## What selector would you use to style a button a user is currently hovering over? How about one that is currently being clicked on? 
:hover
:active

## How could you select all input elements with a type of text?
 input[type="text"] 

## How could you select all classes that begin with thunder?
[class^='thunder']
