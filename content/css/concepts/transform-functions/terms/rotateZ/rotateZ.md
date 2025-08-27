---
Title: 'rotateZ()'
Description: 'A 3D rotation of an element around its z-axis by a specifid angle.'
Subjects:
  - 'Web Design'
  - 'Web Development'
Tags:
  - 'Elements'
  - 'Functions'
  - 'Positioning'
  - 'Values'
CatalogContent:
  - 'learn-css'
  - 'paths/front-end-engineer-career-path'
---

The CSS **`rotateZ()`** function is a 3D rotation of an element around its z-axis by a specifid angle. This rotation can either be clockwise or anticlockwise and is commonly used in [animations](https://www.codecademy.com/resources/docs/css/animations), UI interactions, or creative web layouts.

## CSS `rotateZ()` Syntax

```pseudo
transform: rotateZ(angle);
```

**Parameters:**

- `angle`: Defines the degree of rotation. It accepts values in degrees (`deg`), radians (`rad`), gradians (`grad`), or turns (`turn`).
  - Positive values = Clockwise rotation around the z-axis
  - Negative values = Anticlockwise rotation around the z-axis

## Example 1: Basic Rotation in CSS Using `rotateZ()`

In this example, the `.box` element is rotated 60 degrees clockwise from its original position using CSS `rotateZ()`, creating a diamond-like appearance:

```css
div {
  background-color: orange;
  width: 100px;
  height: 100px;
  margin: 30px;
}

.box {
  background-color: lightblue;
  transform: rotate(60deg);
}
```

Here is the output:

![The CSS rotateZ() function rotates a box 60 degrees clockwise from its original position, creating a right tilting appearance](https://raw.githubusercontent.com/Codecademy/docs/main/media/css-rotatez.jpg)
