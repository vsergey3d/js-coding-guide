# Variables

Do not use global variables.

Variables should use lower camel case capitalization.
The names should be formed from letters and digits (do not use `$`, `\`, etc).

All variable declarations should be placed at the beginning of a scope using a single `var` statement.
All lines after the first should be indented one level (four spaces).
One blank line should be placed after the last variable declaration.

```javascript
var index = 0;
```
```javascript
var name = "Jo",
    profession = "artist",
    age = 35,
    i, l;
```
```javascript
var x = 14.43, y = 30.2, z = 0.23,
    xy = x * y, yz = y * z, zx = z * x;
```
```javascript
var indices = [14, 23, 5, 3],
    fruits = {"apple": 15, "mango": 9},
    fragments = [
        "lorem ipsum dolor",
        "sit amet, consectetuer",
        "aenean commodo ligula eget dolor",
        "sociis natoque penatibus"
    ];
```

[back](readme.html)