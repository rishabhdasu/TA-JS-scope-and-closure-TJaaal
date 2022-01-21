1. What does thread of execution means in JavaScript?

When a code is executed in JS, it goes through the code line by line and. Each line of code is executed independently while communicating between one another.

2. Where the JavaScript code gets executed?

Everything inside Javascript is excuted inside a execution context. It is like container which holds all the information of Javascript environment for the JS code to be executed.

3. What does context means in Global Execution Context?

Execution context in JS is the environment in which the JS code is to be executed.

4. When do you create a global execution context.

It is created when we load the file for the first time even when it is empty.

5. Execution context consists of what all things?

Execution context has 2 major things. First, the GLOBAL EXECUTION CONTEXT which is executed when the JS loads the file for the first time. And it is executed only once and that is on the first loading of the JS file. All global code that are not inside any function or any object are executed inside the GEC. Second, FUNCTION EXECUTION CONTEXT is executed whenever the JS engine finds a new function to be executed. It can be executed more than once depending upon the number of times a function needs to be executed.

6. What are the different types of execution context?

Execution context has 2 major things. First, the GLOBAL EXECUTION CONTEXT which is executed when the JS loads the file for the first time. And it is executed only once and that is on the first loading of the JS file. All global code that are not inside any function or any object are executed inside the GEC. Second, FUNCTION EXECUTION CONTEXT is executed whenever the JS engine finds a new function to be executed. It can be executed more than once depending upon the number of times a function needs to be executed.


7. When global and function execution context gets created?

GLOBAL EXECUTION CONTEXT which is executed when the JS loads the file for the first time. And it is executed only once and that is on the first loading of the JS file. All global code that are not inside any function or any object are executed inside the GEC.

8. Function execution gets created during function execution or while declaring a function.

Function execution is created whenever a function needs to be executed.


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./code/Snippets.executionThread_diagram1.png)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/executionThread_diagram2.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/executionThread_diagram13.jpg)
