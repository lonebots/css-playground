# CSS Box Model

- All HTML elements can be considered as boxes.
- It consist of `Margin`, `Border`, `Padding` and the `Actual-content`.

```txt
When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.
```

## Best practice

- It is always nice to reset the default user agent styling applied to a page using bellow `wild-card-selector`

```css
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
```

- In the above case `border-box` changes the default type `content-box` annd it incorporates both `border + padding` , adjusting the orignal `content` size.

## Setting up padding and margin

```css
p {
  /* how to set up margin - with/without shorthand */

  margin: 1em 2em 3em 4 em; /*top right left bottom*/
  margin: 1em 2em 3em; /*top right-left bottom*/
  margin: 1em 2em; /*top-botton right-left*/

  /* same can be applied to padding */
}
```

## some cool properties to discuss

- **outline** - comes outside of the border; gives a regular outline
- **outline-offset** - an offset given to the outline relative to the border.
