# Enumerations

The enumeration is a set of constants.

The name should be formatted in upper camel case.
Each line contains at most one constant.

```javascript
Tools.Status = {

    WAITING: 1,
    LOADING: 2,
    READY: 3,
    FAILED: 4
};
```

```javascript
Texture.Format = {

    RGBA8: SomeAPI.rgba,
    RGB8: SomeAPI.rgb,
    A8: SomeAPI.alpha
};
```

The dot notation should always be used to access constants.

```javascript
Texture.Format.RGBA8
```

[back](readme.html)