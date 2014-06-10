## Statements

Each line contains at most one statement.

Condition statements should have the following form (`[]` - optional blank line):

```javascript
if (condition) {
    []
    statements
}
```

```javascript
if (condition) {
    []
    statements
    []
} else if (condition) {
    []
    statements
    []
} else {
    []
    statements
}
```

```javascript
switch (expression) {
case expressionA:
    []
    statements
    []
    break;
    []
case expressionB:
case expressionC:
    []
    statements
    []
    break;
    []
default:
    []
    statements
}
```

Loop statements should have the following form (`[]` - optional blank line):

```javascript
for (initialization; condition; update) {
    []
    statements
}
```

```javascript
for (variable in object) {
    []
    statements
}
```

```javascript
while (condition) {
    []
    statements
}
```

```javascript
do {
    statements
    []
} while (condition);
```

Do not use parentheses around `return` value unless they make it more obvious.

```javascript
return (conditionA && conditionB);
```

Do not use `with` statement.


[:arrow_backward:](modules.md) [:arrow_forward:](comments.md)