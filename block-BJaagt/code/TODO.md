Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // output
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // output
```

Before going to the declaration inside the scope, interpreter will first execute the code outside the scope which console log username. Therefore the output will throw an error for undefined.

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```
Since, username is declared inside a scope the console log will throw an error of undefined.


4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); // output
```
Again, it will throw an error because the variable is inside a scope.

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // output
```
Same variable name cannot be used twice therfore it will throw an error of already declared.

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```
Same variable name cannot be used twice therfore it will throw an error of already declared.

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // output
```
Same variable name cannot be used twice therfore it will throw an error of already declared.

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
```

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
```
