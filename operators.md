# Operators

Do not use `==`, `!=`, `++`, `--` operators.

No space should separate an unary operator and its operand (except `typeof`).
All binary operators (except `.` and `(` and `[`) should always be separated from their operands by one space.

```javascript
var negate = !value,
    sum = a + b,
    result = a1 * b1 + a2 * b2;

map["some"] = "other";

call(a, b);
```

The ternary operator is only for assigning values conditionally. Do not use it as a shortcut for an `if` statement.

```javascript
var value = condition ? value1 : value2;
```

When assigning a value to a variable, use parentheses around a right-side expression that contains a comparison.

```javascript
var value = (some < another);
```

Parentheses should be always used around unary cast to number operator.

```javascript
var value = (+some),
    total = one + (+another.value);
```

Concise cast to boolean `!!` should be used instead of comparison operations.

```javascript
var enabled = !!some;
```

`||` operator should be used as the "default" operator.

```javascript
var value = count || 0;
```

`&&` operator should be used instead of cascade conditions.

```javascript
var child = node && node.children && node.children[index];
```

[back](readme.html)