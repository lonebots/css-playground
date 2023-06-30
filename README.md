## Reference

1. [CSS Tutorial - Full course for beginners](https://www.youtube.com/watch?v=OXGznpKZ_sA)
2. [CSS - W3School](https://www.w3schools.com/css/default.asp)

## CSS Basic

CSS stands for _cascading style sheets_, it is the most general way used by programmers to style a website. There are three ways you can add CSS to an HTML page ( their priority is also in the given order)

1. Inline css - provided with the tag using `style` property.
2. Internal css - provided with the html file using `<style>` tag.
3. External css - provided with the help of `.css` external file, which is then linked to the HTML page

- Styling in css is provided by selecting a `tag`, and listing style as `property:value` pairs. For example;

```css
p {
  color: red;
  font-size: 50px;
}
```

## CSS Selector

This selects the particular HTML tag for applying custom styles. Common types are

1. class selector - selection based on class name.
2. id selector - based on id name. `#id` is how you select using id._(Rare to use)_.
3. \* selector(universal selector) - select all the elements.
4. element selector - based on the HTML tag name.
5. Group selector - selecting a group of HTML tags.
6. Nested selector - based on nested tags or class names.
   Then there are combinations possible, for example `class_name.element_name` or `element_name.class_name` etc

## Things to keep in mind while using CSS

1. CSS won't check for syntax correctness and would ignore anything that breaks it.
2. Make the stylings reusable.
3. Cascade - CSS work from top down; so that it apply the last style found when duplicates occurs.
4. Class selector has more specificity than element selector; they retain the styles even if it's element style is changed.
5. We can always `inspect` to see which stylings are applied to a particular tag on the DOM.

## Rarest

1. `!important` keyword along with the property value over-rides every other style applied to the particular selection._(Donot use this)_

## Additional Resources

1. [CSS validator website](https://jigsaw.w3.org/css-validator/) - A website to check/validate your css styling.
2. [Specificity Calculator](https://cssbootcamp.com/css/specificity-calculator) - How you determine the priority of a style( in external file). `!important` overrides everything.
