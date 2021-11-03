1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
This will actually return a value you can use

// second
function sum(a, b) {
  console.log(a + b);
}
Will give you the answer in the console log but is undefined


```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

The first variable will return a value.
The second variable will be undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

The third number will be ignored

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
   Yes. You call store any function and variable in another variable and call it later.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function (name = "Arya") {
return `Hello ${name}`
}

6. What will be the output of the function below and why?

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

showMessage();
```

It will say "Hello, John"
Iit will first look for the userName variable in local scope and if it can't find it, it will look for the variable in the global scope.

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

alert(userName); // "John"

showMessage(); // "Hello, John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
   When you omit the function name.
   Example
   let one = function () {
   console.log("test")
   }

   let two = function () {
   alert("test")
   }

   let three = function () {
   prompt("test")
   }

9. Can function declaration be a Anonymous Function? Explain
   No. Function expression can omit anonymous functions. Whereas dinction declarations cannot/

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

numberOne
isGreatThan
isLowerThan
doubleNumber
findConnection

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
