1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
sum(12, 24, 35)

// second
function sum(a, b) {
  console.log(a + b);
}
```
In first function we used return, and second function we used console.log. return is used to get the out come of something (i.e function) console.log is used in to get the out put of a statement



2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Value of first function is '36', and second value is Undefined.


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

  The output will be 36 because in first function we define only two value so here return only 12 + 24 = 36.


4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

  Yes we can, but we don't use function name sum.  The function above is actually an anonymous function.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
 
 function sayHello(name) {
  return "Hello Arya";
 }

 sayHello();

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
The output will be 'Hello, John' because here already store the value of variable userName 'John'.

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName);  // John

showMessage(); // 'Hello John'

alert(userName); //  John
```


8. What is a Anonymous Function give example of three functions.

Anonymous Function is a function that does not have any name associated with it. Normally we use the function keyword before the function name to define a function in JavaScript, however, in anonymous functions in JavaScript, we use only the function keyword without the function name.

  ex:  const addNumber = function (numA, numB) {
         return numA + numB;
       }


       let sayHello = function(name) {
          console.log (name);
       }


       const square = function(num) {
         return num * num;
       }


9. Can function declaration be a Anonymous Function? Explain

Yeah function declaration can be a Anonymous function. you can pass the parameter by using the same name , and in function accept those parameter and return that or use those values.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

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
function showMessage(..) // shows a message
getAge(..) // returns the age (gets it somehow)
calcSum(..) // calculates a sum and return the result
createForm(..) // creates a form (and usually returns it)
checkPermission(..) // checks a permission, return true/false