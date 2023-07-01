# CSS List styles

These include properties for styling a list,(ordered or unordered)

Some of the common styles are

1. `list-style-type` : we can change the bullet points or markers here.
2. `list-style-image` : for setting image to list marker points.
3. `list-styel-position` : used to specify the marker position

- shorthand

  - `list-style:<type> <image> <position>`

- psuedo-class

  - `nth-child()` - select nth child in the list.
  - usage :
    ```css
    ul li:nth-child(2) {
      color: red;
    }
    ```
  - The above code makes the second child `red` in color.
  - It also accepts parameters like `odd`, `even`, etc.

- psuedo-element : elements class that start with `::` here it is `::marker`.

  - `::marker` is used to style the markers of the list.

- `value` property - specified in the `<li>` tag and used to give the element number a value

Notes

- Even when `list-style-type` is set to `none`, there will be default padding and we can manually set it to `padding:0;`, for removing it.
- If we set the `color` property it changes the markers as well the list of text.
- There are properties like `start`(to specify the starting count of ordered list) and `reversed` to make the count reverse.
