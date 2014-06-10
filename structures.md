## Structures

`{}` should be used instead of `new Object()`.

The names of properties should be formed from letters and digits (do not use `$`, `\`, etc).

Each line contains at most one property.

```javascript
var settings = {
        width: 640,
        height: 480,
        color: {
            r: 8,
            g: 8,
            b: 8,
            a: 0
        }
    };
```

The dot notation should always be used to access properties.

```javascript
settings.width = 1280;
settings.height = 720;
```

[:arrow_backward:](enumerations.md) [:arrow_forward:](functions.md)