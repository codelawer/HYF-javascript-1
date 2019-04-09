# Done according to the [janke-learning-errors](https://github.com/janke-learning/errors)


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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
```
your notes:

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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
```
your notes:

[TOP](#errors)

---
## improper nested quotes 1
broken code:
```js
let innerHtml = "<p>Click here to <a href="#Home">return home</a></p>";
```
error message:
```
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
```
your notes:

[TOP](#errors)

---
## improper nested quotes 2 
broken code:
```js
let nested_messages = 'remind yourself ''i can do this!'' at least once a day';
```
error message:
```
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
```
your notes:

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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
```
your notes:

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
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
```
your notes:



[TOP](#errors)

