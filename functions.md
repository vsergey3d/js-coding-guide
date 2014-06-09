# Functions

Do not use global functions.

The name should be formatted in lower camel case.
There should be no space between the name of a function and the left parenthesis.
If a function literal is anonymous, there should be one space between the word function and the left parenthesis.
There should be one space between the right parenthesis and the left curly brace.

The function body should be indented one level (four spaces).

```javascript
Math.mul = function (a, b) {
    return a * b;
};
```

Additional empty lines should be inserted before and after internal `var` statement.

```javascript
function someFunction(one, another) {

    var someVar = 3;

    // ...
}
```

Functions declared inside of other functions should be declared immediately after the `var` statement (or should be assigned after regular variables).

```javascript
var SOME_CONST = 25,

    callback = function () {

        // ...
    };
```

Immediately-invoked function expressions (IIFE) should be surrounded with parentheses.

```javascript
(function () {

    // ...
}());
```

Closures and IIFE should be used to encapsulate function's temporary variables.

```javascript
myFunc = (function() {

    var myTempVar = makeSome();

    return function (args) {

        // using temporary variables
    };
}());
```

[back](readme.html)