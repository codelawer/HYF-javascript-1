# Functions



### Index

* exercises
    * [number 1](#1)
    * [number 2](#2)
    * [number 3](#3)
    * [number 4](#4)
    * [number 5](#5)
    * [number 6](#6)
    * [number 7](#7)
    * [number 8](#8)

---


## Exercises

### 1

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1,%20param_2,%20param_3%29%20%7B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A//%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22,%20arg_2%20%3D%20%22%22,%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1,%20arg_2,%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22zyx%22,%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1,%20param_2,%20param_3%29%20%7B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A//%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22,%20arg_2%20%3D%20%22%22,%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1,%20arg_2,%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22zyx%22,%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)
```js
{   // 1
  function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "zyx", "1: return_val === " + return_val);
}
```

   * codelawer's solution, [pytut](http://tinyurl.com/y3s9p3dx)

```js
function f(param_1, param_2, param_3) {
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "y", arg_2 = "x", arg_3 = "z";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "zyx", "return_val === " + return_val);

```

[TOP](#Functions)

---

### 2

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A%2F%2F%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22%2C%20arg_2%20%3D%20%22%22%2C%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22yxz%22%2C%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)    
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A%2F%2F%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22%2C%20arg_2%20%3D%20%22%22%2C%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22yxz%22%2C%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)
```js
{  // 2
  function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "yxz", "2: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/y69cqvzb)

```js
function f(param_1, param_2, param_3) {
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "x", arg_2 = "z", arg_3 = "y";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "yxz", "return_val === " + return_val);
```
[TOP](#Functions)

--- 
### 3

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20%20var%20_%20%3D%20param_2%3B%0A%20%20param_2%20%3D%20param_1%3B%0A%20%20param_1%20%3D%20_%3B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A%2F%2F%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22%2C%20arg_2%20%3D%20%22%22%2C%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22yxz%22%2C%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)   
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20%20var%20_%20%3D%20param_2%3B%0A%20%20param_2%20%3D%20param_1%3B%0A%20%20param_1%20%3D%20_%3B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A%2F%2F%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22%2C%20arg_2%20%3D%20%22%22%2C%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22yxz%22%2C%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)
```js
{  // 3
  function f(param_1, param_2, param_3) {
    var _ = param_2;
    param_2 = param_1;
    param_1 = _;
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "yxz", "3: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/y4k5vaud)

```js
function f(param_1, param_2, param_3) {
  var _ = param_2;
  param_2 = param_1;
  param_1 = _;
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "z", arg_2 = "x", arg_3 = "y";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "yxz", "return_val === " + return_val);
```
[TOP](#Functions)

--- 
### 4

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20%20var%20_%20%3D%20param_2%3B%0A%20%20param_2%20%3D%20param_3%3B%0A%20%20param_3%20%3D%20_%3B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A%2F%2F%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22%2C%20arg_2%20%3D%20%22%22%2C%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xyz%22%2C%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&mode=edit&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20%20var%20_%20%3D%20param_2%3B%0A%20%20param_2%20%3D%20param_3%3B%0A%20%20param_3%20%3D%20_%3B%0A%20%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20%20return%20result%3B%0A%7D%3B%0A%0A%2F%2F%20set%20values%20in%20the%20args%20to%20pass%20the%20assert%0Alet%20arg_1%20%3D%20%22%22%2C%20arg_2%20%3D%20%22%22%2C%20arg_3%20%3D%20%22%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xyz%22%2C%20%22return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)
```js
{  // 4
  function f(param_1, param_2, param_3) {
    var _ = param_2;
    param_2 = param_3;
    param_3 = _;
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "xyz", "4: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/yy6ngm49)

```js
function f(param_1, param_2, param_3) {
  var _ = param_2;
  param_2 = param_3;
  param_3 = _;
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "y", arg_2 = "x", arg_3 = "z";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "xyz", "return_val === " + return_val);
```
[TOP](#Functions)

--- 
### 5

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20x%20%3D%20%22x%22%2C%20y%20%3D%20%22y%22%2C%20z%20%3D%20%22z%22%3B%0Alet%20return_val%20%3D%20f%28%2F*%20pass%20x%2C%20y%20%26%20z%20in%20the%20right%20order%20*%2F%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xyz%22%2C%20%225%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)   
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20param_3%20%2B%20param_1%20%2B%20param_2%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20x%20%3D%20%22x%22%2C%20y%20%3D%20%22y%22%2C%20z%20%3D%20%22z%22%3B%0Alet%20return_val%20%3D%20f%28%2F*%20pass%20x%2C%20y%20%26%20z%20in%20the%20right%20order%20*%2F%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xyz%22%2C%20%225%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)  
```js
{  // 5
   function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
   };

   let x = "x", y = "y", z = "z";
   let return_val = f(/* pass x, y & z in the right order */);

   console.assert(return_val === "xyz", "5: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/yyr7mgkk)

```js
function f(param_1, param_2, param_3) {
 var result = param_3 + param_1 + param_2;
 return result;
};

let x = "x", y = "y", z = "z";
let return_val = f(y, z, x);

console.assert(return_val === "xyz", "5: return_val === " + return_val);
```
[TOP](#Functions)

--- 
### 6

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20param_2%20%2B%20param_1%20%2B%20param_3%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20x%20%3D%20%22x%22%2C%20y%20%3D%20%22y%22%2C%20z%20%3D%20%22z%22%3B%0Alet%20return_val%20%3D%20f%28%2F*%20pass%20x%2C%20y%20%26%20z%20in%20the%20right%20order%20*%2F%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xzy%22%2C%20%226%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20param_2%20%2B%20param_1%20%2B%20param_3%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20x%20%3D%20%22x%22%2C%20y%20%3D%20%22y%22%2C%20z%20%3D%20%22z%22%3B%0Alet%20return_val%20%3D%20f%28%2F*%20pass%20x%2C%20y%20%26%20z%20in%20the%20right%20order%20*%2F%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xzy%22%2C%20%226%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B) 
```js
{  // 6
   function f(param_1, param_2, param_3) {
    var result = param_2 + param_1 + param_3;
    return result;
   };

   let x = "x", y = "y", z = "z";
   let return_val = f(/* pass x, y & z in the right order */);

   console.assert(return_val === "xzy", "6: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/y2de6lur)

```js
function f(param_1, param_2, param_3) {
 var result = param_2 + param_1 + param_3;
 return result;
};

let x = "x", y = "y", z = "z";
let return_val = f(z, x ,y);

console.assert(return_val === "xzy", "6: return_val === " + return_val);
```
[TOP](#Functions)

--- 
### 7

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20%2F*%20arrange%20the%20params%20to%20pass%20the%20assert%20*%2F%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20arg_1%20%3D%20%22z%22%2C%20arg_2%20%3D%20%22y%22%2C%20arg_3%20%3D%20%22x%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xzy%22%2C%20%227%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20%2F*%20arrange%20the%20params%20to%20pass%20the%20assert%20*%2F%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20arg_1%20%3D%20%22z%22%2C%20arg_2%20%3D%20%22y%22%2C%20arg_3%20%3D%20%22x%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22xzy%22%2C%20%227%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)  
```js
{  // 7
   function f(param_1, param_2, param_3) {
    var result = /* arrange the params to pass the assert */;
    return result;
   };

   let arg_1 = "z", arg_2 = "y", arg_3 = "x";
   let return_val = f(arg_1, arg_2, arg_3);

   console.assert(return_val === "xzy", "7: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/y3uxrf8u)

```js
function f(param_1, param_2, param_3) {
 var result = param_3 + param_1 + param_2;
 return result;
};

let arg_1 = "z", arg_2 = "y", arg_3 = "x";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "xzy", "7: return_val === " + return_val);
```
[TOP](#Functions)

--- 
### 8

[on pytut](http://www.pythontutor.com/javascript.html#code=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20%2F*%20arrange%20the%20params%20to%20pass%20the%20assert%20*%2F%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20arg_1%20%3D%20%22z%22%2C%20arg_2%20%3D%20%22y%22%2C%20arg_3%20%3D%20%22x%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22yxz%22%2C%20%228%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B&curInstr=0&mode=display&origin=opt-frontend.js&py=js&rawInputLstJSON=%5B%5D)  
[parsonized](http://janke-learning.github.io/parsonizer/?snippet=function%20f%28param_1%2C%20param_2%2C%20param_3%29%20%7B%0A%20var%20result%20%3D%20%2F*%20arrange%20the%20params%20to%20pass%20the%20assert%20*%2F%3B%0A%20return%20result%3B%0A%7D%3B%0A%0Alet%20arg_1%20%3D%20%22z%22%2C%20arg_2%20%3D%20%22y%22%2C%20arg_3%20%3D%20%22x%22%3B%0Alet%20return_val%20%3D%20f%28arg_1%2C%20arg_2%2C%20arg_3%29%3B%0A%0Aconsole.assert%28return_val%20%3D%3D%3D%20%22yxz%22%2C%20%228%3A%20return_val%20%3D%3D%3D%20%22%20%2B%20return_val%29%3B)  
```js
{  // 8
   function f(param_1, param_2, param_3) {
    var result = /* arrange the params to pass the assert */;
    return result;
   };

   let arg_1 = "z", arg_2 = "y", arg_3 = "x";
   let return_val = f(arg_1, arg_2, arg_3);

   console.assert(return_val === "yxz", "8: return_val === " + return_val);
}
```
   * codelawer's solution, [pytut](http://tinyurl.com/y6b638kr)

```js
function f(param_1, param_2, param_3) {
 var result = param_2 + param_3 + param_1;
 return result;
};

let arg_1 = "z", arg_2 = "y", arg_3 = "x";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "yxz", "8: return_val === " + return_val);
```
[TOP](#Functions)
___
___
### <a href="https://github.com/codelawer" target="_blank"><img src="http://tinyurl.com/y5a3eyoo" width="60" height="40"></img> codeLawer</a>
