# CSS grids

- used for setting elements in to grid in the screen ( set `display:grid`)
- we can play with the followng grid properties
  - `gap` : to set the gap between the rows and the columns.
  - `grid-template-columns` - `repeat(n,fractionlist)` etc to set the number of columns to be displayed on the screen.
  - `grid-template-rows` - refer above, set similar properties to the rows.
  - `grid-auto-rows` - `minmax(minvalue,maxvalue)` we can also set to auto so as to automatically adjust to the situation.
  - `grid-auto-columns`- specify the same as above for columns
- We can use the psuedo-class selectors such as `nth-child()`, `first-child` `last-child` to style individual grid elements. some of the other properties we can controll with this are;
  - `grid-column-start` - start of the grid column.
  - `grid-column-end` - end of the grid column.
  - simlar properties goes to the rows as well.
  - also short hands works. eg; `grid-column:1/4` - grid-column:start/end
- We can nest a grid inside a another grid, similar to flex inside flex.
  - `align-content` : vertically align a content in the grid element.
  - `justify-content` : horizontally align a content in the grid element.
  - `place-content` : to set the align(vertically) and justify(horizontally)

## Learning Tool

1. [CSS Grid Garden](https://cssgridgarden.com/)
