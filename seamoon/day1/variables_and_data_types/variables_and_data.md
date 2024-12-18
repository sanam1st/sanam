# Variables and data types

## declaration

```js
    let vs const vs var
```

### var

- var is a function-scoped variable, meaning it is available within the function it is defined.

### let

- let is a block-scoped variable, meaning it is only available within the block it is defined.

### const

- const is a block-scoped variable, meaning it is only available within the block it is defined.
- const cannot be reassigned.
- const must be initialized at the time of declaration.

NOTE: JS is a dynamically typed language, meaning you don't have to specify the data type of a variable when you declare it. The data type will be determined automatically when the program is being processed.

<!-- TODO: -->

- learn about hoisting in JS

## Data types

- null
- undefined
- number
- string
- boolean
- object
- bigint

### Object

- Object is a collection of key-value pairs.

eg:

```js
const person = {
  name: "John Doe",
  age: 30,
  isEmployed: true,
};
```
