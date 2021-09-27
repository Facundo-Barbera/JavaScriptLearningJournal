#Comments...

Comments in any programming language are key to make your code understandable.
It's necessary to keep your code readable for multiple reasons:

* You might lose track on what you are doing.
* You might want other people to read your code.
* It looks cool. (Text editors with colors are extra cool.)

#The Learning journal

To make comments in JavaScript:

```js
// This is a single line comment.

/*
This is a multi-line comment.
You can add more text to it.
 */
```

Writing // at any point will make the rest of that line a comment:
```js
// Comments are cool.
```

Wiring /* will start a multi-line comment which needs to be closed with */:
```js
/*
But...
Long comments are cool too!
 */
```

You can also use comments to stop code from executing!
```js
console.log("This code will execute!")
// console.log("This code won't!")
```

Another example of commenting would be to describe what you are doing:
```js
// Prints "Hello World!" to the console.
console.log("Hello World!")
```