# <span id="errors"></span>Done according to the [janke-learning-errors](https://github.com/janke-learning/errors)


## Exercises

### malformed while loop

broken code:
```js
let value = 0;
while (value < 9) 
  value++;
};
```
error message:
```
Uncaught SyntaxError: Unexpected token }
```
classification:
* creation phase
* syntax

the fix:
```js
let value = 0;
while (value < 9) {
  value++;
};
```
your notes:

[TOP](#errors)

---

### missing variable name
broken code:
```js
var = 5;
```
error message:
```js
Uncaught SyntaxError: Unexpected token =
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
var a = 5;
```
your notes:

[TOP](#errors)

---

## too-far object access
broken code:
```js
let a = {b:3};
let b = a.b.3
```
error message:
```
Uncaught SyntaxError: Unexpected number
```
classification:
* creation phase 
* syntax

the fix:
```js

????

let a = {b:3};
let b = a.b;
```


[TOP](#errors)

---
## access property directly
broken code:
```js
let x = {b:'e'};
let y = b.e;
```
error message:
```
ReferenceError: b is not defined
```
classification:
* creation phase 
* syntax

the fix:
```js
let x = {b:'e'};
let y = x.b;
```
your notes:

[TOP](#errors)

---
## improper multi-line string
broken code:
```js
let a = 'this is 
two lines';
```
error message:
```
SyntaxError: Unexpected token ILLEGAL

```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let a = 'this is\n two lines';
```
your notes:

[TOP](#errors)

---
## improper end of statement
broken code:
```js
let a = 1:
```
error message:
```
SyntaxError: Unexpected token :

```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let a = 1;
```
your notes:

[TOP](#errors)

---
## malformed array
broken code:
```js
let myArray = [1, 2, 3;
```
error message:
```
SyntaxError: Unexpected token ;

```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let myArray = [1, 2, 3];
```
your notes:

[TOP](#errors)

---
## missing arguments
broken code:
```js
function getNine {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
error message:
```
SyntaxError: Unexpected token {
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
function getNine () {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
your notes: added `()` brackets before `{}` curly brackets.

[TOP](#errors)

---
## improper nested quotes 1
broken code:
```js
let innerHtml = "<p>Click here to <a href="Home">return home</a></p>";
```
error message:
```
SyntaxError: Unexpected token ILLEGAL

```
classification:
* creation phase 
* syntax 

the fix:
```js
let innerHtml = "<p>Click here to <a href=\"#Home\">return home</a></p>";

```
your notes: set a \ before you escape

[TOP](#errors)

---
## improper nested quotes 2 
broken code:
```js
let nested_messages = 'remind yourself ''i can do this!'' at least once a day';
```
error message:
```
SyntaxError: Unexpected string

```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let nested_messages = 'remind yourself \'i can do this!\' at least once a day';

or 

let nested_messages = 'remind yourself "i can do this!" at least once a day';

```
your notes:

[TOP](#errors)

---
## reassigning to constant
broken code:
```js
const a = 9;
a = 0;
```
error message:
```
TypeError: Assignment to constant variable.

```
classification:
* **creation phase** or execution phase ?
* syntax or **semanitc** ?

the fix:
```js
const a = 9;
```
your notes: `const` can not be reassigned.

[TOP](#errors)

---
## unassigned const declaration
broken code:
```js
const a;
a = 0;
```
error message:
```
SyntaxError: Missing initializer in const declaration

```
classification:
* **creation phase** or execution phase ?
* syntax or **semanitc** ?

the fix:
```js
const a=0;
```
your notes: const value should assigned initial. because it can not be changable later on.

[TOP](#errors)

---
## is not a function
broken code:
```js
let array = [];
array.length()
```
error message:
```
TypeError: array.length is not a function

```
classification:
* **creation phase** or execution phase ?
* **syntax** or semanitc ?

the fix:
```js
let array = [];
array.length;
```
your notes: array is not defined a function. the bracket at the end of the length should be deleted.



[TOP](#errors)

