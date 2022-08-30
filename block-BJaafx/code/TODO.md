1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
const arr = [1, 2, 3, 4, 5,6,7,8,9,10];
const average = arr.reduce((a, b) => a + b, 0) / arr.length;
console.log(average); // 55 output

```
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
no output
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js
const max =10;
function getEvenSum(max)  
    {  
        let i, sum = 0;  
        for (i = 2; i <= max; i+=2) {  
            sum += i;  
        }  
        return sum;  
    }  

```
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js

const max =10;
function getOddSum(max)  
    {  
        let i, sum = 0;  
        for (i = 1; i <= max; i+=2) {  
            sum += i;  
        }  
        return sum;  
    }  
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

```js
function getProduct(n)
{
    let product = 1;
 
    while (n != 0)
    {
        product = product * (n % 10);
        n = Math.floor(n / 10);
    }return product;
    while (n = 0){
      return `valid baleu`
    }
}

```

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

check(10); // output
check(1); // output
check(5); // output
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
getOutput('John'); // what will be the output
getOutput(); // what will be the output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.