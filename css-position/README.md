# CSS Position

- It specifies the type of positioning method used for an element.
- The possible values for this property are;
  - `static`
  - `relative`- The position is relative to it current container.
  - `fixed`- once fixed it alway stays there.
  - `absolute`- we can specify with respective to which relative container it needs to be absolute with.
  - `sticky`

Note;

- In order the last element in the HTML page comes on top of the other element. This can be tweeked using the `z-index` property in the css.

CSS Trick;

- When trying to remove an element from the viewport we can keep `position:absolute` and then keep `left:-100000px` really high negative value.
