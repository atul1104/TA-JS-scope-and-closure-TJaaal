1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
};

let percentage = (marks, total) => (marks * 100) / total;
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

// Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

// Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;

// Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

```js
//Expression is something that resuts in value. Values are string, number, boolean, object, undefined and null. Function itself is an object therefore fumction definition is an expression in javascript.
function add() {}
let add = function () {};
```

4. Why is a function call an expression in JavaScript?

```js
function add(a, b) {
  return a + b;
}

function addAgain() {}

//Functio always returns some value. Even if a function does not have any return statement it returns "undefined", and it is a value. Therefore function call is an expression in javascript.
```

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer Valid
five = add; // Answer Valid
five = five(10, 11); // Answer valid
five = function () {
  return "Hello";
}; // Answer valid
```

6. What is the difference between function definition and function call? Explain with an example.

```js
function add(a, b) {
  return a + b;
} //This is a function definition.

add(2, 3); //This is a function call.
```

7. What is the similarities between function definition and function call?

```js
//Function definition is an expression, because function is an object in itself.
//function call is an expression, because a function always returns a value.
```

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // valid
```

9. What is higher order function explain with an example.

```js
//HOF is that which accepts a function definition.
//HOF is that which returns a function definition.

function(cb){
  cb();
}

function(){
  function main(){

  }
  return main
}
```

10. Explain what is callback function. Why you can pass a function inside a function?
