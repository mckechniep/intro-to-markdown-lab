# Writing a Function in JavaScript

![woman frustrated with computer](https://images.unsplash.com/photo-1516534775068-ba3e7458af70?w=1200&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTh8fGZydXN0cmF0ZWQlMjB3aXRoJTIwY29tcHV0ZXJ8ZW58MHx8MHx8fDA%3D)
In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```const functionName = (params) => {
  // code to be executed
}
```

- **const:** const should be used whenever a function expression is assigned to a variable.
  The function name: The name you choose for the function.
- **Parameters:** Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
- **The arrow syntax:** Indicates that this will be a function.
- **The body:** The statements that make up the function itself. Surrounded by curly braces.

**_Example:_**

```const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ).

## 2. Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

**_Example:_**

`greet('Alice'); // Outputs: Hello, Alice! `

## 3. Return values

Functions can process data input and output a value using the _return_ keyword.

**_Example:_**

```const addNums = (numA, numB) => {
  return numA + numB
}
```

` const total = addNums(2, 4);`

` console.log(total) // Expected value: 6`

For more information on functions and how they are used in JS, check out the MDN docs.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
