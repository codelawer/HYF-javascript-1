#  Done according to the [janke-learning/variables-and-hoisting](http://bit.do/eNKNK)

## Exercises

* challenges (**swaps**) <br>
It can be done the number of lines and  different ways. 
First of all assign a variable to "underscore" in order to store that value inside that;
After that starting from the first assignment it can be changed respectively. 
And at the end assign the last one.

i. [the first](http://bit.do/eNKEP)
```js 
let a = "b";
let b = "a";
let _ = " ";

//first option
/*

_ = b;
b=a;
a=_;

*/

//second option

_=a;
a=b;
b=_;
```
ii. [the second](http://tinyurl.com/y63mdt8w)

```js

let a = "c", 
b = "a", 
c = "b";
let _ = ' ';


// can be done in 4 lines

//first option
/*
_ = b;
b=c;
c=a;
a=_;

*/


//second option 
/*

_=a;
a=b;
b=c;
c=_;

*/


//third option
_ = c;
c=a;
a=b;
b=_;

```

iii. [the third](http://tinyurl.com/y62lq6os)
```js 
let a = "d", b = "a", c = "b", d = "c";
let _ = ' ';

// can be done in 5 lines



//First option

/*
_= a;
a=b;
b=c;
c=d;
d=_;
*/

//Second Option

_=b;
b=c;
c=d;
d=a;
a=_;

//...

```

iv. [the fourth](http://tinyurl.com/y6esaocj) 
```js 

let a = "z", b = "y", c = "x", d = "w";
let _ = ' ';

// can be done in 6 lines
//First Option 
/*
_=a;
a=d;
d=_;
_=b;
b=c;
c=_;
*/

//Second Option
_=b;
b=c;
c=_;
_=d;
d=a;
a=_;

```

v. [the fifth](http://tinyurl.com/y45x9w9m)

```js
let a = "z", b = "y", c = "x", d = "w", e = "v";
let _ = ' ';

// can be done in 6 lines and 5 different ways.

_=e;
e=a;
a=_;
_=d;
d=b;
b=_;

```


* challenges (**sentences**) <br>

** without extra holder variables

a. [the toad reads me](http://tinyurl.com/yxdza46u)

```js
// the toad reads me

// we give you this
let _1 = " ", _2 = " ", _3 = " ", _4 = " ", _5 = " ";

// -- you write this --

// the
_1="t", _2="h", _3="e"; 
// toad
_2="o", _3="a", _4="d";
// reads
_1="r", _2="e", _5="s";
// me
_1="m";_3=" "; _4=" ";_5=" ";

```

