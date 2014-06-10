## Indentation

The unit of indentation is four spaces.

Line length should be no longer than 100 characters.
Long lines should be wrapped after an operator (ideally after a comma).
The following line should always be indented one level (four spaces).

Logical sections of code should be separated using one blank line.
Declarations of constructors and enumerations should be separated using one or two blank lines.

Liberal spacing (for alignment or decoration) should be avoided.

```javascript
// Wrong

var colors = {
    "Cyan":                 false,
    "Black":                true,
    "DarkGoldenRod":        true,
    "LightGoldenRodYellow": true
};

// Right

var colors = {
    "Cyan": false,
    "Black": true,
    "DarkGoldenRod": true,
    "LightGoldenRodYellow": true
};
```

[:arrow_backward:](naming.md) [:arrow_forward:](primitives.md)