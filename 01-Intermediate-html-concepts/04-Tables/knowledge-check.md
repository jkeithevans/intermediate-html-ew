# [Tables Knowledge Check](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-tables#knowledge-check)

## What is a table?
A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data

## Why is it a bad idea to use HTML Tables for page layout?
1. Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user.
2. Tables produce tag soup. This can result in the code being harder to write, maintain, and debug.
3. Tables are not automatically responsive.

## What are caption elements useful for?
This is useful for all readers wishing to get a quick idea of whether the table is useful to them as they scan the page, but particularly for blind users.

## What is the scope attribute?
It tells screen readers exactly what cells the header is a header for — is it a header for the row it is in, or the column. Screen readers will recognize markup structured like this, and allow their users to read out the entire column or row at once, for example.
