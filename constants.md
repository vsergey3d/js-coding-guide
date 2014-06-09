# Constants

Constants should be declared as regular variables or static properties.

The names should be formatted using all uppercase letters with words separated by a single underscore and formed from letters and digits (do not use `$`, `\`, etc).

```javascript
var MAX_ITERAIONS = 150;
```

Constants should always be placed before regular variables.

```javascript
var PI = 3.14,
    x, y, z;
```

```javascript
var MAX_USER_COUNT = 1024,
    DEFAULT_USER_NAME = "noname",

    users = {},
    counter = 0;
```

[back](readme.html)