# Reference Type Exercises



### Index
* [reference exercises](#reference-exercises)
* [array exercises](#array-exercises)
* [object exercises](#object-exercises)
* [arrays vs objects](#arrays-vs-objects)
* nesting -> for week 3

---


## Reference Exercises

1. __Swap the Object & the Array__  
[on pytut](http://www.pythontutor.com/javascript.html#code=let%20obj%20%3D%20%5B%5D%3B%0Alet%20arr%20%3D%20%7B%7D%3B%0Alet%20_%20%3D%20null%3B%0A%0A//%20swap%20the%20object%20and%20the%20array&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
let obj = [];
let arr = {};
let _ = null;

// --- swap below here ---

```

  * **codelawer's solution** 
  [pytut](http://tinyurl.com/yxv5qg3x)
```js 
let obj = [];
let arr = {};
let _ = null;

// codelawer's Solution

_ = obj;
obj= arr;
arr=_;

```
[TOP](#reference-type-exercises)

---

2. __Complete this code__  
[(read this first)](https://github.com/janke-learning/reference-vs-value)  
[on pytut](http://www.pythontutor.com/javascript.html#code=%20%20let%20value_1%20%3D%205%3B%0A%20%20let%20reference_1%20%3D%20%5B%5D%3B%0A%0A%20%20let%20value_2%20%3D%20value_1%3B%0A%20%20console.assert%28value_2%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20value_1%29%3B%0A%0A%20%20let%20reference_2%20%3D%20reference_1%3B%0A%20%20console.assert%28reference_2%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20reference_1%29%3B%0A%0A%20%20%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20console.assert%28value_1%20!%3D%3D%20value_2%29%3B%20%20%0A%20%20%20%20%0A%20%20%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20console.assert%28reference_1%5B0%5D%20%3D%3D%3D%20reference_2%5B0%5D%29%3B%0A%0A%20%20//%20remove%20the%20array%20from%20memory%0A%20%20%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%20%20%3B%20//%20write%20this%20line&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
let value_1 = 5;
let reference_1 = [];

let value_2 = value_1;
console.assert(value_2 /* === or !== ? */ value_1);

let reference_2 = reference_1;
console.assert(reference_2 /* === or !== ? */ reference_1);

    ; // write this line
console.assert(value_1 !== value_2);  

    ; // write this line
console.assert(reference_1[0] === reference_2[0]);

// remove the array from memory
    ; // write this line
    ; // write this line
```


  * **codelawer's solution** [pytut](http://tinyurl.com/yxesv7ej)
```js 
  let value_1 = 5;
  let reference_1 = [];

  let value_2 = value_1;
  console.assert(value_2, /* === or !== ? */ value_1);

  let reference_2 = reference_1;
  console.assert(reference_2, /* === or !== ? */ reference_1);

  value_1 = 6; // write this line
  console.assert(value_1 !== value_2);  
    
  reference_1[0] = 1; // write this line
  console.assert(reference_1[0] === reference_2[0]);

  // remove the array from memory
    reference_1=null; // write this line
    reference_2=null; // write this line
```
[TOP](#reference-type-exercises)

---

## Array Exercises

1. __Complete the Assertions__  
[on pytut](http://www.pythontutor.com/javascript.html#code=let%20a_1%20%3D%20%5B%5D%3B%0Alet%20a_2%20%3D%20a_1%3B%0Aconsole.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0Alet%20b_1%20%3D%20%5B%5D%3B%0Alet%20b_2%20%3D%20%5B%5D%3B%0Aconsole.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A%0A//%20---%0A%0Alet%20a_1.push%283%29%3B%0Alet%20a_2.push%283%29%3B%0Aconsole.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0Alet%20b_1.push%285%29%3B%0Alet%20b_2.push%285%29%3B%0Aconsole.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A%0A&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
let a_1 = [];
let a_2 = a_1;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1 = [];
let b_2 = [];
console.assert(b_1 /* === or !== ? */ b_2);

// ---

let a_1.push(3);
let a_2.push(3);
console.assert(a_1 /* === or !== ? */ a_2);

let b_1.push(5);
let b_2.push(5);
console.assert(b_1 /* === or !== ? */ b_2);
```
  * **codelawer's solution**
[pytut](http://tinyurl.com/y5a9erc4)

```js
let a_1 = [];
let a_2 = a_1;
console.assert(a_1 === /* === or !== ? */ a_2);

let b_1 = [];
let b_2 = [];
console.assert(b_1 !== /* === or !== ? */ b_2);

// ---

 a_1.push(3);
 a_2.push(3);
console.assert(a_1 === /* === or !== ? */ a_2);

 b_1.push(5);
 b_2.push(5);
console.assert(b_1 !== /* === or !== ? */ b_2);
```
[TOP](#reference-type-exercises)

---
2. __Complete the Assertions__  
[on pytut](http://www.pythontutor.com/javascript.html#code=let%20a_1%20%3D%20%5B%5D%3B%0Alet%20a_2%20%3D%20a_1%3B%0Aconsole.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0Alet%20b_1%20%3D%20%5B%5D%3B%0Alet%20b_2%20%3D%20%5B%5D%3B%0Aconsole.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A%0A//%20---%0A%0Aconst%20key%20%3D%200%3B%0A%0Alet%20a_1%5Bkey%5D%20%3D%203%3B%0Alet%20a_2%5Bkey%5D%20%3D%203%3B%0Aconsole.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0Alet%20b_1%5Bkey%5D%20%3D%205%3B%0Alet%20b_2%5Bkey%5D%20%3D%205%3B%0Aconsole.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
let a_1 = [];
let a_2 = a_1;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1 = [];
let b_2 = [];
console.assert(b_1 /* === or !== ? */ b_2);

// ---

const index = 0;

let a_1[index] = 3;
let a_2[index] = 3;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1[index] = 5;
let b_2[index] = 5;
console.assert(b_1 /* === or !== ? */ b_2);
```
  * **codelawer's solution**
[pytut](http://tinyurl.com/y4fgwlz7)

```js
let a_1 = [];
let a_2 = a_1;
console.assert(a_1 ===  a_2);

let b_1 = [];
let b_2 = [];
console.assert(b_1 !==  b_2);

// ---

const key = 0;

 a_1[key] = 3;
 a_2[key] = 3;
console.assert(a_1 === a_2);

 b_1[key] = 5;
 b_2[key] = 5;
console.assert(b_1 !== b_2);
```
[TOP](#reference-type-exercises)

---
3. __Fill in the Blanks__  
[on pytut](http://www.pythontutor.com/javascript.html#code=%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28arr_1%20!%3D%3D%20arr_2%29%3B%0Aconsole.assert%28arr_1%5B1%5D%20%3D%3D%3D%20arr_2%5B1%5D%29%3B%0A%0Alet%20key%20%3D%200%3B%0Aconsole.assert%28arr_1%5Bkey%5D%20%3D%3D%3D%20arr_2%5Bkey%5D%29%3B%0A%0A%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28arr_1%5Barr_2%5B2%5D%5D%20%3D%3D%3D%20arr_2%5Barr_1%5B2%5D%5D%29%3B%0A%0A%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28arr_1%20%3D%3D%3D%20arr_2%29%3B%0Aconsole.assert%28arr_3%20!%3D%3D%20arr_1%29%3B%0Aconsole.assert%28arr_3%20!%3D%3D%20arr_2%29%3B%0Aconsole.assert%28arr_3%5Bkey%5D%20%3D%3D%3D%20arr_1%5B0%5D%29%3B%0A%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28obj_3%5B1%5D%20%3D%3D%3D%20obj_2%5Bkey%5D%29%3B%0A&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
    ; // write this line
    ; // write this line
console.assert(arr_1 !== arr_2);
console.assert(arr_1[1] === arr_2[1]);

let key = 0;
console.assert(arr_1[key] === arr_2[key]);

    ; // write this line
    ; // write this line
console.assert(arr_1[arr_2[2]] === arr_2[arr_1[2]]);

    ; // write this line
    ; // write this line
console.assert(arr_1 === arr_2);
console.assert(arr_3 !== arr_1);
console.assert(arr_3 !== arr_2);
console.assert(arr_3[key] === arr_1[0]);

    ; // write this line
console.assert(obj_3[1] === obj_2[key]);
```
  * **codelawer's solution**

[pytut](http://tinyurl.com/yyemal49)

```js
let arr_1 = [0, 1, 2]; // write this line
let arr_2 = [0, 1, 2]; // write this line
console.assert(arr_1 !== arr_2);
console.assert(arr_1[1] === arr_2[1]);

let key = 0;
console.assert(arr_1[key] === arr_2[key]);

arr_1[2]=1; // write this line
arr_2[2]=1; // write this line
console.assert(arr_1[arr_2[2]] === arr_2[arr_1[2]]);

arr_1=arr_2; // write this line
let arr_3 = [0]; // write this line
console.assert(arr_1 === arr_2);
console.assert(arr_3 !== arr_1);
console.assert(arr_3 !== arr_2);
console.assert(arr_3[key] === arr_1[0]);

let obj_3= ["" , 0]; // write this line
let obj_2=[0]        // write this line
console.assert(obj_3[1] === obj_2[key]);
```

[TOP](#reference-type-exercises)

---

## Object Exercises

1. __Complete the Assertions__  
[on pytut](http://www.pythontutor.com/javascript.html#code=let%20a_1%20%3D%20%7B%7D%3B%0Alet%20a_2%20%3D%20a_1%3B%0Aconsole.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0Alet%20b_1%20%3D%20%7B%7D%3B%0Alet%20b_2%20%3D%20%7B%7D%3B%0Aconsole.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A%0A//%20---%0A%0Alet%20a_1.x%20%3D%203%3B%0Alet%20a_2.x%20%3D%203%3B%0Aconsole.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0Alet%20b_1.x%20%3D%205%3B%0Alet%20b_2.x%20%3D%205%3B%0Aconsole.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A%0A&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
let a_1 = {};
let a_2 = a_1;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1 = {};
let b_2 = {};
console.assert(b_1 /* === or !== ? */ b_2);

// ---

let a_1.x = 3;
let a_2.x = 3;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1.x = 5;
let b_2.x = 5;
console.assert(b_1 /* === or !== ? */ b_2);
```
  * **codelawer's solution**
  
[pytut](http://tinyurl.com/y3maogfn)

```js
let a_1 = {};
let a_2 = a_1;
console.assert(a_1 ===  a_2);

let b_1 = {};
let b_2 = {};
console.assert(b_1 !==  b_2);

// ---

 a_1.x = 3;
 a_2.x = 3;
console.assert(a_1 === a_2);

 b_1.x = 5;
 b_2.x = 5;
console.assert(b_1 !== b_2);
```
[TOP](#reference-type-exercises)

---
2. __Complete the Assertions__  
[on pytut](http://www.pythontutor.com/javascript.html#code=%20%20let%20a_1%20%3D%20%7B%7D%3B%0A%20%20let%20a_2%20%3D%20a_1%3B%0A%20%20console.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0A%20%20let%20b_1%20%3D%20%7B%7D%3B%0A%20%20let%20b_2%20%3D%20%7B%7D%3B%0A%20%20console.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B%0A%0A%20%20//%20---%0A%20%20%0A%20%20const%20key%20%3D%20%22x%22%3B%0A%0A%20%20let%20a_1%5Bkey%5D%20%3D%203%3B%0A%20%20let%20a_2%5Bkey%5D%20%3D%203%3B%0A%20%20console.assert%28a_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20a_2%29%3B%0A%0A%20%20let%20b_1%5Bkey%5D%20%3D%205%3B%0A%20%20let%20b_2%5Bkey%5D%20%3D%205%3B%0A%20%20console.assert%28b_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20b_2%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
let a_1 = {};
let a_2 = a_1;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1 = {};
let b_2 = {};
console.assert(b_1 /* === or !== ? */ b_2);

// ---

const key = "x";

let a_1[key] = 3;
let a_2[key] = 3;
console.assert(a_1 /* === or !== ? */ a_2);

let b_1[key] = 5;
let b_2[key] = 5;
console.assert(b_1 /* === or !== ? */ b_2);
```
* **codelawer's solution**
  
[pytut](http://tinyurl.com/y4e6ne9b)

```js
  let a_1 = {};
  let a_2 = a_1;
  console.assert(a_1 === a_2);

  let b_1 = {};
  let b_2 = {};
  console.assert(b_1  !== b_2);

  // ---
  
  const key = "x";

   a_1[key] = 3;
   a_2[key] = 3;
  console.assert(a_1 === a_2);

   b_1[key] = 5;
   b_2[key] = 5;
  console.assert(b_1 !==  b_2);
``` 
[TOP](#reference-type-exercises)

---
3. __Fill in the Blanks__  
[on pytut](http://www.pythontutor.com/javascript.html#code=%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28obj_1%20!%3D%3D%20obj_2%29%3B%0Aconsole.assert%28obj_1.x%20%3D%3D%3D%20obj_2.x%29%3B%0A%0Alet%20key%20%3D%20%22y%22%3B%0Aconsole.assert%28obj_1%5Bkey%5D%20%3D%3D%3D%20obj_2%5Bkey%5D%29%3B%0A%0A%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28obj_1%5Bobj_2.y%5D%20%3D%3D%3D%20obj_2%5Bobj_1.y%5D%29%3B%0A%0A%20%20%20%20%3B%20//%20write%20this%20line%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28obj_1%20%3D%3D%3D%20obj_2%29%3B%0Aconsole.assert%28obj_3%20!%3D%3D%20obj_1%29%3B%0Aconsole.assert%28obj_3%20!%3D%3D%20obj_2%29%3B%0Aconsole.assert%28obj_3%5Bkey%5D%20%3D%3D%3D%20obj_1.y%29%3B%0A%0A%20%20%20%20%3B%20//%20write%20this%20line%0Aconsole.assert%28obj_3.x%20%3D%3D%3D%20obj_2%5Bkey%5D%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
    ; // write this line
    ; // write this line
console.assert(obj_1 !== obj_2);
console.assert(obj_1.x === obj_2.x);

let key = "y";
console.assert(obj_1[key] === obj_2[key]);

    ; // write this line
    ; // write this line
console.assert(obj_1[obj_2.y] === obj_2[obj_1.y]);

    ; // write this line
    ; // write this line
console.assert(obj_1 === obj_2);
console.assert(obj_3 !== obj_1);
console.assert(obj_3 !== obj_2);
console.assert(obj_3[key] === obj_1.y);

    ; // write this line
console.assert(obj_3.x === obj_2[key]);
```
* **codelawer's solution**
  
[pytut](http://tinyurl.com/y5fv5j6x), [second](http://tinyurl.com/yyxvgpbt)

```js
let obj_1= {}; // write this line
let obj_2= {}; // write this line
console.assert(obj_1 !== obj_2);
console.assert(obj_1.x === obj_2.x);

let key = "y";
console.assert(obj_1[key] === obj_2[key]);

obj_1=[key]; // write this line
obj_2=[key]; // write this line
console.assert(obj_1[obj_2.y] === obj_2[obj_1.y]);

obj_1 = obj_2; // write this line
let obj_3 = [key]; // write this line
console.assert(obj_1 === obj_2);
console.assert(obj_3 !== obj_1);
console.assert(obj_3 !== obj_2);
console.assert(obj_3[key] === obj_1.y);

const x = "y"; // write this line
console.assert(obj_3.x === obj_2[key]);
``` 
[TOP](#reference-type-exercises)

---

## Comparison Exercises

1. __Swap 'em__  
[on pytut](http://www.pythontutor.com/javascript.html#code=const%20obj%20%3D%20%7Bprop%3A%20%22array%22%7D%3B%0Aconst%20arr%20%3D%20%5B%22object%22%5D%3B%0Alet%20_%20%3D%20null%3B%0A%0A//%20swap%20the%20values%20stored%20in%20each%20structure%0A//%20%20using%20dot%20notation%20for%20the%20object%0A//%20%20using%20direct%20access%20for%20the%20array&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)
```js
const obj = {prop: "array"};
const arr = ["object"];
let _ = null;

// swap the values stored in each structure
//  using dot notation for the object
//  using direct access for the array
```
* **codelawer's solution**
  
[pytut](http://tinyurl.com/yx947qq9) or [this](http://tinyurl.com/y6fj8nes)

```js
const obj = {prop: "array"};
const arr = ["object"];
let _ = null;

// 1. swap the values stored in each structure
// 2. using dot notation for the object
// 3. using direct access for the array

//First Solution
/*
_ = arr[0];
arr[0]=obj.prop;
obj.prop=_;
*/

//Second Solution
_ = obj.prop;
obj.prop=arr[0]; //if you don't add [0] value will be "arr" and if you  change later "arr", "obj.prop" also changed. This is the meaning of 3rd instruction.
arr[0]=_;


/*_ = arr;
arr[0]=obj.prop

oR

_ = obj;
obj.prop=arr;
*/
``` 

Notes : ``` Understanding of the meaning of the direct access of the value is important. If you don't direct access of the value,  the value inside underscor change automatically. becasue it is not primitive. Both "arr" and "obj" are objects.This is the meaning of instruction 3rd.```

[TOP](#reference-type-exercises)

---

2. __Swap 'em__  
[on pytut](http://www.pythontutor.com/javascript.html#code=const%20obj%20%3D%20%7Bprop%3A%20%22array%22%7D%3B%0Aconst%20arr%20%3D%20%5B%22object%22%5D%3B%0Alet%20_%20%3D%20null%3B%0A%0A//%20swap%20the%20values%20stored%20in%20each%20structure%0A//%20%20using%20bracket%20notation%20for%20the%20object%0A//%20%20using%20variable%20access%20for%20the%20array%0Aconst%20obj_key%20%3D%20%3B%0Aconst%20arr_index%20%3D%20%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
```js
const obj = {prop: "array"};
const arr = ["object"];
let _ = null;

// swap the values stored in each structure
//  using bracket notation for the object
//  using variable access for the array
const obj_key = ;
const arr_index = ;
```
* **codelawer's solution**
  
[pytut](http://tinyurl.com/y2jph4lp)

```js
const obj = {prop: "array"};
const arr = ["object"];
let _ = null;

// swap the values stored in each structure
//  using bracket notation for the object
//  using variable access for the array

const obj_key = "prop" ;
const arr_index = 0;

// First Option
/*
_ = obj[obj_key];
obj.prop = arr[arr_index];
arr[arr_index] = _;
*/

//Second option

_ = arr[arr_index];
arr[arr_index] = obj[obj_key];
obj[obj_key]= _;
``` 
[TOP](#reference-type-exercises)

---

3. __Relative vs Absolute__  
[on pytut](http://www.pythontutor.com/javascript.html#code=//%20array%20indices%20are%20relative%0Aconst%20arr%20%3D%20%5B%22a%22,%20%22b%22%5D%3B%0Aconst%20index%20%3D%200%3B%0A%0Aconst%20read_arr_1%20%3D%20arr%5Bindex%5D%3B%0Aarr.shift%28%29%3B%20//%20removes%20the%20first%20item%0Aconst%20read_arr_2%20%3D%20arr%5Bindex%5D%3B%0A%0Aconsole.assert%28read_arr_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20read_arr_2%29%3B%0A%0A//%20object%20keys%20are%20absolute%0Aconst%20obj%20%3D%20%7Bx%3A%20%22a%22,%20y%3A%20%22b%22%7D%3B%0Aconst%20key%20%3D%20%22y%22%3B%0A%0Aconst%20read_obj_1%20%3D%20obj%5Bkey%5D%3B%0Adelete%20obj.x%3B%0Aconst%20read_obj_2%20%3D%20obj%5Bkey%5D%3B%0A%0Aconsole.assert%28read_obj_1%20/*%20%3D%3D%3D%20or%20!%3D%3D%20%3F%20*/%20read_obj_2%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
```js
// array indices are relative
const arr = ["a", "b"];
const index = 0;

const read_arr_1 = arr[index];
arr.shift(); // removes the first item
const read_arr_2 = arr[index];

console.assert(read_arr_1 /* === or !== ? */ read_arr_2);

// object keys are absolute
const obj = {x: "a", y: "b"};
const key = "y";

const read_obj_1 = obj[key];
delete obj.x;
const read_obj_2 = obj[key];

console.assert(read_obj_1 /* === or !== ? */ read_obj_2);
```
* **codelawer's solution**
  
[pytut](http://tinyurl.com/y6yaqhun)

```js
// array indices are relative
const arr = ["a", "b"];
const index = 0;

const read_arr_1 = arr[index];
arr.shift(); // removes the first item
const read_arr_2 = arr[index];

console.assert(read_arr_1 !== read_arr_2);

// object keys are absolute
const obj = {x: "a", y: "b"};
const key = "y";

const read_obj_1 = obj[key];
delete obj.x;
const read_obj_2 = obj[key];

console.assert(read_obj_1 ===  read_obj_2);
``` 
[TOP](#reference-type-exercises)

---

## Nesting

-> coming in week 3


[TOP](#reference-type-exercises)

___
___
### <a href="https://github.com/codelawer" target="_blank"><img src="http://tinyurl.com/y5a3eyoo" width="60" height="40"></img> codeLawer</a>
