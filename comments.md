## Comments

One whitespace should be uses before a trailing comment.

```javascript
doSomeAction(); // comment
doAnotherAction(); // comment
```

Additional empty line should be inserted before single line comment.

```javascript
// comment
doSome();

// comment
doAnother();
```

Multiline comments should be only used to document code that requires more explanation.

```javascript
/*
comment
...
*/
```

Comments may be used to annotate pieces of code with additional information.

The acceptable annotation keywords are:

* `TODO` - Indicates that the code is not yet complete. Information about the next steps should be included.
* `FIXME` - Indicates that the code is problematic and will be fixed soon. Information about the problem should be included.
* `HACK` - Indicates that the code is using a hack. Information about the hack should be included.

```javascript
doSomeAction(); // TODO: comment
doAnotherAction(); // HACK: comment

// FIXME: comment
doSomeAction();
doAnotherAction();

/*
HACK: comment
comment
*/
doSomeAction();
```

[:arrow_backward:](statements.md)
