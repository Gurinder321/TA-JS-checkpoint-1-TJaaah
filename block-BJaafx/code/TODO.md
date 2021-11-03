1. Using loops take 10 inputs from user and find the average of all the numbers.

let i = prompt("What's your number?")

while (i < 10) {
let number = i
i++
}

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println("hi");
  i++;
}
```

println isn't the right statement. It would say return.
It will print "hi" 3 times

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum(arr = 10){
var sum = 0;
for(var i = 5; i< 429; i++) {
if(i % 2 === 0) {
sum = sum + i;
}
}
return sum;
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

function getEvenSum(arr = 10){
var sum = 0;
for(var i = 5; i< 429; i++) {
if(i % 2 !== 0) {
sum = sum + i;
}
}
return sum;
}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

function getProductOfDigits(num) {

}

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return "Bigger than 5";
  }

  if (num < 5) {
    return "Smaller than 5";
  }

  return num;
}

check(10); // "Bigger than 5"
check(1); // "Smaller than 5"
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") return "You are arya";
  if (name === "John") return "You are john";
  return "Who are you";
}

getOutput("Arya"); // "You are arya"
getOutput("John"); // You are john"
getOutput(); // "Who are you"

There is a return after every if statement.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") console.log("You are arya");
  if (name === "John") console.log("You are john");
  return "Who are you";
}

getOutput("Arya"); // "Who are you"
getOutput("John"); // "Who are you"
getOutput(); // "Who are you"

Because the return is only on "Who are you". However, the answers are still being console logged

```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Yes, however, only the first return function will run.

function isGreatThan(num) {
if (num < 10) return `${num} is less than 10`;
if (num > 11) return `${num} is less than 10`;
return `${num} is equal to ${num}`;
}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
    The difference between for loop and while loop is that in for loop the number of iteration to be done is already known and is used to obtain certain result whereas in while loop the command runs until a certain condition is reached and the statement is proved to be false.

WHILE LOOP
let i = 0;
while (i < 3) { // shows 0, then 1, then 2
alert( i );
i++;
}

FOR LOOP
for (let i = 0; i < 3; i++) { // shows 0, then 1, then 2
alert(i);
}
