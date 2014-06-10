## Primitives

### Numbers

Numbers should be written as decimal integers, e-notation integers, hex-notation integers or floating-point decimals (with at least one digit before and one digit after the point).

```javascript
0    115    1e24    0.259    15.7    0xEA    0xFFCCFF
```

Do not use octal literals.

### Strings

Strings should always use double quotes.
Strings that require inner quoting should use double outside and single inside.

```javascript
"Something"
```

```javascript
"<p style='color:red'>"
```

Do not use multiline literals, use string concatenation instead.
The wrapped line should be indented one level (four spaces).

```javascript
"Lorem ipsum dolor sit amet, consectetuer adipiscing " +
    "elit. Aenean commodo ligula eget dolor. Aenean " +
    "massa. Cum sociis natoque penatibus et magnis."
```

### Arrays

`[]` should be used instead of `new Array()`.

There should be no space after the opening square bracket or before the closing square bracket.

```javascript
[10, 15, 20, 25]
```

```javascript
[1, 2, 4, 8, 16, 32, 64, 128, 256, 512,
    1024, 2048, 4096, 8192, 16384]
```

```javascript
[
    "lorem ipsum dolor",
    "sit amet, consectetuer",
    "aenean commodo ligula eget dolor",
    "sociis natoque penatibus"
]
```

### Dictionaries

`{}` should be used instead of `new Object()`.

There should be no space after the opening curly bracket or before the closing curly bracket.

A key should always have the string type.

```javascript
{"bike": 3, "car": 1, "plane": 7};
```

```javascript
{"na6sdn": 55, "sydt63": 3, "s6dbrj": 85,
    "ccddy2": 74, "lld692": 31, "ssst89": 65, "ssaa22": 2};
```

```javascript
{
    "BlanchedAlmond": true,
    "Cyan": false,
    "DarkGoldenRod": true,
    "LightGoldenRodYellow": true
};
```

Square brackets should always be used instead of the dot notation.

```javascript
var fruits = {"apple": 12, "mango": 4};

fruits["sweet lime"] = 7;
fruits["apple"] = 10;

delete fruits["mango"];
```

### RegExps

The literal notation should be used instead of `RegExp` constructor.

### Undefined

Do not use the `undefined` assignment.

[:arrow_backward:](indentation.md) [:arrow_forward:](variables.md)