#  Done according to the [janke-learning/variables-and-hoisting](http://bit.do/eNKNK)

## Exercises

* challenges (**swaps**) <br>
It can be done the number of lines and  different ways. 
First of all assign a value to **extra holder variable(s)** in order to store that value inside that;
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

1. without extra holder variables

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

b. [eating meat every meal](http://tinyurl.com/yyrg2bcc)

```js
// eating meat every meal

// we give you this
let _1 = ' ', _2 = ' ', _3 = ' ', _4 = ' ', _5 = ' ', _6= ' ';

// -- you write this --

// eating
_1="e", _2="a", _3="t", _4="i", _5="n", _6="g"
// meat
_1="m",_2="e", _3="a",_4="t", _5=" "; _6=" ";
// every
_1="e", _2="v", _3=_1, _4="r", _5="y";
// meal
_1="m", _2=_3, _3="a", _4="l", _5=" ";

```

c. [many men may melt my mind](http://tinyurl.com/y5qf6z38)

```js 
// many men may melt my mind

// we give you this
let _1 = ' ', _2 = ' ', _3 = ' ', _4 = ' ';

// -- you write this --

// many
_1="m", _2="a", _3="n", _4="y";
// men
_2="e", _4=" ";
// may
_2="a", _3="y";
// melt
_2="e",_3="l", _4="t";
// my
_2="y", _3=" ", _4=" ",
// mind

_2="i", _3="n", _4="d";
```

d.[if fir trees ever fall](http://tinyurl.com/y4zm689e)
```js

// if fir trees ever fall

// we give you this
let _1 = ' ', _2 = ' ', _3 = ' ', _4 = ' ', _5 = ' ';

// -- you write this --

// if
_1="i", _2="f";
// fir
_1=_2, _2="i", _3="r";
// trees
_1="t", _2=_3, _3="e", _4=_3, _5="s";
// ever
_1=_3, _2="v", _4="r", _5=" ";
// fall
_1="f", _2="a", _3="l", _4=_3;

```

2. with extra holder variables

a. [the toad reads me](http://tinyurl.com/y2l8gart)

```js


// we give you this
let _1 = " ", _2 = " ", _3 = " ", _4 = " ", _5 = " ";
let x = ' ', y = ' ';

// -- I wrote this --

// the
_1="t", _2="h", _3="e";
// toad
_2="o", x=_3, _3="a", _4="d";
// reads
_1="r", _2=x, _5="s";
// me
_1="m", _3=" ", _4=" " , _5= " ";
```

b. [eating meat every meal](http://tinyurl.com/y4yd5qyv)

```js


// we give you this
let _1 = ' ', _2 = ' ', _3 = ' ', _4 = ' ', _5 = ' ', _6= ' ';
let x = ' ', y = ' ';

// -- I wrote this --

// eating
_1="e", _2="a", _3="t", _4="i", _5="n", _6="g";
// meat
x=_1, y=_2, _1="m", _2=x, _3=y, _4="t", _5=" ", _6=" ";

// every
_1=x,_2="v", _3=x, _4="r", _5="y";

// meal
_1="m", _2=x, _3=y, _4="l", _5=" ";
```

c. [ many men may melt my mind](http://tinyurl.com/y5rkrk68)
```js


// we give you this
let _1 = ' ', _2 = ' ', _3 = ' ', _4 = ' ';
let x, y;
// -- I wrote this --

// many
_1="m", _2="a", _3="n", _4="y";
// men
x=_2, y=_4;
_2="e", _4=" "; 
// may
_2= x, _3=y;
// melt
_2="e", _3="l", _4="t";

// my
_2=y, _3=" ", _4= " ";
// mind
_2="i", _3="n", _4="d";
```

d. [if fir trees ever fall](http://tinyurl.com/yxvaubwv)
```js


// we give you this
let _1 = ' ', _2 = ' ', _3 = ' ', _4 = ' ', _5 = ' ';
let x = ' ', y = ' '; // to save extra values for later

// -- I wrote this --

// if
_1="i", _2="f";
// fir
x=_1;
_1=_2, _2=x, _3="r";
// trees
x=_1;
_1="t", _2=_3, _3="e", _4=_3, _5="s";
// ever
y=_3;
_1=_3, _2="v",_3=y, _4="r", _5=" ";
// fall
_1=x, _2="a", _3="l", _4="l";
```
