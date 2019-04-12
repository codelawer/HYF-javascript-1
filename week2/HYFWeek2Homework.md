# <span id="Done"></span>Done according to the instructions at [HYF-JS1-Week2_Homework](https://github.com/HackYourFuture/JavaScript1/blob/master/Week2/MAKEME.md)

## Task 1

* **_Instruction_** 
1. Write a `console.log` statement saying "Hello World!" for each language that you know.

* **Solution**
```js 
console.log("Merhaba, Dünya") // Turkish
console.log("Bonjour le monde!") // French
console.log("Hallo wereld!")// Dutch
```
Notes:  ```for more information see that``` [webpage](https://www.webucator.com/blog/2010/03/saying-hello-world-in-your-language-using-javascript/)


## Task 2

* **_Instruction_** 

> 2\. Consider the following code:

```js
console.log('I'm awesome');
```

Copy the code in your `.js` file and run it. You will see that you will get a SyntaxError. Find a solution for this error. Hint: read the error message carefully, it also gives an indication of where the problem is.


  * **Error message** 
```js 
Uncaught SyntaxError: missing ) after argument list
```
* **Solution**
```js
console.log('I\'m awesome'); 
```
[TOP](#Done)
 
## Task 3

* **_Instruction_**
> 3\. Declare a variable `x` and initialize it with an integer, using these exact steps:  
3\.1 First, _declare_ your variable `x` (do not initialize it yet).  
3\.2 Add a `console.log` statement that explains in words what _you think_ the value of `x` is, like in this example:
3\.3 Add a `console.log` statement that logs the value of `x`.  
3\.4 Now _initialize_ your variable `x` with an integer.  
3\.5 Next, add a `console.log` statement that explains what _you think_ the value of `x` is.  
3\.6 Add a `console.log` statement that logs the value of `x`.  
 
 * **Solution**
 ```js 
 let x;
 console.log("the value of the x: for now \"undefined\"");
 console.log(x); // undefined
 x = 10;
 console.log("the value of my x after assignment is: " + x); // the value of my x after assignment is: 10
 console.log(x); // 10
 
 ```
[TOP](#Done)
 
 ## Task 4
* **_Instruction_**

>4\. Declare a variable `y` and assign a string to it.  
4\.1 Write a `console.log` statement in which you explain in words what _you think_ the value of the string is.  
4\.2 Now `console.log` the variable `y`.  
4\.3 Now assign a new string to the variable `y`.  
4\.4 Just like what you did before write a `console.log` statement that explains in words what you think will be logged to the console.  
4\.5 Now console.log `y` again.

 * **Solution**
```js 
let y = " "; // string
console.log("the value of \"y\" is: `string`")
console.log(y); // string
y = "something";
console.log(y); // something

```

[TOP](#Done)

## Task 5

* **_Instruction_**

> 5\. How do you round the number 7.25, to the nearest integer (i.e., whole number)?  
5\.1 Declare a variable `z` and assign the number 7.25 to it.  
5\.2 `console.log` `z`.  
5\.3 Declare another variable `a` that has the value of `z` but rounded to the nearest integer.  
5\.4 `console.log` `a`.  
5\.5 So now we have `z` and `a` find a way to compare the two values and store the highest of the two in a new variable.  
5\.6 `console.log` the highest value.

 * **Solution**
 
 ```js 
 5. Math.round(7.25); // 7
 5.1 let z = 7.25;
 5.2 console.log(z); // 7.25
 5.3 let a = Math.round(z); // 7
 5.4 console.log(a); // 7
 5.5 let highest = Math.max(z, a); //
 5.6 console.log(highest) //
 
 ```
 
 
[TOP](#Done)

## Task 6

* **_Instruction_**
> 6\. _Arrays_  
6\.1 Declare an empty array. Make sure that the name you choose indicates 'plurality', because an array is capable of containing more than one element. (See [Naming conventions](https://github.com/HackYourFuture/fundamentals/blob/master/fundamentals/naming_conventions.md)).  
6\.2 Write a `console.log` statement that explains in words what you think the value of the array is.  
6\.3 `console.log` your array.  
6\.4 Create an array that has your favorite animals inside (see if you can find a good name that exactly describes what this variable will hold).  
6\.5 Log your array.  
6\.6 Add a statement that adds Daan's favorite animal ('baby pig') to the _existing array_.  
6\.7 Log your new array!

* **Solution**
 
 ```js 
 let myArray = []; 
console.log("the value of \"myArray\" is: " +  myArray); // the value of "myArray" is: []
console.log(myArray); // []
let myFavoriteAnimals = ["dog", "cat", "crocodile", "elephant", "lion"]; 
console.log(myFavoriteAnimals); // [ 'dog', 'cat', 'crocodile', 'elephant', 'lion' ]
myFavoriteAnimals.push("baby pig"); 
console.log(myFavoriteAnimals); // [ 'dog', 'cat', 'crocodile', 'elephant', 'lion', 'baby pig' ]
console.log("Daan's favorite animal is: " + myFavoriteAnimals[5]); // Daan's favorite animal is: baby pig
 ```
[TOP](#Done)

## Task 7


* **_Instruction_**
> 7\. _More strings_  
Let's consider the following string: `let myString = "this is a test"`.  
7\.1 Add the string to your file and console.log it.  
7\.2 Find a way to get the length of `myString`.  
7\.3 `console.log` the length of `myString`.

* **Solution**
 
 ```js 
let myString = "this is a test"; 
console.log(myString);  // this is a test 
console.log(myString.length); // 14
 ``` 
 [TOP](#Done)

## Task 8

* **_Instruction_**

> 8\. Write a program that checks the types of two variables and prints out `SAME TYPE` if they are the same type.  
8\.1 First declare at least four variables and assign them different data types.  
8\.2 For each variable write a `console.log` statement that logs the value
8\.3 Now write a `console.log` statement wherein you first explain in words what you think the _type_ of your variables is.  
8\.4 Now use `typeof` to log the actual _type_ of your variables.  
8\.5 Now compare the types of your different variables with one another.  
8\.6 Make sure to also show a message when the variables you are comparing are not the same type.

* **Solution**
 

 8\.1 First declare at least four variables and assign them different data types.  
 ```js
let a = 10;
let b = "trial";
let c; // undefined
let d = true;
```
8\.2 For each variable write a `console.log` statement that logs the value
 ```js
console.log("the value of my variable a is: " + a) //the value of my variable a is: 10
console.log("the value of my variable a is: " +b) // the value of my variable a is: trial
console.log("the value of my variable a is: " +c) // the value of my variable a is: undefined
console.log("the value of my variable a is: " +d) // the value of my variable a is: true
```
8\.3 Now write a `console.log` statement wherein you first explain in words what you think the _type_ of your variables is.  
 ```js
console.log("the typof my variable a is: 'number'") //the typof my variable a is: 'number'
console.log("the typof my variable a is: 'string'") // the typof my variable a is: 'string'
console.log("the typof my variable a is: 'undefined'") // the typof my variable a is: 'undefined'
console.log("the typof my variable a is: 'boolean'") // the typof my variable a is: 'boolean'
```
8\.4 Now use `typeof` to log the actual _type_ of your variables.  
 ```js
console.log(typeof a); // number
console.log(typeof b); // string
console.log(typeof c); // undefined
console.log(typeof d); // boolean
```
8\.5 Now compare the types of your different variables with one another.  
8\.6 Make sure to also show a message when the variables you are comparing are not the same type.
 ```js
 if (typeof a == typeof b || typeof b == typeof c || typeof c == typeof d){
     console.log("These are the SAME TYPE")
} else {
     console.log("These AREN'T SAME TYPE")
}  // These AREN'T SAME TYPE
 
 ```
 
[TOP](#Done)
  
  ## Task 9

* **_Instruction_**

9\. If `x` equals 7, and the only other statement is `x = x % 3`, what would be the new value of `x`?  
9\.1 Add at least 3 `console.log` statements in which you show that you understand what `%` does.

* **Solution**
  ```js 
  let x = 7; 
  x = x % 3; // 1 
  
  console.log(x = x % 1) // 0
  console.log(x = x % 4) // 3
  console.log(x = x % 5) // 2
   ``` 
  `Notes: ` _**This is a remainder assignment. It shows the remainder after the division of the given value._**
  
[TOP](#Done)

## Task 10

* **_Instruction_**

10\. Write a program to answer the following questions:  
10\.1 Can you store multiple types in an array? Numbers and strings? Make an example that illustrates your answer.  
10\.2 Can you compare infinities? (Not in Eyad's world) - does 6/0 === 10/0? How can you test this?  
10\.3 Add `console.log` statements to the above program in which you show that you understand the concepts (just like you've done in the above assignments).

* **Solution**
  
  
[TOP](#Done)
 
