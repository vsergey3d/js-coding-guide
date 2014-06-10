## Errors

Do not throw primitives and literals.

Errors should be created using the `new` operator.

```javascript
throw new Error("message");
```

Try-catch statements should have the following form (`[]` - optional blank line):

```javascript
try {
    statement
    []
} catch (error){
    []
    statement
}
```

Custom errors should use following pattern:

```javascript
MyError = function (message, name) {

    this.stack = (new Error()).stack; // non-standard!
    this.name = name || "MyError";
    this.message = message;
};

MyError.prototype = Error.prototype;
```

Inheritance from the custom error:

```javascript
OtherErrorProto = function () {

    // methods
};

OtherErrorProto.prototype = MyError.prototype;


OtherError = function (message, ...) {

    Error.call(this, message, "OtherError");

    // properties
};

OtherError.prototype = new OtherErrorProto();
```

[:arrow_backward:](objects.md) [:arrow_forward:](modules.md)
