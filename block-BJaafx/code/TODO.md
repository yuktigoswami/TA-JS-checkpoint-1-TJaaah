1. Using loops take 10 inputs from user and find the average of all the numbers.

```js
let num = +prompt ("Enter 10 numbers") ;

let sum = 0;
for (let i = 0; i < num.length; i++) {
sum += num[i];
}
let average = (sum / num.length)
console.log (average);

```


2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
hi
hi
hi

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js

function getEvenSum(max = 10) {
  let sum  = 0;
  for (let i = 0; i <= max; i++);
  if (i % 2 == 0) {
  sum += i;
  }
  return sum;
}
getEvenSum();
```


4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

```js
function getOddSum(max = 10) {
  let sum = 0;
  for (let i = 0; i <= max; i++);
  if (i % 2 !== 0) {
    sum += i;
  }
  return sum;
}
getOddSum();
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.


function getProductOfDigits(num) {
  let product = 1;
  for (let i = 1; i >= 1; i++) {
    product *= i;
    retrun product;
  } 
  
  if (i <= 0) {
    return 'not a valid input';
  }
}

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // Bigger than 5, because if we pass argument 10, and 10 > 5.
check(1); // Smaller than 5, if we pass argument 5 and 1 < 5.
check(5); // 5 because we pass argument 5 , and 5 is not greater than 5 or smaller than 5, so return number 5.
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // You are arya because in if statement we define the name === Arya , and return value You are arya, we call the function and pass argument arya.
getOutput('John'); // You are john because in if statement we define the name === John , and return value You are John, we call the function and pass argument John.
getOutput(); // who are you because we did not pass any argument in function call.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // Who are you because here return value who are you, and you are arya is print in console in inspect of the browser.
getOutput('John'); // Who are you
getOutput(); // Who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Yes, you can have multiple return statements in a function. When a return statement is reached, the function will immediately exit and return the specified value to the caller.
  
  function isEven(num) {
    if (isEven % 2 === 0) {
      return true;
    } else {
      retrun false;
    }
  }
  isEven();

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

`for` loop is used when the number of iterations is known, declaring a variable in loop statement .`while` loop is used when number of iterations is unknown, declaring a variable is always outside the loop.

ex : for (let i = 0; i < 10; i = i + 1) {
        if (i % 2 == 0) {
          consol.log(i);
        }
     }

 while 
     let i = 0;
      while(i < 10) {
        if (i % 2 == 0) {
          consol.log(i);
        }
        i = i + 1;
      }
         