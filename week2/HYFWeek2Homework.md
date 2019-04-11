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
 
 ```
[TOP](#Done)
