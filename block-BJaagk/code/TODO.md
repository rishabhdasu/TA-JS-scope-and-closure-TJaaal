1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage_marks = function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentage_marks = function (marks, total) {
  return (marks * 100) / total;
}

let percentage_marks = (marks, total) => {
  return (marks * 100) / total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
// Function Expression

let percentage = function (marks, total) {
  return (marks * 100) / total;
}

```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

// Function Declaration

let percentage_marks = function percentage(marks, total) {
  return (marks * 100) / total;
}

```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

```js
Functions are objects and objects are values in javascript , they can be copied, assigned or declared in any part of the code. Therefore we can use functions as an expression.
```

4. Why is a function call an expression in JavaScript?

```js
An expression is a set of code or instructions which produces a value or an output. And, sicne wehn we call a function we are expeting an output or a result from that 
function therefore it is called a function expression.
```

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Functions can be used as an expression so this is VALID
five = add; // Answer
five = five(10, 11); // Answer
five = function () {
  return 'Hello';
}; // Answer
```

6. What is the difference between function definition and function call? Explain with an example.

```js 
Function definition is defining or creating a function block with a function name which can be used later in the code. Example :- 

function percentage(marks, total) {
  return (marks * 100) / total;
}

Function  call is a calling or executing the function defined and decalred earlier to get an output or some result from the function. Example :-

percentage(24, 100);

```


7. What is the similarities between function definition and function call?

```js 
similarity between a function definition and a function call is that both are expressions.

```

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid


The above code is valid because a function is an object in javascript and therefore we can add a property to the function.

```

9. What is higher order function explain with an example.

```js

Higher-order functions are functions that take other functions as arguments or return functions as their results.

Taking an other function as an argument is often referred as a callback function, because it is called back by the higher-order function. 
There are mnay higer order functions in Javascript lilke forEach(), filter(), map(), reduce(), e.t.c.,.

```

10. Explain what is callback function. Why you can pass a function inside a function?

```js
Any function that is passed as an argument in another function so that it can be executed in the other function is called a callback function.
Since functions are objects and objects are valklues which can be passed as an argument inside a function so like any other object a function can also be passed as a functions inside another function.
```
