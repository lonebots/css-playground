# Styling links

common link styles are

1. `text-decoration` : set to underline(default) or none (without underline)
2. `cursor` : to controll mouse pointer changing when hovered over the link
3.

**Psuedo Class** : A class that tracks the current state of a html element

- common psuedo classes are : `visited` ,`hover`, `focus`, `active`.
- In this case we have two states ( visited links/ non-visited links)
- How to define a psuedo-class

```css
a {
  /*regular styles*/
}

a:visited {
  /*decides what happens afte the link is visited*/
}
```

_Note: psuedo class has more specificity that normal elements and proper order should be maitained while defining them Order - (visited > hover > active)_
