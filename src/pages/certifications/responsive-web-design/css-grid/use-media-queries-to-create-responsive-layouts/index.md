---
title: Use Media Queries to Create Responsive Layouts
---
## Use Media Queries to Create Responsive Layouts

In this challenge, you are required to make the header occupy the top row completely, and the footer area occupy the bottom row completely, when the viewport width is 400px or more by using a media query to rearrange the grid areas.

### Hint

You can define where to place your cells in the grid like this:
````css
grid-template-areas:
  "a b c"
  "a b c"
  "c c c";
````

### Solution

In order to make the header occupy the top row, advert and content the middle row, and footer the bottom row, change the code in grid-template-areas like this:
````css
grid-template-areas:
  "header header"
  "advert content"
  "footer footer";
````
