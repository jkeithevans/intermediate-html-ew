# [Positioning Knowledge Check](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-positioning#knowledge-check)

## What is the difference between static and relative positioning?
Static is the default position of every element, and properties top, right, bottom, and left do not affect the position of the element. Relative on the other hand is pretty much the same as static, but properties top, right, bottom, and left displace the element relative to its normal position in the flow of the document.

## What is absolute positioning useful for?
This property is really useful when you want to position something at an exact point on the screen, without disturbing any of the other elements.

## What is the difference between fixed and sticky positioning?
position: fixed generally means fixed to the viewport*. You tell it where to position itself, and it stays there as the user scrolls. It is out of the flow of the rest of the document. position: sticky scrolls along like anything else until it reaches the offset that you set. At that point, it acts like it’s fixed. There is a catch though, it must stay within it’s containing block (it’s parent)! Once that containing block scrolls off the page, it leaves with it.

